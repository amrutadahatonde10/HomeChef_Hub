# WishList View API 
```
GET /user/wishlist/view
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
``` json
{
    "username": "string"
}
```
## Response
```
Body
{
    "message": 'Success'
}

```
200 - Success

400 - Bad Request 

500 - Internal Server Error
