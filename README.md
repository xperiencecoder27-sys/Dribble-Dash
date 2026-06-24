<audio id="music" src="music.mp3" preload="auto"></audio>

<script>
document.addEventListener("keydown", function (e) {
  if (e.key.toLowerCase() === "q") {
    const music = document.getElementById("music");
    music.currentTime = 0;
    music.play();
  }
});
</script>
