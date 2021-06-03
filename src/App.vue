<template>
  <div id="app">
    <Header />
    <ListItems />
  </div>
</template>

<script>
import Header from './components/Header';
import ListItems from './components/ListItems';

export default {
  name: 'App',
  components: {
    Header,
    ListItems
  }
}
</script>

<style>
:root {
  --white: #F9FAFB;
  --black: #111827;
  --gray: #D1D5DB;
  --green: #10B981;
  --red: #EF4444;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body, html {
  font-size: 16px;
  font-family: 'Roboto', sans-serif;
  background-color: var(--white);
}

button { cursor: pointer; }

.color-green { color: var(--green); }
.color-red { color: var(--red); }

.container {
  width: 100%;
  max-width: 800px;

  margin: auto;
}
</style>
