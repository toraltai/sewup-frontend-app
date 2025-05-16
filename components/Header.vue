<script setup></script>
<template>
    <div class="flex justify-center">
      <!-- <ul><li>Главная</li></ul> -->
      <a class="btn-netural text-3xl mt-5 mb-5" href="#">SewUp</a>
      <!-- <ul><li><a href="#about">О нас</a></li></ul> -->
    </div>
</template>

<style>
.btn-netural {
    display: inline-block;
    text-decoration: none;
    color: inherit;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.btn-netural:hover {
    transform: translateY(-3px);
    text-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
</style>