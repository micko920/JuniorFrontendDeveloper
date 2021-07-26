<template>
  <div id="header">
    <p id="title">{{ Title }}</p>
    <NewBtn />
  </div>
</template>

<style>
#header {
  text-align: center;
  margin: 0.5% 0% 1.5% 0%;
  padding: 1.5% 0%;
  border-bottom: 5px solid grey;
  border-top: 5px solid grey;
}
#title {
  font-size: 200%;
  display: inline;
}
</style>

<script>
export default {
  props: ['Title'],
}
</script>
