<template>
  <view :class="$style.view">
    <Result />
  </view>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import { Result } from '@/components'

export default defineComponent({
  components: {
    Result,
  }
})
</script>

<style module>
.view {
  padding: 20px;
}

</style>
