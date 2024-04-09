<template>
    <div>
      <div class="appbar">
      <div class="toolbar">
        <h5 class="btn">Home</h5>
        <div class="btn" style="display: flex; gap: 45px">
          <h5>채용</h5>
          <h5>해외 개발자 활용 서비스</h5>
        </div>
        <h5 class="btn">문의하기</h5>
      </div>
    </div>
    </div>
</template>

<script setup>
</script>

<style scoped>
  .tool-bar {
    background-color: transparent;
    height: 100px;
    width: 100%;
    display: flex;
    align-items: center;
    color: white;
  }
  .appbar {
      color: white;
      font-size: 0.5rem;
      display: flex;
      justify-content: center;
    }

    .toolbar {
      display: flex;
      justify-content: space-between;
      width: 80%;
    }

    .btn {
      cursor: pointer;
    }

</style>