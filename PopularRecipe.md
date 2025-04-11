# Popular Recipe API 
```
GET /user/recipe/popular
```

### Request Headers
```
Content-Type : application/json
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
    "recipeName": "string"
}
```
200 - Success

400 - Bad Request 

500 - Internal Server Error
