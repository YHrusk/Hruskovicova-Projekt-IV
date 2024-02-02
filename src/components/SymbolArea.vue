<template>
    <div class="wrapper-symbols">


    </div>
</template>

<script>

export default {
    name: "SymbolArea",
}
</script>

<style>
.wrapper-symbols {
    width: 400px;
    display: grid;
    grid-template-columns: 200px 200px 200px;
    grid-template-rows: 110px;
    border-collapse: collapse;
    border: 1px solid #000;
    position: relative;
    float: left;
}

.arrows-area {
    grid-row-start: 1;
    grid-row-end: 2;
    grid-column-start: 1;
    grid-column-end: 2;
}

.lines-area {
    grid-row-start: 2;
    grid-row-end: 3;
    grid-column-start: 2;
    grid-column-end: 3;
}

.xs-area {
    grid-row-start: 3;
    grid-row-end: end;
    grid-column-start: 3;
    grid-column-end: end;
}

.image-record {
  width: 100%;
  height: 100%;
}

</style>