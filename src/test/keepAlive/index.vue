<template>
  <div>
      <h1>keepAlive</h1>
      <keep-alive>
        <router-view v-if="$route.meta.keepAlive"></router-view>
      </keep-alive>
      <router-view v-if="!$route.meta.keepAlive"></router-view>
      <!-- <router-view/> -->
  </div>
</template>

<script>

export default {
  data () {
    return {}
  },
  created () {
  },
  mounted () {
  }
}
</script>
