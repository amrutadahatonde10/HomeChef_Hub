# WishList Add API 
```
POST /user/wishlist/add
```

### Request Headers
```
Content-Type : application/json
Bearer <Token>

```

### Request Body
``` json
{
    "recipe_id": "int"
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
