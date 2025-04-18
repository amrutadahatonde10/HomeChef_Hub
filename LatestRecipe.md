# Latest Recipes API 
```
GET /user/recipe/latest
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
``` json
{
    "id": "int",
    "recipeImage": "string",
    "recipeName": "string"
}

```
200 - Success

400 - Bad Request 

500 - Internal Server Error
