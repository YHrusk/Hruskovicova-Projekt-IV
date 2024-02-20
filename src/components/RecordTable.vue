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
  background: url(data:image/png;base64,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);
  background-size: cover;
}
</style>