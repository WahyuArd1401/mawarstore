<template>
  <div class="app">
    <Header />
    <Content @add-to-cart="handleAddToCart"/>
    <Footer />
  </div>
</template>

<script setup>
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";

import { useToast } from "vue-toastification";

const toast = useToast();

const handleAddToCart = (event) => {
  toast.success('Item added to cart!')
}
</script>
