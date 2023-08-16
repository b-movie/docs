---
title: Activity detail
---

## GET /activities/:id

### Explain

Get activities timeline in open group.

### Endpoint URL

```
https://b.movie/api/activities/:id
```

### Parameters

| param | explain     |
| ----- | ----------- |
| `id`  | activity id |

### Response

```json
{
  "id": "3d5a6122-6dc2-48d7-a830-286ce20f9e98",
  "key": "action.watchlist",
  "created_at": "2023-05-13T09:33:19.454Z",
  "text": "want to watch",
  "owner": {
    "id": "f52abbd3-91fc-4efa-b833-2daf0504abf7",
    "name": "0xF376516D190c8e5f455C299fD191e93Bf4624245",
    "username": "0xf376516d190c8e5f455c299fd191e93bf4624245",
    "avatar_url": "https://api.dicebear.com/5.x/shapes/png?seed=0x52CE68A91569e9F99bE0c67a0400638332533683"
  },
  "trackable": {
    "type": "Action",
    "id": "0c75c053-e6ab-44df-9d8c-164fc7ac534c",
    "action_type": "watchlist",
    "target_type": "Movie",
    "target_id": "e684acaa-8c36-474c-a285-ddda07ed7ad3"
  },
  "recipient": {
    "type": "Movie",
    "id": "e684acaa-8c36-474c-a285-ddda07ed7ad3",
    "title": "ear for eye"
  },
  "group": {
    "id": "5c2825d2-588a-4e41-a065-8d73ab7d0e6d",
    "name": "Bee Open Group"
  },
  "trx_timestamp": "1683970399545025280"
}
```
