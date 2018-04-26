<template>
  <div id="app">
    <div class="container mt-4">
      <b-list-group-item active>Simple Task List</b-list-group-item>
      <TaskList/>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap-vue/dist/bootstrap-vue.css";
import TaskList from "./components/TaskList";
export default {
  name: "App",
  components: {
    TaskList
  }
};
</script>
