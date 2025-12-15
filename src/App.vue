<script setup>
import { RouterView } from "vue-router";
import Header from "@/components/header.vue";
import Footer from "@/components/footer.vue";

</script>
<template>
    <Header />
    <main>
        <RouterView /> 
    </main>
    <Footer />
</template>

<style>
body {
  padding-top: 120px;
  background: linear-gradient(135deg, #ff9a76, #ffc08c);
  min-height: 100vh;
  margin: 0;
}

</style>
