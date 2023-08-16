---
title: Verify signature
sidebar_position: 2
---

## POST /auth/ethereum/veirfy

### Explain

Verify signature with the nonce generated before.

### Endpoint URL

```
https://b.movie/api/auth/ethereum/verify
```

### Body

| param       | explain                             |
| ----------- | ----------------------------------- |
| `address`   | a valid ETH address                 |
| `signature` | The personal signature of the nonce |

### Response

```json
{
  "token": "JWT token"
}
```
