<template>
  <div class="app">牛牛牛
    <Person/>
  </div>
</template>

<script lang="ts">
  import Person from './components/Person.vue'

  export default {
    name:'App',
    components:{Person}
  }
</script>

<style>
.app {
background-color: aqua;
color:brown;
font-size: 40px;

}
</style>