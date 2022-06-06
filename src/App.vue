<script setup>
import HeaderComp from "@/components/Template/HeaderComp.vue";
import RodapeComp from "@/components/Template/RodapeComp.vue";
</script>
<template>
  <HeaderComp />
  <main>
    <RouterView />
    </main>
  <RodapeComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}
a {
  color: aliceblue;
  text-decoration: none;
}
header,
footer {
  background-color: rgb(59, 59, 127);
  color: white;
  height: 15%;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 2rem;
}
header,
span {
  padding: 0 20px;
}
header.menu-superior {
  /* display: flex;
  align-items: center; */
  justify-content: space-between;
}

main {
  height: 70%;
}
</style>
