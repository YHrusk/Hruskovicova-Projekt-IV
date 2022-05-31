<template>
  <table class="assistant">
      <td class="assistant-title"><div class="assistant-rotate">Ordinace lékaře</div></td>

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
  width: 50px;
  height: 80px;
  border: 1px solid black;
}

.assistant-rotate {
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg);
  -moz-transform: rotate(-90deg);
  padding-right: 120px;
  padding-bottom: 100px;
  width: 100px;
  height: 50px;
}

</style>