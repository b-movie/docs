---
title: Add list target
sidebar_position: 4
---

## POST /lists/:id/targets

### Explain

Add target to list.

### Endpoint URL

```
https://b.movie/api/lists/:id/targets
```

### Parameters

| param         | explain                    |
| ------------- | -------------------------- |
| `id`          | `id` or `slug` of the list |
| `target_type` | `Movie` or `Series`        |
| `target_id`   | `id` of the target         |

### Response

```json
{
  "id": "48c469cb-dfeb-46c9-9852-9622f0c273b0",
  "list_id": "ea49bf88-fb69-4509-99ec-6e9fa98efadd",
  "target": {
    "id": "07c7070c-1821-457b-ba63-7ab10760d741",
    "slug": "avatar-the-way-of-water",
    "title": "Avatar: The Way of Water",
    "status": "released",
    "original_title": "Avatar: The Way of Water",
    "overview": "Set more than a decade after the events of the first film, learn the story of the Sully family (Jake, Neytiri, and their kids), the trouble that follows them, the lengths they go to keep each other safe, the battles they fight to stay alive, and the tragedies they endure.",
    "tagline": "Return to Pandora.",
    "runtime": 192,
    "release_date": "2022-12-14",
    "spoken_languages": ["en"],
    "production_countries": ["US"],
    "tmdb_id": 76600,
    "tmdb_vote_average": 7.754,
    "imdb_id": "tt1630029",
    "imdb_rating": 7.7,
    "poster_url": "https://image.tmdb.org/t/p/original/t6HIqrRAclMCA60NsSmeqe9RmNV.jpg",
    "backdrop_url": "https://image.tmdb.org/t/p/original/ovM06PdF3M8wvKb06i4sjW3xoww.jpg",
    "genres": ["Action", "Adventure", "Science Fiction"],
    "directors": ["James Cameron"]
  },
  "rank": 1
}
```
