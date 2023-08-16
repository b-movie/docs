---
title: Remove list target
sidebar_position: 5
---

## DELETE /lists/:list_id/targets/:id

### Explain

Remove target from list.

### Endpoint URL

```
https://b.movie/api/lists/:list_id/targets/:id
```

### Parameters

| param     | explain                    |
| --------- | -------------------------- |
| `list_id` | `id` or `slug` of the list |
| `id`      | `id` of the target         |

### Response

```json
{
  "success": true
}
```
