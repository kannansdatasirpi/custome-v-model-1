<template>
  <Input v-model="name" />     <!--6.lets use customize input component and try to bind name property(run the code, data doesn't store)
  7.in this example the v-model directive doesn't know how to behave with custom component.(Next example to change somthing and show the output )-->
</template>

<script>
import Input from './components/custome-v-model1.vue'   //4.included app.vue component

export default {
  name: 'App',
  components: {
    Input                       //5.then added input component
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
