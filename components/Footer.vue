<template>
  <div class="footer">
    <div class="followUs">
      <a href="https://bit.ly/3bmOoCp"><fa :icon="['fab', 'youtube']" class="followIcon" /></a>
      <a href="https://bit.ly/30YXpzt"><fa :icon="['fab', 'instagram']" class="followIcon" /></a>
      <a href="https://bit.ly/2Zw4tU7"><fa :icon="['fab', 'facebook']" class="followIcon" /></a>
      <!-- <a href=""><fa :icon="['fab', 'soundcloud']" class="followIcon" /></a> -->
    </div>
    <div class="legal">
      <a href="https://www.pingr.de/privacy">Datenschutz</a>
      <a href="https://www.pingr.de/imprint">Impressum</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.footer {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-bottom: 30px;
}
.followUs {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  width: 180px;
  margin-bottom: 0 20px;
}

.legal {
  display: flex;
  margin-top: 10px;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  width: 180px;
  font-size: 0.8rem;
  text-decoration: underline orange;
}

.followIcon {
  font-size: 20px;
}
</style>