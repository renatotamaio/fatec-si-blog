<template>
<div class="textodireita">

    <b>Redes sociais e contato dos desenvolvedores:</b>
    <br>
    <br>
    <p><b>Renato Tamaio</b></p>
    <p>Telefone (16) 33333333</p>
    <p>Celular (16) 999999999</p>
    <p><a href="https://github.com/renatotamaio/">https://github.com/renatotamaio/</a></p>
    <p><a href="https://www.facebook.com/renato.tamaio">Facebook</a></p>
    <p><a href="https://www.instagram.com/renatotamaio/">Instagram</a></p>
    <br>
    <br>
    <p><b>Antonio Gambogi</b></p>
        <p>Telefone (16) 33333333</p>
    <p>Celular (16) 999999999</p>
    <p><a href="https://github.com/antoniogambogi/">https://github.com/antoniogambogi/</a></p>
    <p><a href="https://www.facebook.com/antonio.gambogi">Facebook</a></p>
    <p><a href="https://www.instagram.com/antoniogambogi/">Instagram</a></p>
    <br>
    <br>
    <p><b>Antonio Ezarqui</b></p>
        <p>Telefone (16) 33333333</p>
    <p>Celular (16) 999999999</p>
    <p><a href="https://github.com/antonioezarqui/">https://github.com/antonioezarqui/</a></p>
    <p><a href="https://www.facebook.com/antoniocarlos.ezarquijunior">Facebook</a></p>
    <p><a href="https://www.instagram.com/antonioezarqui/">Instagram</a></p>
    <br>
    <br>
    <p><b>Bruno Silva</b></p>
        <p>Telefone (16) 33333333</p>
    <p>Celular (16) 999999999</p>
    <p><a href="...">Github</a></p>
    <p><a href="https://www.facebook.com/profile.php?id=100002509667688">Facebook</a></p>
    <p><a href="...">Instagram</a></p>
    <br>
    <br>
    <br>
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

.textodireita{
padding-left: 40px;
}

</style>