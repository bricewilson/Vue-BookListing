<template>
  <li>{{ mybook.title }} --- {{ mybook.author }}</li>  
</template>

<script>
export default {
  name: 'BookItem',
  props: [
    'mybook'
  ]
}
</script>

<style>
li {
  display: block;
  margin: 0 10px
}
</style>
