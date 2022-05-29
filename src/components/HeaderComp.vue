<template>
<div class="container">
  <div class="container-child1">
    <fieldset class="fieldset">
      <label>Jméno a příjmení pacienta:</label><input type="text" /><br />

      <label>Rodné číslo pacienta:</label><input type="text" /><br />

      <label>Datum narození (není-li RČ)</label><input type="date" />
      <label>Kód ZP</label>
      <select>
        <option value=""></option>
        <option value="111">111</option>
        <option value="201">201</option>
        <option value="205">205</option>
        <option value="207">207</option>
        <option value="209">209</option>
        <option value="211">211</option>
        <option value="213">213</option></select
      ><br />

      <label>Adresa trv. pobytu (případně jiná adresa)</label
      ><input type="text" />
    </fieldset>

  </div>

  <div class="container-child2">
    <div class="right-part">
      <label class="parent">Porodní křivka</label>
      <div class="child">
          <label>list č.</label>
          <input type="number" min="1" style="width: 35px">
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "HeaderComp",
};
</script>

<style>
.container {
  margin-left: 1000px;
  font: 14px Arial;
  padding-bottom: 165px;
}

.container-child1 {
  width: 75%;
  float: left;
}

.container-child2 {
  width: 25%;
  float: left;
}

.parent {
  margin-right: 20px;
  position: relative;
  font-weight: bold;
  font-size: 20px;
}

.child {
  position: absolute;
  padding-top: 15px;
  margin-left: 50px;
}

.right-part {
  padding-top: 80px;
}

.fieldset {
  border: 1px solid black;
  margin: 3pt;
  border-top: 5px solid black;
  width: 450px;
}

.fieldset input {
  margin: 5px;
}
</style>