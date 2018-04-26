<template>
  <b-list-group>
      <Task v-for="task in tasks" :key="task" :task="task"/>
  </b-list-group>
</template>

<script>
import Task from './Task';
export default {
    name: 'task-list',
    components:{
        Task
    },
    data(){
        return {
            tasks: [
                'Go to the store.',
                'Clean up my bedroom.',
                'Learn react because you just don\'t have a choice as a js developer.'
            ]
        }
    }
}
</script>