<template>
  <section>
    <h1>👍 Compre ou Venda 👎</h1>
    <ProdutosBuscar />
    <ProdutosLista />
  </section>
</template>

<script>
import ProdutosBuscar from "@/components/ProdutosBuscar.vue";
import ProdutosLista from "@/components/ProdutosLista.vue";

export default {
  name: "Home",
  components: {
    ProdutosBuscar,
    ProdutosLista,
  },
};
</script>

<style lang="scss" scoped>
@import "@/assets/scss/helpers";

h1 {
  color: $cor-02;
  margin-top: 40px;
  font-size: 2rem;
  text-align: center;
}
</style>
