<template>
  <div class="center footer">
    <div class="row followUs">
      <a href="https://bit.ly/3bmOoCp"><fa :icon="['fab', 'youtube']" class="followIcon" /></a>
      <a href="https://bit.ly/30YXpzt"><fa :icon="['fab', 'instagram']" class="followIcon" /></a>
      <a href="https://bit.ly/2Zw4tU7"><fa :icon="['fab', 'facebook']" class="followIcon" /></a>
      <!-- <a href=""><fa :icon="['fab', 'soundcloud']" class="followIcon" /></a> -->
    </div>
    <div class="legal">
      <a href="https://bit.ly/3pKd1RO">Datenschutz</a>
      <a href="https://bit.ly/3vR6qpT">Impressum</a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.footer {
  margin-bottom: 30px;
}
.followUs {
  width: 180px;
  margin-bottom: 0 20px;
}

.legal {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  margin-top: 10px;
  width: 180px;
  font-size: 0.8rem;
  text-decoration: underline orange;
}

.followIcon {
  font-size: 20px;
}
</style>