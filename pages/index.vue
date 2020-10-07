<template>
  <div class="textodireita">
    <p>
      <b
        >Esportes Interior de São Paulo o maior blog de esporte do interior e do
        mundo você encontra aqui.</b
      >
    </p>
    <br />
    <p>Acompanhe noticias do seu esporte favorito.</p>
    <br />

    <p><a href="">Futebol</a></p>
    <br />

    <p><a href="">Volei</a></p>
    <br />

    <p><a href="">Natação</a></p>
    <br />

    <p><a href="">Basquete</a></p>
    <br />

    <p><a href="">Golf</a></p>
    <br />
    <p><a href="">Oliempiadas</a></p>
    <br />
    <p><a href="">Futebol Internacional</a></p>
    <br />
    <p><a href="">Futebol Americano</a></p>
    <br />
    <p><a href="">Rugby</a></p>
    <br />
    <p><a href="">Outros</a></p>
    <br />
    <p><b>Campeonatos de futebol:</b></p>
    <br />
    <a href=""> <p>Campeonato Brasileiro Serie A</p></a>
    <br />
    <a href=""> <p>Campeonato Brasileiro Serie B</p></a>
    <br />
    <a href="">Campeonato Brasileiro Serie C</a>
<br>
<br>
    <a href=""> <p>Copa Libertadores da America</p></a>
    <br>
<a href=""><p>Outros Campeonatos</p></a>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  grid-template-rows: repeat(3, 1fr);
  grid-gap: 10px;
}
.container2 {
  text-align: center;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
  width: 100%;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}

.card1 {
  display: grid;
  grid-column: 0/1;
  grid-row: 1/1;
}

.card2 {
  display: grid;
  grid-column: 3/3;
  grid-row: 1/1;
}

.card3 {
  display: grid;
  grid-column: 5/5;
  grid-row: 1/1;
}
</style>
