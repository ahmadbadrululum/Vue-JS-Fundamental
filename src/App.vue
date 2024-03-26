<template>
    <div id="app">
        <h1>List Tugas</h1>
        <div v-for="task in tasks" :key="task.id">
            <ItemTugas :task="task"></ItemTugas>
        </div>
        
    </div>
</template>

<script>
import ItemTugas from './components/ItemTugas.vue'

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
    components: {
        ItemTugas
    }
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
