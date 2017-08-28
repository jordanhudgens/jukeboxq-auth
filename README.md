## JukeboxQ Auth Service

> This application serves as the centralized authentication system for the various JukeboxQ applications.


### Auth

Example request:

```
curl -X POST "http://localhost:3000/user_token" -d '{"auth": {"email": "john.doe@example.com", "password": "123456"}}' -H "Content-Type: application/json"
```
