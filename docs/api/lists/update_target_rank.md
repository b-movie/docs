---
title: Update list target rank
sidebar_position: 6
---

## PUT /lists/:list_id/targets/:id

### Explain

Update target rank in list.

### Endpoint URL

```
https://b.movie/api/lists/:list_id/targets/:id
```

### Parameters

| param                | explain                    |
| -------------------- | -------------------------- |
| `list_id`            | `id` or `slug` of the list |
| `id`                 | `id` of the target         |
| `row_order_position` | integer, rank in list      |

### Response

```json
{
  "success": true
}
```
