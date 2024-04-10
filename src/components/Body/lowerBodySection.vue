<template>
    <div class="items flex" style="color: white;">
        <div class="item flex-1">
            <div class="row">
                <span class="bg-grey q-pa-xs rounded">
                    <q-icon name="personal_video" size="md"></q-icon>
                </span>
                <p class="text-bold q-mt-sm">
                    해외 마케팅
                </p>
            </div>
        </div>
        <div class="item flex-1">
            <div class="row">
                <span class="bg-grey q-pa-xs rounded">
                    <q-icon name="wallpaper" size="md"></q-icon>
                </span>
                <p class="text-bold q-mt-sm">
                    퍼블리셔
                </p>
            </div>
        </div>
        <div class="item flex-1">
            <div class="row">
                <span class="bg-grey q-pa-xs rounded">
                    <q-icon name="view_in_ar" size="md"></q-icon>
                </span>
                <p class="text-bold q-mt-sm">
                    캐드원(제도사)
                </p>
            </div>
        </div>
        <div class="item flex-1">
            <div class="row">
                <span class="bg-grey q-pa-xs rounded">
                    <q-icon name="explore" size="md"></q-icon>
                </span>
                <p class="text-bold q-mt-sm">
                    해외 세일즈
                </p>
            </div>
        </div>
        <div class="item flex-1">
            <div class="row">
                <span class="bg-grey q-pa-xs rounded">
                    <q-icon name="settings_phone" size="md"></q-icon>
                </span>
            </div>
        </div>
    </div>
</template>

<script setup>
</script>

<style scoped>
.items {
    display: flex;
    gap: 8px;
}

.item {
    border: 1px solid #ccc;
    padding: 20px;
    border-radius: 6px;
}

.flex-1 {
    flex-grow: 1;
}

</style>