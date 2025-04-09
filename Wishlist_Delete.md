# WishList Delete API 
```
DELETE /user/wishlist/delete
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
``` json
{
    "id": "int",
    "username": "string",
}
```
## Response
```
Body
{
    "message": "Recipe Deleted Successfully!"
}

```
200 - Success

400 - Bad Request 

500 - Internal Server Error
`