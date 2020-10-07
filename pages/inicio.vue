<template>
  <div>
  </div>
</template>

<script>
export default {
    name: "inicio"
}
</script>

<style>
    .container{
        display: grid;
        grid-template-columns: repeat(5, 1fr);
        grid-template-rows: repeat(3, 1fr);
    }

    .cabeca{
        display: flex;
        grid-column: 1/3;
        grid-row: 1/1;
    }
</style>