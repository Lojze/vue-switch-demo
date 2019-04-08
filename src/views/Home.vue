<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    {{lightSwitch}}
    {{lightSwitch2}}
    <moor-switch v-model="lightSwitch">开关:</moor-switch>
    <moor-switch v-model="lightSwitch2">开关2:</moor-switch>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  // components: {
  //   HelloWorld
  // }
  data() {
    return {
      lightSwitch: false,
      lightSwitch2: false,
    }
  }
}
</script>
