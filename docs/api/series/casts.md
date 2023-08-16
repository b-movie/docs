---
title: Series casts
sidebar_position: 7
---

## GET /seriess/:series_id/casts

### Explain

Get casts of a series

### Endpoint URL

```
https://b.series/api/seriess/:series_id/casts
```

### Parameters

| param       | explain                  |
| ----------- | ------------------------ |
| `series_id` | `id` or `slug` of series |
| `page`      | page                     |

### Response

```json
{
  "casts": [
    {
      "id": "371a6bcb-b4ca-4e35-96fb-9766b4b8e299",
      "character": "Jake Sully",
      "celebrity": {
        "id": "f5291267-b9dd-4677-abbc-a77f4cfa268d",
        "name": "Sam Worthington"
      }
    }
    // ...
  ],
  "current_page": 1,
  "next_page": null,
  "prev_page": null
}
```
