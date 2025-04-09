# User Login API 
```
POST /user/login
```

### Request Headers
```
Content-Type : application/json
```

### Request Body
``` json
{
    "username": "string",
    "password": "string"
}
```
## Response
```

Body
{
    "success": true,
    "message": "Login successful",
    "token": "string"
}

```
200 - Success

400 - Bad Request - Invalid User Details

500 - Internal Server Error