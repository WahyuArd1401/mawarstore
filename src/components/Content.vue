<template>
  <div class="content">
    <div class="content-left">
      <h2 class="category animate__animated animate__fadeIn">NOVEL</h2>
      <h1 class="title animate__animated animate__fadeInLeft">NEBULA</h1>
      <p class="description animate__animated animate__fadeIn">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem dolore
        laudantium iure quibusdam velit culpa cum quas, consectetur maxime libero
        magnam obcaecati nihil ex corporis voluptate dignissimos. Aperiam,
        assumenda cum! Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Necessitatibus tempore ut natus earum velit veritatis accusantium quasi
        vero! Doloremque ullam sequi, tenetur eveniet sapiente blanditiis ducimus
        praesentium laudantium libero eius. Lorem ipsum dolor sit amet consectetur
        adipisicing elit.
      </p>
      <button class="btn-shop">Buy Now</button>
    </div>
    <div class="content-right">
      <img
        class="animate__animated animate__fadeInRight animate__fast 800ms"
        src="../assets/Nebula.jpg"
        alt="Nebula"
      />
    </div>
  </div>
</template>

<script setup>
const emit = defineEmits(['add-to-cart']);

const addToCart = () => {
  emit('add-to-cart');
}

</script>