---
title: Movie casts
sidebar_position: 7
---

## GET /movies/:movie_id/casts

### Explain

Get casts of a movie

### Endpoint URL

```
https://b.movie/api/movies/:movie_id/casts
```

### Parameters

| param      | explain                 |
| ---------- | ----------------------- |
| `movie_id` | `id` or `slug` of movie |
| `page`     | page                    |

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
