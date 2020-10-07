<template>
  <div class="container">
    <div class="card1">
      <div class="card">
        <n-link to="./PaginasDosCards/pagina3" no-prefetch>
          <img
            src="https://s2.glbimg.com/3jOOCaMeuUzdaMQusRTsL40KKr0=/0x0:2000x1334/1008x0/smart/filters:strip_icc()/s.glbimg.com/es/ge/f/original/2019/10/27/rib7155_vYxlttZ.jpg"
            alt="Avatar"
            style="width: 100%"
          />
          <div class="container2">
            <h4><b>São Paulo.</b></h4>
            <p>
              Mancini x São Paulo: técnico do Atlético-GO reencontra Fernando
              Diniz pressionado no cargo
            </p>
          </div>
        </n-link>
      </div>
    </div>
    <div class="card2">
      <div class="card">
        <n-link to="./PaginasDosCards/pagina2" no-prefetch>
          <img
            src="https://s2.glbimg.com/gOjD6TYcp2IXWPvUo2tRiCUP-5c=/0x0:1600x1065/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2020/P/Y/wdiIw3TFqkBCEp2uMm1w/49540674266-5a08b94aab-o.jpg"
            alt="Avatar"
            style="width: 100%"
          />
          <div class="container2">
            <h4><b>Super Liga.</b></h4>
            <p>
              SporTV transmite a Superliga 2020/21; veja os jogos já
              confirmados.
            </p>
          </div>
        </n-link>
      </div>
    </div>
    <div class="card3">
      <div class="card">
        <n-link to="./PaginasDosCards/pagina1" no-prefetch>
          <img
            src="https://s2.glbimg.com/fmVt9qk0TU2b93EnVoFbV9Iku64=/0x0:3600x2400/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2020/q/Y/jEhfn4QBA2EMp6VhcSew/lebron-davis-lakers.jpg"
            alt="Avatar"
            style="width: 100%"
          />
          <div class="container2">
            <h4><b>Basquete Mundial.</b></h4>
            <p>
              Heat x Lakers: lamento de Dragic, repertório de LeBron e sequência
              da vitória de Davis marcam jogo 4.
            </p>
          </div>
        </n-link>
      </div>
      </div>
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