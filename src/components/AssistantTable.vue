<template>
  <table class="assistant">
      <td class="assistant-title"><div class="rotate">Ordinace lékaře</div></td>

        <AssistantComp/>
        <AssistantComp/>
        <AssistantComp/>
        <AssistantComp/>
        <AssistantComp/>
        <AssistantComp/>
        <AssistantComp/>

  </table>
</template>

<script>
import AssistantComp from "./AssistantComp.vue"

export default {
    name:"AssistantTable",
    components:{
        AssistantComp
    }
}
</script>

<style>
.assistant {
  border-collapse: collapse;
  width: 100%;
  table-layout: fixed;
  font: 14px Arial;
}

.assistant-title{
  text-align: center;
  width: 50px;
  height: 80px;
  border: 1px solid black;
}

.rotate {
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg);
  -moz-transform: rotate(-90deg);
  width: 100px;
  height: 100px;
  margin-left: 30px;
}

</style>