<template>
  <table class="hours-table">
      <td class="hour-title">Hodina <button type="button" @click="doplnHodiny">Doplnit hodiny</button></td>
      <td class="hour-cell">
        <input
          type="number"
          id="hodina"
          style="width: 50px"
          min="0"
          max="23"
          v-model="hour"
        /> :30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h1" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h2" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h3" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h4" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h5" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h6" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h7" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h8" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h9" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h10" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h11" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h12" readonly />:30
      </td>
      <td class="hour-cell" style="text-align: right">
        <input type="number" id="h13" readonly />:30
      </td>
  </table>
</template>

<script>
export default {
  name: "HoursTable",
  data() {
    return{
      hour: 0
    }
  },
  methods: {
    doplnHodiny() {
      var int = this.hour;
      console.log(int);
      if (int < 0 || int > 23) {
        window.alert("Hodnota hodiny musí být mezi 0 a 23");
      }

      for (let i = 1; i < 14; i++) {
        if (int + i < 24) {
          document.getElementById("h" + i).value = int + i;
        } else {
          document.getElementById("h" + i).value = int + i - 24;
        }
      }
    },
  },
};
</script>

<style>
.hours-table {
  border-collapse: collapse;
  width: 100%;
  padding-top: 10px;
  border-top: 0px;
  font: 14px Arial;
}

.hour-title {
  border: 1px solid black;
  width: 110px;
  padding: 10px;
  text-align: left;
}

.hour-cell {
  border: 1px solid black;
  padding: 10px;
  text-align: center;
  width: 105px;
}

.hours-table input {
  margin: 5px;
  width: 50px;
}
</style>