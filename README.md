# mm-ai-news

Headlines for the AI News ticker on mickeymicklos.com.

This repository holds one file, `news.json`. An automated assistant proposes each day's headlines as a pull request. Nothing reaches the website until that pull request is merged.

## The file

```json
{
  "updated": "YYYY-MM-DD",
  "items": [
    { "title": "Headline in plain words", "source": "Publication", "url": "https://example.com/story" }
  ]
}
```

Plain text only. Links are `https` only. An empty `items` list hides the ticker.
