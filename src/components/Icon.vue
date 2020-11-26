<template>
  <div class="ShadowSample1">
    <label class="titel yields">Yields</label>
    <label class="titel prepTIme">Prep TIme</label>
    <label class="titel cookTime">Cook Time </label>
    <label class="titel totalTime">Total Time</label>
  </div>
</template>



<script>
export default {};
</script>

<style>
.ShadowSample1 {
  position: absolute;
  width: 216px;
  height: 367px;
  left: 984px;
  top: 711px;
  background: #ffffff;
  box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
  border-radius: 12px;
}
.titel {
  /* position: absolute; */
  height: 12px;
  left: 1069px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: bold;
  font-size: 10px;
  line-height: 12px;
  text-transform: uppercase;
  color: #bdbdbd;
}
.yields {
  width: 38px;
  top: 768px;
}
.prepTIme {
  width: 58px;
  top: 844px;
}
.cookTime {
  width: 61px;
  top: 919px;
}

.totalTime {
  width: 63px;
  top: 995px;
}
</style>