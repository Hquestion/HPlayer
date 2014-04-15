HPlayer
=======


HTML5播放器插件


Get Start：

<script type="text/javascript">
        $(function(){
          
            var myPlayer = new HPlayer("video/mp4", $("body"));
            myPlayer._initHPlayer({
                width: 600,
                preload: "auto",
                autoplay: false,
                volume: 0.5,
                poster: "img/33.jpg"
            },"video/basket.mp4");
        })
</script>
