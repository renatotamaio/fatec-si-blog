<template>
  <div>
      <div class="containerpublicar">
          <div class="cabecapubli">
          <section>
        <b-field horizontal label="Título" >
            <b-input name="Título" expanded placeholder="Título"></b-input>
        </b-field>

        <b-field horizontal label="Autor">
            <b-input name="nome" placeholder="Nome" expanded></b-input>
            <b-input name="email" type="email" placeholder="email@email.com" expanded></b-input>
        </b-field>

        <b-field horizontal label="Tema">
            <b-select placeholder="Selecione um tema">
                <option value="1">Futebol</option>
                <option value="2">Volei</option>
                <option value="3">Basquete</option>
                <option value="4">Golf</option>
                <option value="5">Tenis</option>
                <option value="6">Natação</option>
                <option value="7">Atletismo</option>
            </b-select>
        </b-field>

        <b-field horizontal label="Mensagem">
            <b-input type="textarea"></b-input>
        </b-field>

        <b-field horizontal>
            <p class="control">
                <button class="button is-primary">
                  Enviar
                </button>
            </p>
        </b-field>

         </section>
          </div>
          <div class="textopublic">
              <b>Faça sua postagem </b>
          </div>
      </div>
<br>
  </div>


</template>

<script>
export default {

}
</script>

<style>
.containerpublicar{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(5, 1fr);
}

.cabecapubli{
    grid-column: 2/4;
    grid-row: 2/4;
}

.textopublic{
    grid-column: 2/4;
    grid-row: 1/1;
    text-align: center;
    font-size: 50px;
    color: black;
}
</style>