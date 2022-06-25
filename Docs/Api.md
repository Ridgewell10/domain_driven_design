#  Dinner API 
- [Dinner API ](#dinner-api)
 - [Auth](#auth)
    - [Register](#register)
        - [Register Request](#register-request)
        - [Register Response](#register-response)
    - [Login](#login)
        - [Login Request](#login-request)
        - [Login Response](#login-response)

## Auth

### Request

```js
POST {{host}}/auth/register
```

#### Register Request

```json
{
    "fristName": "Ridgewell",
    "lastName": "Madzokere",
    "email": "ridglr@gmail",
    "password": "password"
}
```

#### Register Response

```js
200 OK
```

```json
{

}