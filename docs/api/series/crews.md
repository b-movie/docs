---
title: Series crews
sidebar_position: 8
---

## GET /series/:series_id/crews

### Explain

Get crews of a series

### Endpoint URL

```
https://b.series/api/series/:series_id/crews
```

### Parameters

| param       | explain                  |
| ----------- | ------------------------ |
| `series_id` | `id` or `slug` of series |
| `page`      | page                     |

### Response

```json
{
  "crews": [
    {
      "id": "ceda1f84-d7d1-49b8-9362-298605198d99",
      "celebrity": {
        "id": "efbfd3e9-2e2e-4742-9095-b35b843368e7",
        "name": "Stephen E. Rivkin"
      },
      "job": {
        "id": "13b3c971-d35b-47d2-90ae-e6cd80daf4f6",
        "name": "Editor"
      }
    }
    // ...
  ],
  "current_page": 1,
  "next_page": null,
  "prev_page": null
}
```
