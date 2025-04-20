## Share Recipe API
```
POST /recipe/share
```

## Request Headers
```
Content-Type : application/json
Bearer <token>
```

## Request Body
```json
{
  "recipeId": int,
  "sharedWith": [
    {
      "email": "string"
    }
  ],
  "message": "string"
}
```

## Response
```
200 - Success
Body
{
  "message": "Recipe shared successfully."
}

400 - Bad Request - Invalid Request Data
401 - Unauthorized - User not authenticated
404 - Recipe Not Found
500 - Internal Server Error
```
