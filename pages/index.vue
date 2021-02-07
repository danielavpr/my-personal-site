<template>
  <div class="container">
    <h1>Hey there!</h1>
    <p>🚧 This site is under construction 🚧</p>
    <p>In the meantime, enjoy this video</p>
    <p>✨ unmute for a better experience ✨</p>
    <iframe class="video" src="https://www.youtube.com/embed/dlRtKga7sv8?autoplay=1&mute=1"/>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  /* width: 80%; */
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  flex-direction: column;
}

.container > * {
  margin: 10px 0;
}

.video {
  width: 420px;
  height: 315px;
}

@media (max-width: 480px) {
  .video {
    width: 80%;
    height: 315px;
  }
}
</style>
