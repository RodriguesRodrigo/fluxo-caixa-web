<template>
  <div class="content-title">
    <div class="content-title-item">
      <h1 class="title">Movimentação da minha conta</h1>
    </div>
    <div class="content-title-item">
      <button type="button" class="button-add-item">
        <span class="icon-plus"></span>
      </button>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Header'
};

</script>

<style scoped>
.content-title {
  max-width: 450px;
  margin: auto;
  padding: 3.56rem 1.68rem 1.68rem;
  display: flex;
  justify-content: space-between;
}

.content-title-item {
  display: flex;
  align-items: center;
}

.content-title-item .title {
  font-size: 1.5rem;
  width: 205px;
}

.button-add-item {
  background-color: #E5E7EB;
  font-size: 0;
  padding: 0.323rem;
  border: none;
  border-radius: 2px;
  box-shadow: 0px 0px 4px rgba(0, 0, 0, .25);
}

.icon-plus {
  width: 13.71px;
  height: 13.71px;
  background-image: url('../assets/plus-blue-icon.png');
  background-repeat: no-repeat;
  background-size: 100%;
  background-position: center;
  display: block;
}
</style>
