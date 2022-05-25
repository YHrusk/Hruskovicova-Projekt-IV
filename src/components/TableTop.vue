<template>
  <table class="table-top">
    <tr>
      <td colspan="4">Datum <input type="date" style="width: 200px" /></td>
      <td colspan="3">
        Protokol<input type="number" min="1" style="width: 200px" />
      </td>
      <td colspan="4">Přijata:<input type="date" style="width: 200px" /></td>
      <td colspan="4">v hod:<input type="time" style="width: 200px" /></td>
    </tr>

    <tr>
      <td colspan="4">
        KS
        <select style="margin-left: 10px">
          <option value="A">A</option>
          <option value="B">B</option>
          <option value="AB">AB</option>
          <option value="0">0</option>
        </select>
        <select style="margin-left: 10px">
          <option value="poz">Rh poz</option>
          <option value="neg">Rh neg</option>
        </select>
      </td>
      <td colspan="2" style="text-align: right">
        <select style="margin-right: 10px">
          <option value="primi">primi</option>
          <option value="II">II</option>
          <option value="III">III</option>
          <option value="IV">IV</option>
          <option value="V">V</option>
          <option value="VI">VI</option>
          <option value="VII">VII</option>
          <option value="VIII">VIII</option>
          <option value="IX">IX</option>
          <option value="X">X</option>
          <option value="XI">XI</option>
          <option value="XII">XII</option>
          <option value="XIII">XIII</option>
          <option value="XIV">XIV</option>
          <option value="XV">XV</option>
        </select>
        gravide
      </td>
      <td colspan="2" style="text-align: right">
        <select style="margin-right: 10px">
          <option value="nulli">nulli</option>
          <option value="I">I</option>
          <option value="II">II</option>
          <option value="III">III</option>
          <option value="IV">IV</option>
          <option value="V">V</option>
          <option value="VI">VI</option>
          <option value="VII">VII</option>
          <option value="VIII">VIII</option>
          <option value="IX">IX</option>
          <option value="X">X</option>
          <option value="XI">XI</option>
          <option value="XII">XII</option>
          <option value="XIII">XIII</option>
          <option value="XIV">XIV</option>
          <option value="XV">XV</option>
        </select>
        para
      </td>
      <td colspan="3">
        Grav. hebd. <input type="text" style="width: 200px" />
      </td>
      <td colspan="2">
        GBS:
        <select style="margin-left: 10px">
          <option value="neg">neg</option>
          <option value="poz">poz</option>
        </select>
      </td>
      <td colspan="2" style="width: 130px">
        Dieta
        <select style="margin-left: 10px; width: 50px" v-model="diety" @change="dietaChange(diety)">
          <option value="0">0</option>
          <option value="1">1</option>
          <option value="2">2</option>
          <option value="3">3</option>
          <option value="4">4</option>
          <option value="5">5</option>
          <option value="6">6</option>
          <option value="7">7</option>
          <option value="8">8</option>
          <option value="9">9</option>
          <option value="10">10</option>
          <option value="11">11</option>
          <option value="12">12</option>
          <option value="13">13</option>
          <option value="jiné">jiné</option>
        </select>
        <input type="text" id="jine" style="display: none" />
      </td>
    </tr>
  </table>
</template>

<script>
export default {
  name: "TableTop",
  methods: {
    dietaChange(data) {
      if (data === "jiné") {
        document.getElementById("jine").style.display = "block";
        document.getElementById("jine").style.width = "70px";
        document.getElementById("jine").style.float = "right";
      } 
      else document.getElementById("jine").style.display = "none";
    },
  },
};
</script>

<style>
.table-top {
  border-collapse: collapse;
  width: 100%;
  font: 14px Arial;
}

.table-top th,
.table-top td {
  border: 1px solid black;
  padding: 10px;
  text-align: left;
}

.table-top td {
  border: 1px solid black;
}

.table-top input {
  margin: 5px;
}

.table-top select {
  width: 80px;
}
</style>