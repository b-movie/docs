---
title: Delete post
---

## POST /posts/:id

### Explain

Destroy a post.

### Endpoint URL

```
https://b.movie/api/posts/:id
```

### Parameters

| param | explain | required |
| ----- | ------- | -------- |
| `id`  | post id | _true_   |

### Response

```json
{
  "id": "626f8429-51af-46f1-89c6-51867f5426eb",
  "deleted_at": "2023-05-17T07:20:18.153Z"
}
```
