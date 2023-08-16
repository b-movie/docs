---
title: Create post
---

## POST /posts

### Explain

Create new post.

### Endpoint URL

```
https://b.movie/api/posts
```

### Parameters

| param         | explain                              | required |
| ------------- | ------------------------------------ | -------- |
| `content`     | text content                         | _true_   |
| `post_type`   | `note`(default), `article`           | _false_  |
| `title`       | title, used for article type         | _false_  |
| `overview`    | overview, used for article type      | _false_  |
| `reply_to_id` | reply to another post                | _false_  |
| `url`         | attach a url                         | _false_  |
| `target_type` | `Movie`, `Series`, `Episode`, `List` | _false_  |
| `target_id`   | used with `target_type`              | _false_  |
| `group_id`    | Group ID                             | _false_  |

### Response

```json
{
  "id": "626f8429-51af-46f1-89c6-51867f5426eb",
  "post_type": "note",
  "title": null,
  "content": "Hello from API",
  "collects_count": 0,
  "dislikes_count": 0,
  "edited_at": null,
  "likes_count": 0,
  "replies_count": 0,
  "created_at": "2023-05-17T07:17:52.686Z",
  "updated_at": "2023-05-17T07:17:52.686Z",
  "images": [],
  "target": {
    "id": null,
    "type": null
  },
  "user": {
    "id": "7be0b03f-4426-4d46-94da-58c43d14a8b1",
    "name": "xxx",
    "username": "xxx",
    "avatar_url": "https://api.dicebear.com/5.x/shapes/png?seed=0xe2d26DDE236C397B53cC94e5FA70C84046f8d84a"
  },
  "activity": {
    "id": "ff82ce5c-49c4-4961-84be-5198b897c7a1"
  }
}
```
