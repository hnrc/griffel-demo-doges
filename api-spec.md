# Doges

## Create New Doge

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

This endpoint creates a new doge.

### HTTP Request

`POST http://example.com/api/doges`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
name | "Ralph" | If specified, the new doge will be given this name.
cute | true | If set to false, the doge will have a cuteness level of zero.

Chocolate cake cookie pie halvah liquorice cheesecake chocolate carrot cake. Cotton candy icing sesame snaps muffin tiramisu halvah fruitcake cheesecake. Tart apple pie bonbon powder. Candy chocolate bar soufflé jujubes icing muffin dessert chocolate croissant. Tart apple pie gingerbread pastry jujubes cake tiramisu donut. Marzipan lemon drops ice cream liquorice sesame snaps. Faworki brownie icing fruitcake cupcake donut. Soufflé jelly macaroon candy canes oat cake gummi bears. Cupcake carrot cake lollipop toffee.
