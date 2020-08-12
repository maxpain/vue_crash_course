<template>
  <div id="app">
    <h1>Tofo 123asdd</h1>
    <hr>
    <TodoList

    />
  </div>
</template>

<script>
import TodoList from '@/components/TodoList'
export default {
  name: 'App',
  data(){
    return{
      todos: [
        {id: 1, title: 'купить гавно', completed: false},
        {id: 2, title: 'купить масло', completed: false},
        {id: 3, title: 'купить пивас', completed: false}
      ]
    }
  },
  components: {
  TodoList
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
