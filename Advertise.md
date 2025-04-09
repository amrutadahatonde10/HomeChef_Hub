# Advertise API 
```
GET /user/recipe/advertise
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
``` 
```

## Response
```json
{
    {
        "id": "int",
        "image": "string",
        "name": "string",
        "description": "string",
        "link": "string"
    },
    {
        "id": "int",
        "image": "string",
        "name": "string",
        "description": "string",
        "link": "string"
    }..
}
```
200 - Success

400 - Bad Request 

500 - Internal Server Error
