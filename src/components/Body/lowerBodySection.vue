<template>
<transition
appear
  enter-active-class="animated slideInLeft delay-10s repeat-2"
  leave-active-class="animated fadeOut"
>
<div class="items flex" >
        <div class="item flex-1">
            <div class="row">
                <span>
                    <q-icon class="bg-grey-2 q-pa-md q-mb-md" name="personal_video" size="md"></q-icon>
                </span>
                <p class="text-bold q-mt-sm">
                    해외 마케팅
                </p>
            </div>
        </div>
        <div class="item flex-1">
            <div class="row">
                <span>
                    <q-icon class="bg-grey-2 q-pa-md q-mb-md" name="wallpaper" size="md"></q-icon>
                </span>
                <p class="text-bold q-mt-sm">
                    퍼블리셔
                </p>
            </div>
        </div>
        <div class="item flex-1">
            <div class="row">
                <span >
                    <q-icon class="bg-grey-2 q-pa-md q-mb-md" name="view_in_ar" size="md"></q-icon>
                </span>
                <p class="text-bold q-mt-sm">
                    캐드원(제도사)
                </p>
            </div>
        </div>
        <div class="item flex-1">
            <div class="row">
                <span>
                    <q-icon class="bg-grey-2 q-pa-md q-mb-md" name="explore" size="md"></q-icon>
                </span>
                <p class="text-bold q-mt-sm">
                    해외 세일즈
                </p>
            </div>
        </div>
        <div class="item flex-1">
            <div class="row">
                <span>
                    <q-icon class="bg-grey-2 q-pa-md q-mb-md" name="settings_phone" size="md"></q-icon>
                </span>
            </div>
        </div>
    </div>
</transition>

</template>

<script setup>
</script>

<style scoped>
.items {
    display: flex;
    gap: 8px;
    margin-top: 50px;
    color: white;
    padding: 100px;
}

.item {
    border: 1px solid #ffff;
    padding: 20px;
    border-radius: 6px;
}

.flex-1 {
    flex-grow: 1;
}
.transparent-icon {
    opacity: 0.5;
}

</style>