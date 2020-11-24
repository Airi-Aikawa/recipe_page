<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p class="explanation">
      Look no further for a creamy and ultra smooth classic cheesecake recipe!
      Paired with a buttery graham cracker crust, no one can deny its simple
      decadence. For the best results, bake in a water bath.
    </p>
    <p class="ingredient">Ingredients</p>
    <p class="preparation">Graham Cracker Crust</p>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox1" />
    <label for="checkbox" class="checkboxText cup">
      1 and 1/2 cups (150g) graham cracker crumbs (about 10 full sheet graham
      crackers)
    </label>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox2" />
    <label class="butter">5 Tablespoons (70g) unsalted butter, melted</label>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox3" />
    <label class="sugar">1/4 cup (50g) granulated sugar</label>
    <h2 class="cheesecake">Cheesecake</h2>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox4" />
    <label class="creamcheese">
      four 8-ounce blocks (904g) full-fat cream cheese, softened to room
      temperature
    </label>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox5" />
    <label class="cupsugar">1 cup (200g) granulated sugar</label>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox6" />
    <label class="temperature"
      >1 cup (240g) full-fat sour cream, at room temperature</label
    >
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox7" />
    <label class="vanilla">1 teaspoon pure vanilla extract</label>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox8" />
    <label class="juice"
      >2 teaspoons fresh lemon juice (optional, but recommended)</label
    >
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox9" />
    <label class="egg">3 large eggs, at room temperature</label>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox checkbox10" />
    <label class="topping">
      topping suggestions: salted caramel, lemon curd, strawberry topping,
      chocolate ganache, red wine chocolate ganache, fresh fruit, whipped cream,
      or raspberry sauce (recipe in notes)
    </label>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  position: absolute;
  width: 587px;
  height: 64px;
  left: 236px;
  top: 49px;
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 64px;
  color: #000000;
  white-space: nowrap;
}

.explanation {
  position: absolute;
  width: 592px;
  height: 51px;
  left: 261px;
  top: 125px;
  font-family: Montserrat;
  font-style: italic;
  font-weight: 500;
  font-size: 14px;
  line-height: 17px;
  color: #4f4f4f;
}

.ingredient {
  position: absolute;
  width: 128px;
  height: 32px;
  left: 236px;
  top: 711px;

  font-family: Playfair Display;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 32px;
  color: #333333;
}
.preparation {
  position: absolute;
  width: 177px;
  height: 24px;
  left: 237px;
  top: 775px;
  font-family: Playfair Display;
  font-style: italic;
  font-weight: normal;
  font-size: 18px;
  line-height: 24px;
  color: #333333;
  white-space: nowrap;
}
.checkbox{
  position: absolute;
  width: 21px;
  height: 21px;
  left: 237px;
    border: 1px solid #828282;
  box-sizing: border-box;
  border-radius: 4px;  
}
.checkbox1 {
  top: 829px;
}
.checkbox2 {
  top: 882px;
}
.checkbox3 {
  top: 921px;
}
.checkbox4 {
  top: 1040px;
}
.checkbox5 {
  top: 1102px;
}
.checkbox6 {
  top: 1137px;
}
.checkbox7 {
  top: 1172px;
}
.checkbox8 {
  top: 1207px;
}
.checkbox9 {
  top: 1244px;
}
.checkbox10 {
  top: 1279px;
}
.checkboxText{
    position: absolute;
      left: 275px;  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  color: #333333;
}
.cup {
  width: 554px;
  height: 50px;
  top: 830px;
}

.butter {
  position: absolute;
  width: 360px;
  height: 25px;
  left: 275px;
  top: 883px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  color: #333333;
}

.sugar {
  position: absolute;
  width: 250px;
  height: 20px;
  left: 275px;
  top: 922px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 20px;
  color: #333333;
}
.cheesecake {
  position: absolute;
  width: 287px;
  height: 48px;
  left: 238px;
  top: 980px;
  font-family: Playfair Display;
  font-style: italic;
  font-weight: normal;
  font-size: 18px;
  line-height: 24px;
  color: #333333;
}

.creamcheese {
  position: absolute;
  width: 599px;
  height: 50px;
  left: 275px;
  top: 1040px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  color: #333333;
}

.cupsugar {
  position: absolute;
  width: 246px;
  height: 20px;
  left: 275px;
  top: 1102px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 20px;
  color: #333333;
}

.temperature {
  position: absolute;
  width: 429px;
  height: 25px;
  left: 275px;
  top: 1135px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  color: #333333;
}

.vanilla {
  position: absolute;
  width: 251px;
  height: 20px;
  left: 275px;
  top: 1173px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 20px;
  color: #333333;
}

.juice {
  position: absolute;
  width: 488px;
  height: 25px;
  left: 275px;
  top: 1205px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  color: #333333;
}

.egg {
  position: absolute;
  width: 277px;
  height: 25px;
  left: 275px;
  top: 1242px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  color: #333333;
}

.topping {
  position: absolute;
  width: 543px;
  height: 75px;
  left: 275px;
  top: 1279px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  color: #333333;
}
</style>
