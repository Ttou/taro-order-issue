<template>
  <view :class="$style.scene">
  </view>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Scene',
})
</script>

<style module>
.scene {
  display: flex;
  flex-flow: column nowrap;
  padding: 10px 15px;
  margin: 25px 0;
  background: #fffbf5;
  color: #666;
  border-radius: 5px;
}
</style>
