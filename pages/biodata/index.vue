<template>
    <div id="app">
      <h1>Biodata Saya</h1>
      <div class="biodata-card">
        <img :src="profile.picture" alt="Profile Picture" class="profile-picture" />
        <div class="biodata-details">
          <p><strong>Nama:</strong> {{ profile.name}}</p>
          <p><strong>Alamat:</strong> {{ profile.address}}</p>
          <p><strong>Telepon:</strong> {{ profile.phone }}</p>
          <p><strong>Email:</strong> {{ profile.email }}</p>
          <p><strong>Hobi:</strong> {{ profile.hobby }}</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'App',
    data() {
      return {
        profile: {
          name: 'ILHAM S.H',
          address: 'kp sukamaju',
          phone: '0081779993102',
          email: 'ilhamseptihadi44@gmail.com',
          hobby: 'voli',
        }
      };
    }
  };
  </script>
  
  <style scoped>
  #app {
    font-family: 'Arial', sans-serif;
    text-align: center;
    margin-top: 50px;
  }
  
  .biodata-card {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 10px;
    display: inline-block;
    width: 300px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  .profile-picture {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-bottom: 20px;
  }
  
  .biodata-details p {
    font-size: 16px;
    margin: 5px 0;
  }
  
  strong {
    color: #333;
  }
  </style>
  