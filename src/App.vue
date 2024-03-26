<template>
  <div id="app">
    <h1>List Tugas</h1>
    <ul>
      <!-- <li v-for="task in tasks" :key="task.id">
        <input type="checkbox" v-model="task.done">
        <span :style="{ textDecoration: task.done ? 'line-through' : 'none' }">{{ task.name }}</span>
      </li> -->
      <li v-for="task in tasks" :key="task.id">{{ task.name }}</li>
    </ul>

  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  data: function() {
    return {
      tasks: [
        { id: 1, name: 'Membuat Aplikasi', done: false },
        { id: 2, name: 'Membuat Presentasi', done: false },
        { id: 3, name: 'Membuat Laporan', done: false }
      ]
    }
  },
  components: {}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
