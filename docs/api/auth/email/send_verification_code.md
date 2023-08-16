---
title: Send Verification Code
sidebar_position: 4
---

## POST /auth/send_verification_code

### Explain

Request to send a verification code to your email address.

### Endpoint URL

```
https://b.movie/api/auth/send_verification_code
```

### Body

| param   | explain            |
| ------- | ------------------ |
| `email` | your email address |

### Response

```json
{ "message": "Already sent" }
```
