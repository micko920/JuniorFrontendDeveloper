<template>
  <div class="header">
    <p class="title">{{ Title }}</p>
    <NewBtn Type="Close"/>
  </div>
</template>

<script>
export default {
  props: ['Title'],
}
</script>

<style>
.header {
  text-align: center;
  margin: 0.5% 0% 1.5% 0%;
  padding: 1.5% 0%;
  border-bottom: 5px solid grey;
  border-top: 5px solid grey;
}
.title {
  font-size: 200%;
  display: inline;
}
</style>


