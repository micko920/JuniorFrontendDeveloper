<template>
  <div class="Btn">
    <router-link class="New" elevation="2" to="/editor"><b>{{ Type }}</b></router-link>
  </div>
</template>

<script>
export default {
  props:['Type'],
}
</script>

<style>
.Btn {
  position: relative;
  text-align: right;
  display: inline;
}
.New {
  color: #1a82e4;
  border: 4px solid #1a82e4;
  padding: 0.25% 2%;
  border-radius: 3%;
  font-size: 120%;
  margin-right: 2.5%;
  margin-top: 0%;
  float: right;
}
</style>
