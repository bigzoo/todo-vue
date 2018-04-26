<template>
  <b-list-group-item>
    {{ task }}
  </b-list-group-item>
</template>

<script>
export default {
  name: "task",
  props: ["task"]
};
</script>
