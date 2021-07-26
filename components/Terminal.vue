<template>
  <div>
    <output></output>
    <div id="input-line" class="input-line">
      <div class="prompt">> Welcome to the terminal <br /></div>
      <div id="prompt"><input class="cmdline" autofocus /></div>
    </div>
  </div>
</template>

<style>
::selection {
  background: #ff5e99;
}
#prompt {
  padding-top: 0.75%;
}
#container {
  padding: 0.1em 1.5em 1em 1em;
}
#container output {
  clear: both;
  width: 100%;
}
#container output h3 {
  margin: 0;
}
#container output pre {
  margin: 0;
}
.input-line {
  display: -webkit-box;
  clear: both;
  color: white;
  background-color: black;
  height: 80vh;
  border-radius: 1%;
}
.prompt {
  white-space: nowrap;
  color: #acacac;
  margin-right: 7px;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none;
  padding-left: 2%;
  padding-top: 1%;
}
.cmdline {
  outline: none;
  background-color: transparent;
  margin: 0;
  width: 100%;
  font: inherit;
  border: none;
  color: inherit;
}
.ls-files {
  height: 45px;
  -webkit-column-width: 100px;
  -moz-column-width: 100px;
  -o-column-width: 100px;
  column-width: 100px;
}
</style>
