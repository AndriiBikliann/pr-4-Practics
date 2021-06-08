<template>
  <div id="app">
    <label-comp/>
    <age-solver :user-age="50"/>
    <product-table
     :user-money="5000"
     :products="dataProductsList"/>
  </div>
</template>

<script>
import LabelComp from './components/LabelComp.vue'
import AgeSolver from './components/AgeSolver.vue'
import ProductTable from './components/ProductTable.vue'

export default {
  name: 'App',
  components: {
    LabelComp,
    AgeSolver,
    ProductTable
  },
    data() {
    return {
      dataProductsList: [
       {
         id:1,
         title:'TV',
         price:2000
       },
       {
         id:2,
         title:'Fridge',
         price:12000
       },
       {
         id:3,
         title:'TV2',
         price:34000
       },
       {
         id:4,
         title:'Fridge2',
         price:10000
       },
      ]
    }
  },
}
</script>









<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(112, 105, 105);
}
</style>
