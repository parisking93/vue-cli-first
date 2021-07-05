

<template>
    <h1>la mia prima app con Vue CLI!</h1>
</template>



<script>
export default {
  name: 'Title',
  props: {
    msg: String
  }
}
</script>

<style scoped>
    h1 {
        font-size: 50px;
        text-transform: capitalize;
    }
</style>