<!--
 * @Author: your name
 * @Date: 2021-10-26 14:04:07
 * @LastEditTime: 2021-10-26 16:19:49
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \vue-vite-cli\src\views\vuex.vue
-->
<template>
  <div>{{msg}}</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name:'HelloWorld',
  setup() {
    return {
      msg:'HelloWorld'
    }
  }
})
</script>

<style scoped></style>
