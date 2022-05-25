<template>
  <td class="cell"><input class="ori" type="text"></td>
  <td class="cell"><input class="ori" type="text"></td>
  <td class="cell"><input class="ori" type="text"></td>
  <td class="cell"><input class="ori" type="text"></td>
  <td class="cell"><input class="ori" type="text"></td>
  <td class="cell"><input class="ori" type="text"></td>
  <td class="cell"><input class="ori" type="text"></td>
  <td class="cell"><input class="ori" type="text"></td>
</template>

<script>
export default {
    name: "AssistantComp"
}
</script>

<style>
.cell {
  border: 1px solid black;
  border-top: 0px;
  overflow: hidden;
  width: 10px;
  height: 300px;
}

.ori{
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg);
  -moz-transform: rotate(-90deg);
  width: 300px;
  height: 100%;
  display: block;
  margin: auto;
}
</style>