<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      default: '',
    },
  },
  data() {
    return {
      count: 0,
    }
  },
}
</script>

<template>
  <div class="hello">
    <h1 class="test">{{ msg }}</h1>

    <p>
      <a href="https://v4.vitejs.dev/" target="_blank">Vite 4 Documentation</a>
      |
      <a href="https://v2.vuejs.org/" target="_blank"> Vue 2 Documentation </a>
    </p>

    <div class="card">
      <button type="button" @click="count++">count is {{ count }}</button>
      <p>
        Edit
        <code>components/HelloWorld.vue</code> to test hot module replacement.
      </p>
    </div>
    <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
