<template>
  <q-page class="flex flex-center bg-yellow-3">
    <q-btn rounded color="red" class="botao">Gerente</q-btn>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>

<style scoped>
.botao {
  font-size: 50px;
  transition: 1s ease-in-out;
}
.botao:hover {
  font-size: 100px;
  box-shadow: 4px 4px 0px 0px rgba(0, 0, 0, 0.1);
}
</style>
