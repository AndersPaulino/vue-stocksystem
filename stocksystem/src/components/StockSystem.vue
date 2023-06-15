<template>
  <section>
    <header>Teste teste</header>
    <nav></nav>
    <aside></aside>
    <main>
      <article>
        <h1>Teste</h1>
        <p>
          HelloWorld!<br>
          HelloWorld!<br>
          HelloWorld!<br>
          HelloWorld!<br>
          HelloWorld!<br>
          HelloWorld!<br>
        </p>
      </article>
      <section></section>
    </main>
    <footer></footer>
  </section>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class StockSystem extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Comic+Neue:ital@1&family=Gruppo&display=swap');

main{
  display: flex;
  align-items: center;
  justify-content: center;
}
header{
  margin-left: 28%;
  background-color:#42b983;
  height: 25px;
  width: 800px;
}
article{
  align-items: center;
  margin: 5%;
  width: 400px;
  height: 400px;
  background-color:#42b983;
  border-radius: 9px;
  box-shadow:#166240 3px 3px 3px;
}
h1{
  font-family: 'Gruppo', sans-serif;
  font: 400;
  font-size: 48px;
  color:#166240;
}
p{
  font-family: 'Gruppo', sans-serif;
  font: 400;
  font-size: 38px;
  color:#166240;
}
</style>
