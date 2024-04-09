<template>
<div class="body bg-blue">
    <div class="row">
        <div class="col-8">
            <div class="decs-wrapper">
                <div class="main-desc q-pa-lg">
                    <p>
                        최고의 실력을 가진<br>
                        외국인 인재를 찾고 계신가요
                    </p>
                    <p>
                        법률 및 인사관리 부담없이<br>
                        1주일 이내에 원격으로 채용해보세요.                
                    </p>
                    <p>
                        개발자가 필요하신가요?
                    </p>
                </div>
                <div class="desc-items q-pa-lg">
                    <div class="row">
                        <div class="col q-pa-md">
                            <q-separator/>
                            <bold>평균 월 120만원</bold>
                            <div class="content">
                                임금을 해당 국가를 기준<br>
                                으로 계산합니다.
                            </div>
                        </div>
                        <div class="col q-pa-md">
                            <q-separator/>
                            <bold>최대 3회 인력교체</bold>
                            <div class="content">
                                막상 채용해보니 맞지 않<br>
                                아도 걱정하지 마세요. 
                            </div>
                        </div>
                        <div class="col q-pa-md">
                            <q-separator/>
                            <bold>평균 3일, 최대 10일</bold>
                            <div class="content">
                                급하게 사람이 필요한 경<br>
                                우에도 빠른 채용이 가능<br>
                                합니다.
                            </div></div>

                    </div>

                </div>
            </div>
        </div>
        <div class="col-4">
            <div class="slider-wrapper">
                slider here
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
      <q-carousel-slide :name="1" img-src="https://cdn.quasar.dev/img/mountains.jpg" />
      <q-carousel-slide :name="2" img-src="https://cdn.quasar.dev/img/parallax1.jpg" />
      <q-carousel-slide :name="3" img-src="https://cdn.quasar.dev/img/parallax2.jpg" />
      <q-carousel-slide :name="4" img-src="https://cdn.quasar.dev/img/quasar.jpg" />
    </q-carousel>
            </div>
        </div>
    </div>
        <div class="items flex">
    <div class="item flex-1">one</div>
    <div class="item flex-1">two</div>
    <div class="item flex-1">three</div>
  </div>

</div>
</template>


<script setup>
import { ref } from 'vue';

const slide = ref(1)
const autoplay = ref(true)

</script>


<style scoped>
.items {
  display: flex;
  justify-content: space-between;
}

.item {
  /* Add your item styling here */
  border: 1px solid #ccc;
  padding: 10px;
}

.flex-1 {
  /* Make each item take full width */
  flex-grow: 1;
}

</style>