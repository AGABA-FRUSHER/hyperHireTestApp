<template>
  <q-layout view="lHh Lpr lFf">
  <div class="main" style="margin-top: 50px;">
    <bodyComponent/>
    <bottomComponent/>
  </div>
  </q-layout>
</template>

<script setup>
import { ref } from 'vue'
import bodyComponent from 'src/components/Body/bodyComponent.vue';
import bottomComponent from 'src/components/Bottom/bottomComponent.vue';

defineOptions({
  name: 'MainLayout'
})

</script>
