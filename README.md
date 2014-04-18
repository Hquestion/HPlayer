HPlayer
=======

HTML5播放器插件

Getting Start:

导入jquery库及HPlayer.js、HPlayer.css先~~

  var myPlayer = new HPlayer("video/mp4", $("body"));
  myPlayer._initHPlayer({
      width: 800,
      preload: "auto",
      autoplay: false,
      volume: 0.5,
      poster: "img/33.jpg"
  },"video/basket.mp4");
