<template>
  <div>
  {{c}}
  <router-link :to = "{name: 'routerPage'}">Apple</router-link>
  <router-link :to = "{path:'/banana'}">Banana</router-link>

  <keep-alive>
    <router-view></router-view>
  </keep-alive>
  </div>

</template>

<script>
import Vue from 'vue'

export default {
  data() {
    return {
      c: "c++"
    }
  }
}
</script>
<style>

</style>
