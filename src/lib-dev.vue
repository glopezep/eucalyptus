<script>
import { EucalyptusSample } from './entry'
export default {
  name: 'EucalyptusLibDev', // vue library dev component
  components: {
    EucalyptusSample
  }
}
</script>

<template>
  <div class="eucalyptus-lib-dev">
    <eucalyptus-sample></eucalyptus-sample>
  </div>
</template>

<style scoped>
.eucalyptus-lib-dev {
  display: block;
  width: 400px;
  margin: 25px auto;
}
</style>
