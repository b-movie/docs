---
title: Update Password
sidebar_position: 5
---

## POST /auth/update_password

### Explain

Update password.

### Endpoint URL

```
https://b.movie/api/auth/update_password
```

### Body

| param                   | explain               |
| ----------------------- | --------------------- |
| `email`                 | your email address    |
| `password`              | your password         |
| `password_confirmation` | password confirmation |
| `verification_code`     | verification code     |

### Response

```json
{ "message": "Password updated" }
```
