## User Logout API
```
POST /user/logout
```

## Request Headers
```
Content-Type : application/json
Bearer <token>
```

## Request Body 

```json
{
}
```

## Response
```
200 - Success
Body
{
  "message": "User logged out successfully."
}

400 - Bad Request - Invalid Request
401 - Unauthorized - User not authenticated
500 - Internal Server Error
```
