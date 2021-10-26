<!--
 * @Author: your name
 * @Date: 2021-10-26 14:02:35
 * @LastEditTime: 2021-10-26 17:29:23
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \vue-vite-cli\src\views\home.vue
-->
<template>
  <div>
    <div>113</div>
    <HelloWorld msg="2222" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from '@/components/HelloWorld.vue'
export default defineComponent({
  components: {
    HelloWorld
  },
  setup() {
    return {}
  }
})
</script>

<style scoped></style>
