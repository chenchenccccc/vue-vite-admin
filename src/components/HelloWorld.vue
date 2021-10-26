<!--
 * @Author: your name
 * @Date: 2021-10-26 14:04:07
 * @LastEditTime: 2021-10-26 17:48:29
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \vue-vite-cli\src\views\vuex.vue
-->
<template>
  <div>{{msg}}</div>
</template>

<script lang="ts">
import { defineComponent,defineProps } from 'vue'
export default defineComponent({
  name:'HelloWorld',
  props:{
    msg:{
      default:'HelloWorld',
      type:String
    }
  },
  setup(props) {
    return {
      msgDate:'2021-10-26'
    }
  }
})
</script>

<style scoped></style>
