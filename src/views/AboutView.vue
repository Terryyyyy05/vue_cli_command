<template>
  <div class="about">
    <h1>This is an about-page</h1>
    <Button type="primary">Primary</Button>
    <hr />
  </div>
  <Carousel v-model="value" loop>
    <CarouselItem v-for="item in 5" :key="item">
      <img :src="require('@/assets/logo.png')" alt="" />
    </CarouselItem>
  </Carousel>
</template>
