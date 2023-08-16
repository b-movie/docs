---
title: Get Nonce
sidebar_position: 1
---

## POST /auth/ethereum/nonce

### Explain

Get a nonce for signature.

### Endpoint URL

```
https://b.movie/api/auth/ethereum/nonce
```

### Body

| param     | explain             |
| --------- | ------------------- |
| `address` | a valid ETH address |

### Response

```json
{
  "event": "Connect to https://b.movie",
  "address": "Your address",
  "session": "session id",
  "timestamp": "timestamp"
}
```
