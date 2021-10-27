<template>
  <div class="platforms">
    <a href="https://www.google.de" class="platformWrapper">
      <div class="platformLogo"></div>
      <h5>Download for Android</h5>
    </a>
    <a href="https://www.google.de" class="platformWrapper">
      <div class="platformLogo"></div>
      <h5>Download for iOS</h5>
    </a>
  </div>
</template>

<script>
export default {};
</script>

<style>

.platforms {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  border-radius: 6px;
  width: 95vw;
  max-width: 800px;
}

.platformWrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background: #1a1a1a;
  height: 100px;
  margin-bottom: 10px;
  width: 49.3%;
  border-radius: 6px;
}

.platformWrapper:hover {
  background: #1d1d1d;
  outline: 1px solid #faa900;
}

.platformLogo {
  background: url("../assets/google-play-store-logo-black-and-white.png")
    no-repeat center center;
  background-size: contain;
  height: 30px;
  width: 30px;
  margin-bottom: 10px;
}
</style>
