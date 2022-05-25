<template>
  <table class="sign-table">
      <td class="sign-title"><div class="rotate">{{title}}</div></td>

      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>

  </table>
</template>

<script>
export default {
    name: "SignComp",
    props: ["title"]
};
</script>

<style>
.sign-table{
  border-collapse: collapse;
  width: 100%;
  table-layout: fixed;
  font: 14px Arial;
}

.sign-title{
  text-align: center;
  width: 125px;
  height: 105px;
  border: 1px solid black;
}

.rotate {
-webkit-transform: rotate(-90deg);
  transform: rotate(-90deg);
  -moz-transform: rotate(-90deg);
  width: 100px;
  height: 100px;
  margin-left: 30px;
}

.sign-table td {
  border: 1px solid black;
  border-top: 0px;
  width: 105px
}
</style>