#Microservice Product

### Endpoints:

#### Save Product
````
POST /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:pasword)
Content-Type: application/json
Cookie: JSESSIONID=4FE249A85D26EF6E29DC157B74DD5D38
Content-Length: 45

{
    "name":"test-1",
    "price":1.2

}
````

#### Get Products

````
GET /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:pasword)
Content-Type: application/json
Cookie: JSESSIONID=4FE249A85D26EF6E29DC157B74DD5D38
Content-Length: 45

{
    "name":"test-1",
    "price":1.2

}
````

#### Delete Product

````
DELETE /api/product/1 HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:pasword)
Cookie: JSESSIONID=4FE249A85D26EF6E29DC157B74DD5D38
````