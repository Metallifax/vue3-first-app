<template>
    <button @click="handleButton">Click me!</button>
    <useless-element v-for="(item, index) in items" :key="index"/>
</template>

<script>
import UselessElement from './UselessElement/UselessElement.vue';

export default {

  name: 'UselessButton',
  components: {
    UselessElement
  },
  data(){
    return {
      items: []
    }
  },
  methods: {
    handleButton(){
      this.items.unshift(Math.floor(Math.random() * 100));
    }
  }
}
</script>

<style>

</style>