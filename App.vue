<template>
  <div id="app">
   <datepicker/>
   <bill/>
   <amount/>
  </div>
</template>

<script>
import datepicker from './components/datepicker.vue'
import Bill from './components/Bill.vue'
import amount from './components/amount.vue'



export default {
  name: 'App',
  components: {
    datepicker,
    Bill,
    amount
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
