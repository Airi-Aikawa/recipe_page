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
   <!--     <p>
      1 and 1/2 cups (150g) graham cracker crumbs (about 10 full sheet graham
      crackers)
    </p>
    <p>5 Tablespoons (70g) unsalted butter, melted</p>
    <p>1/4 cup (50g) granulated sugar</p>
    <h2>Cheesecake</h2>
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
h1{
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

.explanation{
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
color: #4F4F4F;
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
.preparation{
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
</style>
