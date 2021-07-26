<template>
  <div id="content">
    <table>
      <tr>
        <td id="file">
            <p style="background-color: lightblue; padding-left: 5%; border-radius: 5%;">Helloworld.py</p>
        </td>
        <td id="editor">
          <iframe
            frameborder="0"
            width="100%"
            height="500px"
            src="https://repl.it/@burgerbuns943/te_kakano_calculator?lite=true"
          ></iframe>
        </td>
      </tr>
    </table>
  </div>
</template>

<style>
    table{
        border: none;
        margin-left: auto;
        margin-right: auto;
    }
    tr{
        min-width: 100%;
    }
    #content{
        padding-top: 2%;
    }
    #editor{
        min-width: 60vw;
    }
    #file{
        min-width: 12vw;
        margin-top: auto;
        vertical-align: top;
        padding-left: 0.5%;
        padding-top: 2%;
    }
</style>