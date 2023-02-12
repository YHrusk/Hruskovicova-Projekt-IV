<template>
  <div class="cont">

  <div class="table-start">
      <td class="rotation-title"><div class="rotation-rotate">Průběh porodu</div></td>
  </div>

  <div class="table-next">
    <table class="next-table">
      <tr class="next-cell">
        <td>Lem</td>
      </tr>
      <tr class="next-cell">
        <td>Zánik branky</td>
      </tr>
      <tr class="next-cell">
        <td>Porod</td>
      </tr>
      <tr class="next-cell">
        <td>Krvácení placenta</td>
      </tr>
    </table>
  </div>

    <div class="wrapper-birth">

        <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="40"
        :h="40"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="40"
        :h="40"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="40"
        :h="40"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>

        <ResizableComp
        :parentW="Pwidth"
        :parentH="Pheight"
        :parentLimitation="true"
        :minw="25"
        :minh="25"
        :w="40"
        :h="40"
        >
          <img src="../assets/x.png" class="image-record">
        </ResizableComp>

    </div>

</div>
</template>

<script>
import ResizableComp from './ResizableComp.vue';

export default {
    name: "BirthProcess",
    components: {
        ResizableComp
    }
}
</script>

<style>
.image-record {
  width: 100%;
  height: 100%;
}

.wrapper-birth {
  height: 300px;
  width: 1755px;
  border: 1px solid #000;
  position: relative;
  float: left;
  background: url('/static/backrgound-birth.png');
  background-size: cover;
}
</style>