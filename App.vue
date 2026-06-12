<template>
  <div class="container">
    <h1>Hello World!</h1>
    <p>Welcome to Vue.js</p>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hello World!'
    }
  }
}
</script>

<style scoped>
body {
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
}

.container {
  text-align: center;
  color: white;
}

.container h1 {
  font-size: 3em;
  margin: 0;
}

.container p {
  font-size: 1.2em;
  margin-top: 10px;
}
</style>
