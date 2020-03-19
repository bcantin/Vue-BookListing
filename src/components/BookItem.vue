<template>
  <li>{{book.title}}:{{book.author}}</li>
</template>

<script type="text/javascript">

  export default {
    name: 'BookItem',
    props: ['book']
  }

</script>

<style type="text/css">

  li {
    display: block;
    margin: 0 10px;
  }

</style>
