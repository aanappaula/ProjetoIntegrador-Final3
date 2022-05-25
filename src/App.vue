<script>
import { RouterView } from "vue-router";
import MenuLateral from "@/components/MenuLateral.vue";
import CabecalhoComp from "@/components/CabecalhoComp.vue";
import RodapeComp from "@/components/RodapeComp.vue";
export default {
  components: { MenuLateral, CabecalhoComp, RodapeComp, RouterView },
};

</script>
<template>
  <MenuLateral />
  <CabecalhoComp />
  <RodapeComp />
  <RouterView />
</template>
<style>
.teste {
  border: 5px black;
  margin: 0 black;
}
.card-img-top {
  width: 93%;
}
</style>
