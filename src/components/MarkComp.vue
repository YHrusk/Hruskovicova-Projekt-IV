<template>
  <table class="mark">
      <tr>
          <td class="mark-title">{{ title }}</td>

          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>

          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>

          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>

          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>

          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>

          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          <td class="mark-cell"><input type="checkbox"/></td>
          
      </tr>
  </table>
</template>

<script>
export default {
  name: "MarkComp",
  props: ["title"]
};
</script>   

<style>
.mark {
  border-collapse: collapse;
  width: 100%;
  table-layout: fixed;
  font: 14px Arial;
}

.mark-title{
  width: 105px;
  border: 1px solid black;
  border-top: 0px;
  padding: 10px;
  text-align: left;
}

.mark-cell {
  border: 1px solid black;
  border-top: 0px;
  text-align: center;
  vertical-align: middle;
  width: (105/4)px;
}

input[type="checkbox"] {
  width: 13px;
  height: 13px;
  background-color: #fff;
}

</style>