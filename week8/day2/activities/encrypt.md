
# Activity - Encryption 

In this activity you will allow the user to encrypt sensitive data. You can use bcryptjs to perform encryption. 

https://www.npmjs.com/package/bcryptjs

- Create a `POST` route `/encrypt`. User can send Form data as shown below: 

`secret password123`

- In your `/encrypt` route, you will access `req.body.secret` and return the encrypted value as JSON. 

**Example**

Request: 

`secret password123`

Response: 

```
{
 value: "ef92b778bafe771e89245b89ecbc08a44a4e166c06659911881f383d4473e94f"
}
```


