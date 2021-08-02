<template>
  <div>
    <table>
      <thead>
        <tr>
          <th>Status</th>
          <th>Job Title</th>
          <th>Job</th>
          <th>When Created</th>
          <th>Duration</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><OKBtn /></td>
          <td>Hello World onramp</td>
          <td>WAD-43</td>
          <td>10.10.2002</td>
          <td>01:30:39<br />2 hours ago</td>
          <td><DropMenu /></td>
        </tr>
        <tr>
          <td><ErrorBtn /></td>
          <td>Hello World onramp</td>
          <td>WAD-43</td>
          <td>10.10.2002</td>
          <td>01:30:39<br />2 hours ago</td>
          <td><DropMenu /></td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<style>
table tr th,
table tr td {
  width: auto;
}
table tr {
  border-bottom: 2px solid grey;
}
table {
  margin-left: auto;
  margin-right: auto;
}
table tbody tr td {
  text-align: center;
  width: 12%;
  padding: 2.5% 0%;
}
</style>
