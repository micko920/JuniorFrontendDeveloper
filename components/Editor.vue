<template>
  <div class="content">
    <table>
      <tr>
        <td class="w-1/10 pr-2">
          <EditorMenu />
        </td>
        <td class="file w-1/5 m-0">
          <p class="pl-2 bg-blue-200 rounded">Helloworld.py</p>
        </td>
        <td class="w-3/4 align-top">
          <Tiptap />
        </td>
      </tr>
    </table>
  </div>
</template>

<style>
table {
  border: none;
  margin: none;
}
.content {
  padding-top: 2%;
}
.file {
  margin-top: auto;
  vertical-align: top;
  padding-left: 0.5%;
  padding-top: 2%;
}
</style>
