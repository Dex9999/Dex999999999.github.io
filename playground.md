<iframe id="ytplayer" type="text/html" width="640" height="360"
  src="https://www.youtube.com/embed/M7lc1UVf-VE?autoplay=1&origin=http://example.com"
  frameborder="0"></iframe>
  
  <iframe src="https://open.spotify.com/embed/track/1L3wn1FJHmnv9OpjVbkMzY" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>

<script src= "https://player.twitch.tv/js/embed/v1.js"></script>
<div id="<player div ID>"></div>
<script type="text/javascript">
  var options = {
    width: <width>,
    height: <height>,
    channel: "<channel ID>",
    video: "<video ID>",
    collection: "<collection ID>",
    // only needed if your site is also embedded on embed.example.com and othersite.example.com
    parent: ["embed.example.com", "othersite.example.com"]
  };
  var player = new Twitch.Player("<player div ID>", options);
  player.setVolume(0.5);
</script>
