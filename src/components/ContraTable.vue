<template>
  <table class="con">
    <tr>
      <td class="con-title">Kontrakce</td>

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

.con-title{
  border: 1px solid black;
  width: 107px;
  padding: 10px;
  text-align: left;
  border-top: 0px;
}
</style>