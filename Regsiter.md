# User Registration API 
```
POST /user/register
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
``` json
{
    "username": "string",
    "email": "string",
    "password": "string"
}
```
## Response
```
Body
{
    "message": 'User registered Successfully!',
}

```
200-Created

400 - Bad Request - Invalid Registration Information

500 - Internal Server Error
