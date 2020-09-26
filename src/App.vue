<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <h1>Hello Vite + Vue 3 + SWRV !</h1>
  <HelloWorld :count="count" />
  <p>
    <span>図鑑番号: {{ count }}</span>
  </p>
  <button @click="count++">１ふやす</button>
  <button @click="count--">１へらす</button>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  components: { HelloWorld },
  data: () => ({ count: 1 })
}
</script>
