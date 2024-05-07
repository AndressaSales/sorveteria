<script setup lang="ts">
const items = [
    'https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1',
    'https://gelaboca.com.br/wp-content/uploads/2023/04/sabores-de-sorvete-heading.jpg',
    'https://www.gm7club.com.br/wp-content/uploads/2018/09/sonho-de-ver%C3%A3o.jpg',
    'https://static.glamurama.uol.com.br/2019/07/tamanho-Icecream-copy.jpg'
]

const carouselRef = ref()

onMounted(() => {
  setInterval(() => {
    if (!carouselRef.value) return

    if (carouselRef.value.page === carouselRef.value.pages) {
      return carouselRef.value.select(0)
    }

    carouselRef.value.next()
  }, 3000)
})
</script>

<template>
  <UCarousel
    ref="carouselRef"
    v-slot="{ item }"
    :items="items"
    :ui="{ item: 'basis-full' }"
    class="rounded-lg overflow-hidden rounded-none"
    indicators
  >
    <img :src="item" class="w-full" draggable="false">
  </UCarousel>
</template>



