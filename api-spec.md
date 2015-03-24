# Doges

## Create New Doge

This endpoint creates a new doge.

### HTTP Request

`POST http://example.com/api/doges`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
name | "Ralph" | If specified, the new doge will be given this name.
cute | true | If set to false, the doge will have a cuteness level of zero.

```shell
curl -XPOST "http://example.com/api/doges"
  -H "Authorization: woffwoff"
```

> The above command returns JSON structured like this:

```json
{
  "id": 1,
  "name": "Ralph",
  "breed": "unknown",
  "fluffiness": 10,
  "cuteness": 0
}
```
