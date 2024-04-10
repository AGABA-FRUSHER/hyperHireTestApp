<template>
    <div>
        <q-carousel
            animated
            v-model="slide"
            navigation
            infinite
            :autoplay="autoplay"
            arrows
            transition-prev="slide-right"
            transition-next="slide-left"
            @mouseenter="autoplay = false"
            @mouseleave="autoplay = true"
            >
            <q-carousel-slide :name="1" img-src="src/assets/frame.png" />
            <q-carousel-slide :name="2" img-src="src/assets/frame.png" />
            <q-carousel-slide :name="3" img-src="src/assets/frame.png" />
        </q-carousel>
    </div>
</template>

<script setup>
import { ref } from 'vue';

const slide = ref(1)
const autoplay = ref(true)

</script>