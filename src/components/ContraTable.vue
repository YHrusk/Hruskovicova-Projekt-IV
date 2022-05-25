<template>
  <table class="con">
    <tr>
      <td style="width: 105px">Kontrakce</td>

        <Contraction/>
        <Contraction/>
        <Contraction/>
        <Contraction/>
        <Contraction/>
        <Contraction/>
        <Contraction/>
      
    </tr>
  </table>
</template>

<script>
import Contraction from "./Contraction.vue"

export default {
    name: "ContraTable",
    components: {
        Contraction
    }
}
</script>

<style>
.con {
  border-collapse: collapse;
  width: 100%;
  table-layout: fixed;
  font: 14px Arial;
}

.con th,
.con td {
  border: 1px solid black;
  padding: 10px;
  text-align: left;
}

.con td {
  border: 1px solid black;
  vertical-align:middle;
  border-top: 0px;
}
</style>