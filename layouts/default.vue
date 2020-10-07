<template>
  <div>
    <div class="cabeca1">
      <Header />

      <b-navbar class="fundomenu">
        <template slot="brand">
          <n-link to="/" no-prefetch>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
              <img
                src="https://i1.wp.com/frtsports.com.br/wp-content/uploads/2016/04/esportes-360x360.png"
                alt="esporte logo"
              />
            </b-navbar-item>
          </n-link>
        </template>
        <template slot="start">
          <nuxt-link to="/">
            <b-navbar-item> Inicio </b-navbar-item>
          </nuxt-link>

                              <nuxt-link to="/PaginasDosCards/noticias">
            <b-navbar-item> Noticias </b-navbar-item>
          </nuxt-link>

          <nuxt-link to="/PaginasDosCards/publicar">
            <b-navbar-item> Poste suas noticias aqui </b-navbar-item>
          </nuxt-link>

                    <nuxt-link to="/PaginasDosCards/contato">
            <b-navbar-item> Contato e redes sociais </b-navbar-item>
          </nuxt-link>

          


        </template>
      </b-navbar>
    </div>
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header";
import Footer from "../components/Footer";

export default {
  components: {
    Header,
    Footer,
  },
  data() {
    return {
      items: [
        {
          title: "Home",
          icon: "home",
          to: { name: "index" },
        },
        {
          title: "Inspire",
          icon: "lightbulb",
          to: { name: "inspire" },
        },
      ],
    };
  },
};
</script>

<style>
.cabeca1 {
  padding-bottom: 1%;
}
</style>
