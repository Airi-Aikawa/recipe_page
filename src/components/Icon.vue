<template>
<div class="shadow">
  <label class="titel yields">Yields</label>
  <label class="content serving">12 servings</label>
  <label class="titel prepTIme">Prep TIme</label>
  <label class="content minutes">45 minutes</label>
  <label class="titel cookTime">Cook Time </label>
  <label class="content hour">1 hour</label>
  <label class="titel totalTime">Total Time</label>
  <label class="content sevenHours">7,75 hours</label>
</div>
</template>



<script>
export default {};
</script>

<style>
.shadow {
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
  padding: 20px;
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
.content {
    padding: 20px;
  /* position: absolute; */
  height: 17px;
  left: 1069px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 17px;
  color: #333333;
}
.serving {
  width: 77px;
  top: 784px;
  color: #f2994a;
}
.minutes {
  width: 80px;
  top: 860px;
}
.hour {
  width: 43px;
  top: 935px;
}
.sevenHours {
  width: 72px;
  top: 1011px;
}
</style>