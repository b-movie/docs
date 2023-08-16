---
title: Sign In
sidebar_position: 2
---

## POST /auth/sign_in

### Explain

Use email/password to sign in.

### Endpoint URL

```
https://b.movie/api/auth/sign_in
```

### Body

| param      | explain            |
| ---------- | ------------------ |
| `email`    | your email address |
| `password` | your password      |

### Response

```json
{ "token": "JWT used to authorize" }
```
