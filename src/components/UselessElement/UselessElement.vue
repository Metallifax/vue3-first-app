<template>
  <p>{{randInt}}</p>
</template>

<script>
export default {
  data(){
    return {
      randInt: Math.floor(Math.random() * 100)
    }
  }
}
</script>

<style>

</style>