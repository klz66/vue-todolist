<template>
  <div>
    <todolist></todolist>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import './components/n'
// import event from './components/event.vue'
// import vuexx from './components/vuex.vue'
// import pagea from "./components/a.vue";
// import pageb from "./components/b.vue";
import todolist from "./view/toadList"

export default {
  name: "app",
  components: {
    todolist
  },
  data() {
    return {
      age: 18
    };
  },
  methods: {
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
