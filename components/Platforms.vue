<template>
  <div class="platforms">
    <a href="https://www.google.de" class="platformWrapper">
      <div class="platformLogo">
        <fa :icon="['fab', 'apple']" class="icon" />
      </div>
      <h5>Download for iOS</h5>
    </a>
    <a href="https://www.google.de" class="platformWrapper">
      <div class="platformLogo">
        <fa :icon="['fab', 'android']" class="icon android" />
      </div>
      <h5>Download for Android</h5>
    </a>
  </div>
</template>

<script>
export default {};
</script>

<style>
.icon {
  font-size: 30px;
}

.android {
  padding-top: 5px;
}

.platforms {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  border-radius: 6px;
  width: 100%;
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
  height: 30px;
  width: 30px;
  margin-bottom: 10px;
}
</style>
