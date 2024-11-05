<!-- src/components/LoadingScreen.vue -->
<template>
    <div class="loading-screen">
      <img src="../assets/logo_yellow.png" alt="Loading Logo" class="loading-logo" />
    </div>
  </template>
  
  <script>
  export default {
    name: 'LoadingScreen'
  }
  </script>
  
  <style scoped>
  .loading-screen {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #493147;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    z-index: 1000; /* Ensure it's on top */
  }
  .loading-logo {
    width: 150px;
    margin-bottom: 0px;
  }
  </style>
  