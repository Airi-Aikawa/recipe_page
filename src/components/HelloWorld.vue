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
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox1" />
    <label for="checkbox" class="cup">
      1 and 1/2 cups (150g) graham cracker crumbs (about 10 full sheet graham
      crackers)
    </label>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox2" />
    <label class="butter">5 Tablespoons (70g) unsalted butter, melted</label>
    <input type="checkbox" id="checkbox" v-model="checked" class="checkbox3" />
    <label class="sugar">1/4 cup (50g) granulated sugar</label>
        <!--    <h2>Cheesecake</h2>
    <p>
      four 8-ounce blocks (904g) full-fat cream cheese, softened to room
      temperature
    </p>
    <p>1 cup (200g) granulated sugar</p>
    <p>1 cup (240g) full-fat sour cream, at room temperature</p>
    <p>1 teaspoon pure vanilla extract</p>
    <p>2 teaspoons fresh lemon juice (optional, but recommended)</p>
    <p>3 large eggs, at room temperature</p>
    <p>
      topping suggestions: salted caramel, lemon curd, strawberry topping,
      chocolate ganache, red wine chocolate ganache, fresh fruit, whipped cream,
      or raspberry sauce (recipe in notes)
    </p> -->
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
.checkbox1 {
  position: absolute;
  width: 21px;
  height: 21px;
  left: 237px;
  top: 829px;
  border: 1px solid #828282;
  box-sizing: border-box;
  border-radius: 4px;
}
.cup {
  position: absolute;
  width: 554px;
  height: 50px;
  left: 275px;
  top: 830px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  color: #333333;
}
.checkbox2 {
  position: absolute;
  width: 21px;
  height: 21px;
  left: 237px;
  top: 882px;
  border: 1px solid #828282;
  box-sizing: border-box;
  border-radius: 4px;
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
.checkbox3 {
  position: absolute;
  width: 21px;
  height: 21px;
  left: 237px;
  top: 921px;
  border: 1px solid #828282;
  box-sizing: border-box;
  border-radius: 4px;
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
</style>
