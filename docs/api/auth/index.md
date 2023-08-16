---
title: Introduction
---

You may connect B.Movie via three ways

- Email & password
- Ethereum Wallet
- Mixin Wallet

After connected, you'll receive a JWT token. Use it in the header of your request.

Example:

```bash
curl -X GET \
  'https://b.movie/api/me' \
  -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwOi8vMTkyLjE2OC4zMS4xMTY6MzAwMCIsInNpZCI6IjE0YjE1ZGQ2LTk0ZDgtNDg2My04MTlhLThmZGMzOTA2MjRmOSIsInVpZCI6IjdiZTBiMDNmLTQ0MjYtNGQ0Ni05NGRhLTU4YzQzZDE0YThiMSIsImlhdCI6MTY4NDIwNTM4MX0.5eEyX9_ssBQtPCWkMPI26rq76OLmgBNK6_Sj2oP7Bk0' \
  -H 'content-type: application/json'
```
