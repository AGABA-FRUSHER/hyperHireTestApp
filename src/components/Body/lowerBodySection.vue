<template>
    <div class="items flex">
    <div class="item flex-1">one</div>
    <div class="item flex-1">two</div>
    <div class="item flex-1">three</div>
    <div class="item flex-1">four</div>
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