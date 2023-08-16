---
title: Create list
sidebar_position: 3
---

## POST /lists

### Explain

Create list

### Endpoint URL

```
https://b.movie/api/lists
```

### Parameters

| param      | explain                         |
| ---------- | ------------------------------- |
| `title`    | string                          |
| `overview` | string                          |
| `status`   | `public` or `private`, optional |

### Response

```json
{
  "id": "ea49bf88-fb69-4509-99ec-6e9fa98efadd",
  "slug": "must-see-in-may-2023",
  "title": "MUST SEE in MAY, 2023",
  "overview": null,
  "status": "public",
  "likes_count": 0,
  "targets_count": 0,
  "created_at": "2023-05-22T14:44:53.941Z",
  "updated_at": "2023-05-22T14:44:53.941Z",
  "user": {
    "id": "7be0b03f-4426-4d46-94da-58c43d14a8b1",
    "name": "an.lee.work",
    "avatar_url": "https://api.dicebear.com/5.x/shapes/png?seed=0xe2d26DDE236C397B53cC94e5FA70C84046f8d84a",
    "username": "an-lee-work"
  }
}
```
