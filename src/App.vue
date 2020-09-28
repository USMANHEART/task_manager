<template>
  <div id="app">
    <main>
      <span>Enter Task:</span>
      <p style="white-space: pre-line;">{{ task_data }}</p>
      <br>
      <textarea v-model="task_data" placeholder="add multiple lines"></textarea>
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      src: "en",
      dest: "zhCN",
      email: "usmanheart@gmail.com",
      password: "PAKINDIA",
      premiumkey: null
    }
  }
}
</script>

<style>

</style>
