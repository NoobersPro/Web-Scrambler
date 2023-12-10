<template>
  <div class="app">
    <header>
      <h1>Web Scrambler</h1>
    </header>
    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
.app {
  text-align: center;
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}

header {
  background-color: #2563eb;
  color: white;
  padding: 20px 0;
  width: 100%;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

header h1 {
  margin: 0;
}

main {
  border-radius: 4px;
  padding: 20px;
  text-align: center;
  background-color: #f9f9f9;
  width: 300px; 
  margin: auto; 
}
</style>