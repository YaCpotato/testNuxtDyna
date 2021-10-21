<template>
  <div>
    <h1>This is index page in this site</h1>
    <nuxt-link to="/test">testへ遷移</nuxt-link>
    <nuxt-link to="/test2">test2へ遷移</nuxt-link>
    <button @click="moveTest3">test3へ推移</button>
  </div>
</template>

<script>
export default {
  methods:{
    moveTest3() {
      this.$router.push('/test3/3')
    }
  }
}
</script>
