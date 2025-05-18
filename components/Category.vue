<script setup>
const data = [
  "https://pub-6af9a1781d374897a606ff2e745ad40b.r2.dev/catalog/eurasia%20%D0%BA%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20-21.jpg",
  "https://pub-6af9a1781d374897a606ff2e745ad40b.r2.dev/catalog/eurasia%20%D0%BA%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20-22.jpg",
  "https://pub-6af9a1781d374897a606ff2e745ad40b.r2.dev/catalog/eurasia%20%D0%BA%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20-23.jpg",
  "https://pub-6af9a1781d374897a606ff2e745ad40b.r2.dev/catalog/eurasia%20%D0%BA%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20-24.jpg",
  "https://pub-6af9a1781d374897a606ff2e745ad40b.r2.dev/catalog/eurasia%20%D0%BA%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20-25.jpg",
  "https://pub-6af9a1781d374897a606ff2e745ad40b.r2.dev/catalog/eurasia%20%D0%BA%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20-26.jpg"
];
</script>
<template>
    <div class="flex justify-center">
    <div class="grid grid-cols-1 sm:grid-cols-2 gap-10">    
        <article class="card bg-base-100 w-96 shadow-sm" 
        v-for="(image, index) in data" 
        :key="index"
        >
        <img :src="image" alt="Catalog image" class="rounded-md" />
        </article>
    </div>
    </div>
</template>