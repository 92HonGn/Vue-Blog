<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <hello-world msg="Hello Vue 3.0 + Vite" />
  <add-posts />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AddPosts from './components/AddPosts.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    AddPosts
  }
}
</script>
