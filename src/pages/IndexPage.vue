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
  font-size: 80px;
  box-shadow: rgba(240, 46, 46, 0.4) 5px 5px, rgba(240, 46, 46, 0.3) 10px 10px,
    rgba(240, 46, 46, 0.2) 15px 15px, rgba(240, 46, 46, 0.1) 20px 20px,
    rgba(240, 46, 46, 0.05) 25px 25px;
}
</style>
