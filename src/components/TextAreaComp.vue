<template>
  <table class="textarea-table">
    <tr>
      <td colspan="10">
        Důležitá sdělení: <textarea
          name="message"
          rows="3"
          cols="185"
        ></textarea>
        Alergie: <textarea
          name="message"
          rows="1"
          cols="185"
          style="margin-left: 55px"
        ></textarea>
      </td>
      <td colspan="5">
        Začátek prav. kontrakcí (I. doby porodní):<input
          type="time"
          style="width: 200px"
        />
      </td>
    </tr>
  </table>
</template>

<script>
export default {
  name: "TextAreaComp",
};
</script>

<style>
.textarea-table {
  border-collapse: collapse;
  width: 100%;
  height: 80px;
  font: 14px Arial;
}

.textarea-table td {
  border: 1px solid black;
  border-top: 0px;
  padding: 10px;
  text-align: left;
}
</style>