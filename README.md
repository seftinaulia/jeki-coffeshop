curl --location -g '{{url}}/cakes'

{
  "status": "DATA_NOT_FOUND",
  "message": "Cake is not found",
  "data": null
}

{
  "status": "SUCCESS",
  "message": "Detail cake",
  "data": {
    "id": 2,
    "title": "Black Forest Cherry Cake",
    "description": "This type of cake is very traditional from the south-east of Germany, the Black Forest region. Although it is widely believed that the original form of this type of cake comes from Switzerland, Germans have perfected it and made it as famous as it is nowadays.",
    "rating": 6.5,
    "image": "https://thethingswellmake.com/wp-content/uploads/2013/07/14-traditional-cakes-from-around-the-world-Black-Forest-Cake41.jpg",
    "created_at": "2020-02-01 10:56:31",
    "updated_at": "2020-02-13 09:30:23"
  }
}
curl --location -g --request POST '{{url}}/cakes' \
--data ''
{
  "status": "SUCCESS",
  "message": "Cake submitted",
  "data": null
}
curl --location -g --request DELETE '{{url}}/cakes/{{id}}' \
--data ''
{
  "status": "SUCCESS",
  "message": "Cake submitted",
  "data": null
}



# jeki-coffeshop
