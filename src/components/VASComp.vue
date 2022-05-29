<template>
      <td class="vas-cell"><input class="vas-input" type="text" maxlength="2"/></td>
      <td class="vas-cell"><input class="vas-input" type="text" maxlength="2"/></td>
      <td class="vas-cell"><input class="vas-input" type="text" maxlength="2"/></td>
      <td class="vas-cell"><input class="vas-input" type="text" maxlength="2"/></td>

      <td class="vas-cell"><input class="vas-input" type="text" maxlength="2"/></td>
      <td class="vas-cell"><input class="vas-input" type="text" maxlength="2"/></td>
      <td class="vas-cell"><input class="vas-input" type="text" maxlength="2"/></td>
      <td class="vas-cell"><input class="vas-input" type="text" maxlength="2"/></td>
</template>

<script>
export default {
    name:"VASComp"
}
</script>

<style>
.vas-cell {
  border: 1px solid black;
  border-top: 0px;
  overflow: hidden;
  width: (105/4)px;
}

.vas-input {
  display: block;
  width: 20px;
}
</style>