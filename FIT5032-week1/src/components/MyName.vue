<template>
    <div>
      Welcome: {{ name }}
      <br />
      <a href="https://github.com/yxcmongnan" target="_blank" rel="noopener">Xicheng Ye's GitHub</a>
    </div>
  </template>
  
  <script setup>
  const name = 'Xicheng Ye'; 
  </script>
  
  <style scoped>
  div {
    font-size: 20px;
    color: #42b983; 
  }
  
  a {
    color: #007bff;
    text-decoration: none;
  }
  
  a:hover {
    text-decoration: underline;
  }
  </style>
  