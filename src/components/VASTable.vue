<template>
  <table class="vas">
    <tr>
      <td class="vas-title">VAS</td>

      <VASComp/>
      <VASComp/>
      <VASComp/>
      <VASComp/>
      <VASComp/>
      <VASComp/>
      <VASComp/>
      
    </tr>
  </table>
</template>

<script>
import VASComp from "./VASComp.vue"

export default {
  name: "VASTable",
  components: {
    VASComp
  }
};
</script>

<style>
.vas {
  border-collapse: collapse;
  width: 100%;
  table-layout: fixed;
  font: 14px Arial;
}

.vas-title{
  border: 1px solid black;
  width: 107px;
  padding: 10px;
  text-align: left;
  border-top: 0px;
}
</style>