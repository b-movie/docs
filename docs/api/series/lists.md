---
title: Series Lists
sidebar_position: 6
---

## GET /series/:series_id/lists

### Explain

Get lists related to a series

### Endpoint URL

```
https://b.movie/api/series/:series_id/lists
```

### Parameters

| param       | explain                  |
| ----------- | ------------------------ |
| `series_id` | `id` or `slug` of series |
| `page`      | page                     |

### Response

```json
{
  "lists": [
    {
      "id": "ea5dbef6-26db-48d8-af92-f3c718a9e45c",
      "slug": "must-see-in-2023",
      "title": "Must see in 2023",
      "overview": "Everyone should watch.",
      "status": "public",
      "likes_count": 2,
      "targets_count": 3,
      "created_at": "2023-04-07T01:35:39.718Z",
      "updated_at": "2023-04-12T03:07:20.952Z",
      "user": {
        "id": "f52abbd3-91fc-4efa-b833-2daf0504abf7",
        "name": "0xF376516D190c8e5f455C299fD191e93Bf4624245",
        "avatar_url": "https://api.dicebear.com/5.x/shapes/png?seed=0x52CE68A91569e9F99bE0c67a0400638332533683",
        "username": "0xf376516d190c8e5f455c299fd191e93bf4624245"
      }
    }
    //...
  ],
  "current_page": 1,
  "next_page": null,
  "prev_page": null
}
```
