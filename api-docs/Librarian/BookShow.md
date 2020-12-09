#### Show specific book

```Request Header: 
    Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9
    .eyJpZCI6IjVmNjFjNGQzYTAzM2VmNDFmYTc1MTA0MSIsIm5hbWUiOiJNYW11biIsInJvbGUiOiJ1c2VyIiwiaWF0IjoxNjAwMjQ0NTM2LCJleHAiOjE2MDAzMzA5MzZ9
    .MQvTafbRGlI8sQN1BRLH4GlQPCtwDoRQdEb_TyTY_sY

Request Params:
{ 
    "id": "5fcbd8d5221a7a576bafb39e"
}

Response Body:
{
    "id": "5fcae64affc7f92df964b050",
    "bookName": "Node.js test x",
    "author": "test author",
    "genre": "test gener",
    "releaseDate": "12.8.2020",
    "bookImage": "http://localhost:4000/uploads/books/1607196095326.jpg",
    "status": "activate",
    "students": [
        "5fc90e7ea9c52e37057ada5c"
    ]
}

status code:
Success: 200

Error: Token error