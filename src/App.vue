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
import RecordTable from "./components/RecordTable.vue";
import RotationProcess from "./components/RotationProcess.vue";
import BirthProcess from "./components/BirthProcess.vue";
import SymbolArea from "./components/SymbolArea.vue";
import html2pdf from "./components/html2pdf.vue";

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
    SignComp,
    RecordTable,
    RotationProcess,
    BirthProcess,
    SymbolArea,
  },
  methods: {
    exportToPDF() {
			html2pdf(document.getElementById('element-to-convert'), {
        filename: "porodni_krivka.pdf",
        image: { type: 'jpeg', quality: 1 },
        jsPDF: {unit: "px", orientation: "l", hotfixes: "px-scaling", format: [1920, 1080]},
      });
		}
  }
}
</script>

<template>
  <div id="app" ref="document">
  <div id="element-to-convert">
    <HeaderComp/>
    <TableTop/>
    <TextAreaComp/>
    <SymbolArea/>
    <HoursTable/>
    <RecordTable/>
    <MarkComp title="Močení"/>
    <MarkComp title="Strava"/>
    <ContraTable/>
    <VASTable/>
    <AssistantTable/>
    <RotationProcess/>
    <BirthProcess/>
    <SignComp title="Jmenovka + podpis lékaře"/>
    <SignComp title="Jmenovka + podpis sestry/PA"/>
  </div>
    <button @click="exportToPDF">Generovat PDF</button>
  </div>
</template>

<style>

</style>
