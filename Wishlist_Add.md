# WishList Add API 
```
POST /user/wishlist/add
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
``` json
{
    "recipe_id": "int",
    "username": "string"
}
```
## Response
```
Body
{
    "message": "Recipe Added Successfully!"
}

```
200 - Success

400 - Bad Request 

500 - Internal Server Error
