<template>
  <div class="content-list">
    <div class="card-item">
      <div class="card-item-header">
        <div class="card-item-header-content">
          <h2 class="description-item">Lorem Ipsum</h2>
        </div>
        <div class="card-item-header-content">
          <p class="value-item color-green">R$ 200,00</p>
        </div>
      </div>
      <div class="card-item-option">
        <button type="button" class="button-option">
          <span class="icon-option"></span>
        </button>
      </div>
    </div>

    <div class="card-item">
      <div class="card-item-header">
        <div class="card-item-header-content">
          <h2 class="description-item">Lorem Ipsum</h2>
        </div>
        <div class="card-item-header-content">
          <p class="value-item color-red">R$ 200,00</p>
        </div>
      </div>
      <div class="card-item-option">
        <button type="button" class="button-option">
          <span class="icon-option"></span>
        </button>
      </div>
    </div>

    <div class="card-item">
      <div class="card-item-header">
        <div class="card-item-header-content">
          <h2 class="description-item">Lorem Ipsum</h2>
        </div>
        <div class="card-item-header-content">
          <p class="value-item color-green">R$ 200,00</p>
        </div>
      </div>
      <div class="card-item-option">
        <button type="button" class="button-option">
          <span class="icon-option"></span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'ListItems'
};

</script>

<style scoped>

.content-list {
  background-color: var(--black);
  height: 78vh;
  width: 100%;
  border-radius: 16px 16px 0 0;
  padding: 1.68rem;
}

.card-item {
  max-width: 450px;
  padding: 1rem 1.1875rem;
  margin: 0 auto 1.8125rem;
  background-color: var(--gray);
  border-radius: 8px;

  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.card-item-header {
  display: flex;
  flex-direction: column;
}

.description-item {
  font-size: 1rem;
  font-weight: bold;
  color: var(--black);
  margin-bottom: .4375rem;
}

.value-item {
  font-size: .8rem;
}

.button-option {
  background-color: transparent;
  border: none;
  font-size: 0;
}

.icon-option{
  width: 9px;
  height: 34px;
  background-image: url('../assets/more-icon.png');
  background-repeat: no-repeat;
  background-size: auto 100%;
  background-position: center;
  display: block;
}

</style>
