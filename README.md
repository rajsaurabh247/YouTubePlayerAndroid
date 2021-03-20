# YouTubePlayerAndroid
A simple video player to play youtube videos.
<div class="row">
      <img src="/Screenshots/1616234172893.jpg" width="400" title="1">
      <img src="/Screenshots/1616233249405.jpg" width="400" title="2">
      <img src="/Screenshots/1616233249399.jpg" width="400" title="3">
</div>

## Dependencies :
```bash
implementation 'com.pierfrancescosoffritti.androidyoutubeplayer:core:10.0.5'
```
Also Add :
```bash
YouTubePlayerView youTubePlayerView = findViewById(R.id.youtube_player_view);
getLifecycle().addObserver(youTubePlayerView);
```
