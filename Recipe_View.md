# Recipe View API 
```
GET /user/recipe/view
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
```
```

## Response
``` json
{
    {
        "id": "int",
        "recipeImage": "string",
        "rating": "int",
        "recipeName": "string",
        "time": "int",
        "category": "string",
        "ingredients": "string"
    },{
        "id": "int",
        "recipeImage": "string",
        "rating": "int",
        "recipeName": "string",
        "time": "int",
        "category": "string",
        "ingredients": "string"
    }...
}
```
200 - Success

400 - Bad Request 

500 - Internal Server Error
