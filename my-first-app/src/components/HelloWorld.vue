<template>
  <div class="q-pa-md">
    <q-carousel swipeable animated arrows v-model="slide" thumbnails infinite>
      <q-carousel-slide :name="1" img-src="https://cdn.quasar-framework.org/img/mountains.jpg"/>
      <q-carousel-slide :name="2" img-src="https://cdn.quasar-framework.org/img/parallax1.jpg"/>
      <q-carousel-slide :name="3" img-src="https://cdn.quasar-framework.org/img/parallax2.jpg"/>
      <q-carousel-slide :name="4" img-src="https://cdn.quasar-framework.org/img/quasar.jpg"/>
    </q-carousel>
  </div>
</template>

<script>
// script part of a Vue component
export default {
  data() {
    return {
      slide: 3,
      lorem:
        "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Itaque voluptatem totam, architecto cupiditate officia rerum, error dignissimos praesentium libero ab nemo."
    };
  }
};
</script>

<style>
</style>

