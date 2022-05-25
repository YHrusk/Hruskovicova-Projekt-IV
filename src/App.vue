<script>
import HeaderComp from "./components/HeaderComp.vue";
import TableTop from "./components/TableTop.vue";
import TextAreaComp from "./components/TextAreaComp.vue";
import HoursTable from "./components/HoursTable.vue";
import MarkComp from "./components/MarkComp.vue";
import VASTable from "./components/VASTable.vue";
import ContraTable from "./components/ContraTable.vue";
import AssistantTable from "./components/AssistantTable.vue";
import SignComp from "./components/SignComp.vue";

export default {
  name: 'App',
  components: {
    HeaderComp,
    TableTop,
    TextAreaComp,
    HoursTable,
    MarkComp,
    VASTable,
    ContraTable,
    AssistantTable,
    SignComp
  }
}
</script>

<template>
  <HeaderComp/>
  <TableTop/>
  <TextAreaComp/>
  <HoursTable/>
  <MarkComp title="Močení"/>
  <MarkComp title="Strava"/>
  <ContraTable/>
  <VASTable/>
  <AssistantTable/>
  <SignComp title="Jmenovka + podpis lékaře"/>
  <SignComp title="Jmenovka + podpis sestry/PA"/>
</template>

<style>

</style>
