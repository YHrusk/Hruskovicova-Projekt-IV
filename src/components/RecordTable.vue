<template>
   <div class="cont">

  <div class="table-birth-start">
      <td class="birth-title">
        <div class="birth-rotate">Záznamy porodní asistentky ozvy plodu</div>
      </td>
  </div>

  <div class="table-birth-next">
    <table class="next-birth-table">
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td>170</td>
      </tr>
      <tr>
        <td>160</td>
      </tr>
      <tr>
        <td>150</td>
      </tr>
      <tr>
        <td>140</td>
      </tr>
      <tr>
        <td>130</td>
      </tr>
      <tr>
        <td>120</td>
      </tr>
      <tr>
        <td>110</td>
      </tr>
      <tr>
        <td>100</td>
      </tr>
      <tr>
        <td>90</td>
      </tr>
      <tr>
        <td>80</td>
      </tr>
      <tr>
        <td>70</td>
      </tr>
      <tr>
        <td>60</td>
      </tr>
      <tr>
        <td>50</td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
    </table>
  </div>

    <div class="wrapper-record">

        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="100"
        :x="-90"
        :y="-173"
        >
          <img src="../assets/arrow.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="100"
        :x="-90"
        :y="-173"
        >
          <img src="../assets/arrow.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="100"
        :x="-90"
        :y="-173"
        >
          <img src="../assets/arrow.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="100"
        :x="-90"
        :y="-173"
        >
          <img src="../assets/arrow.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="100"
        :x="-90"
        :y="-173"
        >
          <img src="../assets/arrow.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :minw="25"
        :minh="25"
        :w="100"
        :h="50"
        :x="20"
        :y="-145"
        >
          <img src="../assets/line.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="100"
        :h="50"
        :x="20"
        :y="-145"
        >
          <img src="../assets/line.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="100"
        :h="50"
        :x="20"
        :y="-145"
        >
          <img src="../assets/line.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="100"
        :h="50"
        :x="20"
        :y="-145"
        >
          <img src="../assets/line.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="100"
        :h="50"
        :x="20"
        :y="-145"
        >
          <img src="../assets/line.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="50"
        :x="180"
        :y="-145"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="50"
        :x="180"
        :y="-145"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="50"
        :x="180"
        :y="-145"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="50"
        :x="180"
        :y="-145"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>
        <ResizableComp
        :minw="25"
        :minh="25"
        :w="50"
        :h="50"
        :x="180"
        :y="-145"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>


    </div>

</div>
</template>

<script>
import ResizableComp from './ResizableComp.vue';

export default {
    name: "RecordTable",
    components: {
        ResizableComp,
    },
    data(){
      return {
        Pwidth: 0,
        Pheight: 0
      }
    }
};
</script>

<style>
.image-record {
  width: 100%;
  height: 100%;
}

.table-birth-start {
  border-collapse: collapse;
  width: 92px;
  height: 300px;
  float: left;
  font: 14px Arial;
  border: 1px solid black;
}

.table-birth-next {
  border: 1px solid black;
  border-collapse: collapse;
  float: left;
  height: 300px;
  width: 33px;
}

.next-birth-table{
  width: 100%;
  height: inherit;
  border-collapse: collapse;
  text-align: center;
}

.birth-title {
  width: 125px;
  height: 300px;
  border: 1px solid black;
}

.birth-rotate{
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg);
  -moz-transform: rotate(-90deg);
  padding-right: 80px;
  padding-bottom: 200px;
  width: 180px;
  height: 10px;
  float: left;
  text-align: center;
}

.wrapper-record {
  height: 300px;
  width: 1755px;
  border: 1px solid #000;
  position: relative;
  float: left;
  background: url('/static/background-record-table.png');
  background-size: cover;
}
</style>