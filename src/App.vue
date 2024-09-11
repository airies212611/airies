<template>
  <div id="app">
    <ItemList :items="products" />
  </div>
</template>

<script>
import ItemList from './components/ItemList.vue'

export default {
  name: 'App',
  components: {
    ItemList
  },
  data() {
    return {
      products: [
        { name: 'Laptop', price: 10, isVisible: true },
        { name: 'Iphone 14 pro max', price: 20, isVisible: true },
        { name: 'Nike Shoes', price: 15, isVisible: true }
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #fc14c6;
}
</style>
