<template>
      <td class="con-cell"><div class="left"><input class="con-input" type="text" maxlength="2"/></div>'</td>
      <td class="con-cell"><div class="left"><input class="con-input" type="text" maxlength="2"/></div>'</td>
      <td class="con-cell"><div class="left"><input class="con-input" type="text" maxlength="2"/></div>'</td>
      <td class="con-cell"><div class="left"><input class="con-input" type="text" maxlength="2"/></div>'</td>

      <td class="con-cell"><div class="left"><input class="con-input" type="text" maxlength="2"/></div>'</td>
      <td class="con-cell"><div class="left"><input class="con-input" type="text" maxlength="2"/></div>'</td>
      <td class="con-cell"><div class="left"><input class="con-input" type="text" maxlength="2"/></div>'</td>
      <td class="con-cell"><div class="left"><input class="con-input" type="text" maxlength="2"/></div>'</td>
</template>

<script>
export default {
    name: "ContractionComp"
}
</script>

<style>
.con-cell {
  border: 1px solid black;
  border-top: 0px;
  overflow: hidden;
  width: (105/4)px;
  text-align: right;
}

.con-input {
  display: block;
  width: 15px;
}

.left{
  float: left;
}
</style>