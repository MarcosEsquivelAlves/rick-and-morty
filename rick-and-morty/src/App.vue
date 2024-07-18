<template>
  <div id="app">
    <Menu />
    <card-component />
</div>
</template>


<script>
import Menu from './components/Menu.vue'
import Card from './components/Card.vue'



export default {
  name: 'App',
  components: {
    Menu,
    'card-component': Card
  }
}
</script>