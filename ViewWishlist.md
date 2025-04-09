# WishList View API 
```
POST /wishlist/view
```

### Request Headers
```
Content-Type : application/json
Bearer <Token>
```

### Request Body
``` 
{
}
```
## Response
```json
{
    "id": "int",
    "recipeImage": "string",
    "rating": "int",
    "recipeName": "string",
    "time": "int",
    "category": "string",
    "ingredients": "string"
}

```
200 - Success

400 - Bad Request 

500 - Internal Server Error
