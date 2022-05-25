<template>
  <table class="vas">
    <tr>
      <td style="width: 105px">VAS</td>

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

.vas tr,
.vas td {
  border: 1px solid black;
  padding: 10px;
  text-align: left;
}

.vas td {
  border: 1px solid black;
  vertical-align:middle;
  border-top: 0px;
}

/* .vas-select {
    width: (50/4)px;
} */
</style>