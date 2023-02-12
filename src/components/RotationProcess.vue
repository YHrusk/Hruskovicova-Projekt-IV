<template>
<div class="cont">

  <div class="table-start">
      <td class="rotation-title"><div class="rotation-rotate">Postup rotace</div></td>
  </div>

  <div class="table-next">
    <table class="next-table">
      <tr class="next-cell">
        <td>čípek 1</td>
      </tr>
      <tr class="next-cell">
        <td>2</td>
      </tr>
      <tr class="next-cell">
        <td>3</td>
      </tr>
      <tr class="next-cell">
        <td>6</td>
      </tr>
      <tr class="next-cell">
        <td>8</td>
      </tr>
    </table>
  </div>

    <div class="wrapper-rotation">

      <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="80"
        :h="50"
        >
          <img src="../assets/1.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="80"
        :h="50"
        >
          <img src="../assets/2.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="80"
        :h="50"
        >
          <img src="../assets/3.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="80"
        :h="50"
        >
          <img src="../assets/4.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="80"
        :h="50"
        >
          <img src="../assets/5.png" class="image-record">
        </ResizableComp>


    </div>

</div>
</template>

<script>
import ResizableComp from './ResizableComp.vue';

export default {
    name: "RotationProcess",
    components: {
        ResizableComp
    }
};
</script>

<style>
.cont {
  width: 100%;
}

.table-start {
  border-collapse: collapse;
  width: 62px;
  height: 300px;
  float: left;
  font: 14px Arial;
  border: 1px solid black;
}

.table-next {
  border: 1px solid black;
  border-collapse: collapse;
  float: left;
  height: 300px;
  width: 63px;
}

.next-table, .next-cell{
  width: 100%;
  height: inherit;
  border: 1px solid black;
  border-collapse: collapse;
  text-align: center;
}

.rotation-title {
  width: 125px;
  height: 300px;
  border: 1px solid black;
}

.rotation-rotate {
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg);
  -moz-transform: rotate(-90deg);
  padding-right: 130px;
  padding-bottom: 100px;
  width: 50px;
  height: 50px;
}

.wrapper-rotation {
  height: 300px;
  width: 1755px;
  border: 1px solid #000;
  position: relative;
  float: left;
  background: url('/static/background-rotation.png');
  background-size: cover;
}

.symbol {
  display: inline-block;
}
</style>