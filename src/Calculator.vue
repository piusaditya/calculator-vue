<template>
  <div id="calculator">
    <header>
      <h1>Web Service Calculator</h1>
      <span class="author">Pius, Bimo, Aldi 
        <a href="https://github.com/piusaditya" target="_blank"> / klik disini untuk ke github</a></span>
    </header>
    <section class="calculator" id="calculator">
      <calculator-content></calculator-content>
    </section>
  </div>
</template>

<script>
import CalculatorContent from 'components/CalculatorContent.vue'
export default {
  name: 'calculator',
  components: {
    CalculatorContent
  }
 }

</script>

<style>

@import url('https://fonts.googleapis.com/css?family=Chakra+Petch');


html{
   font-size:62.5%;  
}

body{
  background-color:#ffffff; /* warna background calc */
}


header{
  font-size: 1.8rem;
  font-family: 'Chakra Petch', sans-serif;
}

header .author{
  font-size: 1.5rem;
}

header .author a{
  text-decoration: none;
}

header , .calculator {
  margin: 2.5rem auto;
  text-align: center;
}

.calculator{
  border: 0.8rem solid #117058;
  width: 34rem;
  height: 40rem;
  background-color: #ffffff;
  font-size: 1.6rem;
  -webkit-border-radius: 1rem;
  -moz-border-radius: 1rem;
  -ms-border-radius: 1rem;
  -o-border-radius: 1rem;
  border-radius: 1rem;
  -webkit-box-shadow: 1rem 1rem 0.5rem rgb(255, 255, 255);/*ganti shadow calculator*/
  box-shadow: 1rem 1rem 0.5rem rgb(255, 255, 255);
  
}


</style>
