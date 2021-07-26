<template>
    <div id="Btn">
        <button id="New" elevation="2" @click="goTo()"><b>Editor</b></button>
    </div>
</template>

<script>
export default {
  methods: {
    goTo() {
      this.$router.push('/editor')
    },
  },
}
</script>

<style>
    #Btn{
        position: relative;
        text-align: right;
        display: inline;
    }
    #New{
        color: #1a82e4;
        border: 4px solid #1a82e4;
        padding: 0.25% 3%;
        border-radius: 3%;
        font-size: 120%;
        margin-right: 2.5%;
        margin-top: 0%;
        float: right;
    }
</style>