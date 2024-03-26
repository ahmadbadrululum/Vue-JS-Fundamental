<template>
    <div class="profile">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <img src="../assets/logo.png" alt="">
          </div>
          <div class="col-md-8">
            <h1>Profile</h1>
            <p>My name is {{ firstName }} {{ lastName }} {{ description }}</p>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  import "bootstrap/dist/css/bootstrap.min.css";
 
  export default {
    name: 'ProfileView',
    data: function() {
      return {
        firstName : 'John',
        lastName : 'Doe',
        description : 'I am a software developer. I love to code and learn new things.'
      }
    },    
    components: {}
  }
  </script>
  