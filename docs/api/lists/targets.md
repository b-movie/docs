---
title: List items
sidebar_position: 7
---

## GET /lists/:id/targets

### Explain

Get items of a list.

### Endpoint URL

```
https://b.movie/api/lists/:id/targets
```

### Parameters

| param | explain                    |
| ----- | -------------------------- |
| `id`  | `id` or `slug` of the list |

### Response

```json
{
  "list_targets": [
    {
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
    }
    //...
  ],
  "current_page": 1,
  "next_page": null,
  "prev_page": null
}
```
