<template>
<div class="body bg-body">
    <HeaderComponent/>
    <div class="row" style="margin-left: 100px;">
        <div class="col-8">
            <div class="decs-wrapper" style="color: white;">
                <div>
                    <h5>
                        풀타임,파트타임
                    </h5>
                </div>
                <div class="main-desc q-pa-lg">
                    <h3>
                        최고의 실력을 가진<br>
                        외국인 인재를 찾고 계신가요
                    </h3>
                    <h5>
                        법률 및 인사관리 부담없이<br>
                        1주일 이내에 원격으로 채용해보세요.                
                    </h5>
                    <h5>
                        개발자가 필요하신가요?
                    </h5>
                </div>
                <div class="desc-items q-pa-lg">
                    <div class="row">
                        <div class="col q-pa-md">
                            <q-separator class="q-mb-md" color="white"/>
                            <bold style="font-weight: bold;">
                                평균 월 120만원
                            </bold>
                            <div class="content">
                                임금을 해당 국가를 기준<br>
                                으로 계산합니다.
                            </div>
                        </div>
                        <div class="col q-pa-md">
                            <q-separator class="q-mb-md" color="white"/>
                            <bold style="font-weight: bold;">
                                최대 3회 인력교체
                            </bold>
                            <div class="content">
                                막상 채용해보니 맞지 않<br>
                                아도 걱정하지 마세요. 
                            </div>
                        </div>
                        <div class="col q-pa-md">
                            <q-separator class="q-mb-md" color="white"/>
                            <bold style="font-weight: bold;">
                                평균 3일, 최대 10일
                            </bold>
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
                <div class="ro" style="color: white;">
                    <h4>
                        월 100만원
                    </h4>
                </div>
                <sliderComponent/>
            </div>
        </div>
    </div>
    <lowerBodySection/>

</div>
</template>


<script setup>
import HeaderComponent from 'src/components/Header/HeaderComponent.vue';
import sliderComponent from 'src/components/slider/sliderComponent.vue';
import lowerBodySection from 'src/components/Body/lowerBodySection.vue';
import { ref } from 'vue';

const slide = ref(1)
const autoplay = ref(true)

</script>


<style scoped>

.bg-body {
    background-image: url("bg.png");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

</style>