<template>
  <div class="cont-birth">

<div class="parent-birth">
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
.cont-birth {
  width: 100%;
}

.parent-birth {
  width: 130px;
  height: 300px;
  float: left;
}

.image-record {
  width: 100%;
  height: 100%;
}

.wrapper-birth {
  height: 300px;
  width: 1749px;
  border: 1px solid #000;
  position: relative;
  float: left;
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABtwAAAEsCAIAAADPaIA4AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAC5TSURBVHhe7dixbSRAEAPBzz9p/Rkyh21pBQioCoBGm/z39ca/f6+WP56Of/zdfdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHz47AMAAAAA/KLvc/KnvVv+eDr+8Xf3ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh88+AAAAAMAv+j4nf9q75Y+n4x9/d1/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfPvsAAAAAAL/o+5z8ae+WP56Of/zdfdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UD68Whc9vNuXPch+kv0k+yJ7kP0k+0n2oHxQflF+UT4oH5RflF+UD8qHV+uih3f7sgfZT7KfZF9kD7KfZD/JHpQPyi/KL8oH5YPyi/KL8kH58Gpd9PBuX/Yg+0n2k+yL7EH2k+wn2YPyQflF+UX5oHxQflF+UT4oH16tix7e7cseZD/JfpJ9kT3IfpL9JHtQPii/KL8oH5QPyi/KL8oH5cOrddHDu33Zg+wn2U+yL7IH2U+yn2QPygflF+UX5YPyQflF+UX5oHx4tS56eLcve5D9JPtJ9kX2IPtJ9pPsQfmg/KL8onxQPii/KL8oH5QPr9ZFD+/2ZQ+yn2Q/yb7IHmQ/yX6SPSgflF+UX5QPygflF+UX5YPy4dW66OHdvuxB9pPsJ9kX2YPsJ9lPsgflg/KL8ovyQfmg/KL8onxQPrxaFz2825c9yH6S/ST7InuQ/ST7SfagfFB+UX5RPigflF+UX5QPyodX66KHd/uyB9lPsp9kX2QPsp9kP8kelA/KL8ovygflg/KL8ovyQfnwal308G5f9iD7SfaT7IvsQfaT7CfZg/JB+UX5RfmgfFB+UX5RPigfXq2LHt7tyx5kP8l+kn2RPch+kv0ke1A+KL8ovygflA/KL8ovygflw6t10cO7fdmD7CfZT7IvsgfZT7KfZA/KB+UX5Rflg/JB+UX5RfmgfHi1Lnp4ty97kP0k+0n2RfYg+0n2k+xB+aD8ovyifFA+KL8ovygflA+v1kUP7/ZlD7KfZD/JvsgeZD/JfpI9KB+UX5RflA/KB+UX5Rflg/Lh1bro4d2+7EH2k+wn2RfZg+wn2U+yB+WD8ovyi/JB+aD8ovyifFA+vFoXPbzblz3IfpL9JPsie5D9JPtJ9qB8UH5RflE+KB+UX5RflA/Kh1frood3+7IH2U+yn2RfZA+yn2Q/yR6UD8ovyi/KB+WD8ovyi/JB+fBqXfTwbl/2IPtJ9pPsi+xB9pPsJ9mD8kH5RflF+aB8UH5RflE+KB9erYse3u3LHmQ/yX6SfZE9yH6S/SR7UD4ovyi/KB+UD8ovyi/KB+XDq3XRw7t92YPsJ9lPsi+yB9lPsp9kD8oH5RflF+WD8kH5RflF+aB8eLUueni3L3uQ/ST7SfZF9iD7SfaT7EH5oPyi/KJ8UD4ovyi/KB+UD6/WRQ/v9mUPsp9kP8m+yB5kP8l+kj0oH5RflF+UD8oH5RflF+WD8uHVuujh3b7sQfaT7CfZF9mD7CfZT7IH5YPyi/KL8kH5oPyi/KJ8UH76+voPw2GAULi+88oAAAAASUVORK5CYII=);
  background-size: cover;
}
</style>