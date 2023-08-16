---
title: Series index
sidebar_position: 1
---

## GET /series

### Explain

Get series.

### Endpoint URL

```
https://b.movie/api/series
```

### Parameters

| param  | explain |
| ------ | ------- |
| `page` | page    |

### Response

```json
{
  "series": [
    {
      "id": "6baa9aa9-df30-4aeb-9960-593984fb46fe",
      "slug": "al-kabir-awy",
      "status": "returning_series",
      "title": "Al-Kabir Awy",
      "original_title": "الكبير أوي",
      "overview": "Al-Kabeer Away is an Egyptian comedy television series starring Ahmed Makki, Donia Samir Ghanem, Hisham Ismail and Mohamed Shaheen , directed by Islam Khairi, Ahmed El Gendy and Hisham Fathy . The events of the series revolve around the mayor of the village of \"Mazarita\", who married an American woman and had two twin sons with her. One of them was raised in Upper Egypt, the other in America, and comic situations and paradoxes occur between the two brothers when they meet and compete for the vertical to succeed their father. Makki embodies the three roles, the father and the twins (The Elder and Johnny). The two brothers agree to hold a mayoral election, and each tries to win over the villagers, but in the end Johnny wins the election by landslide.",
      "tagline": "",
      "first_air_date": "2010-08-11",
      "spoken_languages": ["en", "ar"],
      "production_countries": ["EG"],
      "tmdb_id": 52698,
      "tmdb_vote_average": 7.1,
      "imdb_id": "tt2290891",
      "imdb_rating": null,
      "poster_url": "https://image.tmdb.org/t/p/original/nXN02ZNJo7xCuGGMmdDBX1JBxFP.jpg",
      "backdrop_url": "https://image.tmdb.org/t/p/original/A6uiMhZaJA6KHmzx1qTJfNMaWuf.jpg",
      "genres": ["Drama", "Family", "Comedy"],
      "directors": ["Ahmed El Gendy"]
    }
    //...
  ],
  "current_page": 1,
  "next_page": 2,
  "prev_page": null
}
```
