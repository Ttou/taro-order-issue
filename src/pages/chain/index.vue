<template>
  <view :class="$style.view">
    <Scene />
  </view>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import { Scene } from '@/components'

export default defineComponent({
  components: {
    Scene
  }
})
</script>

<style module>
.view {
  padding: 20px;
}
</style>
