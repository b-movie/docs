---
title: Sign Up
sidebar_position: 1
---

## POST /auth/sign_up

### Endpoint URL

```
https://b.movie/api/auth/sign_up
```

### Body

| param                   | explain               |
| ----------------------- | --------------------- |
| `email`                 | A valid email address |
| `password`              | your password         |
| `password_confirmation` | confirm your password |

### Response

```json
{
  "id": "user id"
  //...
}
```
