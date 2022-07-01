```
// Bloomberg player
//|-------------|           |-----------|
//|             |           |  PLAYING  |
//|    BBTV     | -> Click  |           |
//|-------------|           |-----------|
// Title + Description

// Trader TV
//|-------------|
//|             |
//|  TraderTv   |
//|-------------|
// Title + Description

// Real Vision
//|-------------|
//|             |
//|     RV      |
//|-------------|
// Title + Description
```

# Tasks

1.  Bare minimum: We want to create a SPA web app for trading videos. Use the given json data along with [YouTube Iframe API](https://developers.google.com/youtube/iframe_api_reference), to create a gallery of videos that start playing when you click on their thumbnail image.

2. Intermediate: We want to allow certain feeds (BBTV) only play limited time (1 min). Set up a listener for play and pause, and show notification when BBTV player has played for 1 minute.

3. Advanced: If time limit is reached instead of showing a notification refetch the BBTV data. The idea here is to see how you optimize performance given there might be multiple refetches.
