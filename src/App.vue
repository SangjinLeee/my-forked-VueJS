<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

 .button{
   padding: 5px;
   color: blue;
}

.button:hover{
  background-color: orange;
}

.button:focus {
  background-color: orange; 
}


.all{
  border-width: 5px;
  width: 400px;
  max-width: 500px;
  margin: auto;
  margin-top: 10px;
}

.title{
  text-align: center;
  font-size: 40px;
}

.name{
  text-align: center;
}
.content{
   text-align: center;
}
img {
  width: 300px;
}

p {
/*   text-align: left;  */
  text-indent: 5%;
  font-size: 18px;
}

.detailsButton {
  margin: 12px;
  position: center; 
  color: blue;
}

  @media (min-width: 500px) and (max-width: 800px) {
    
    .detailsButton {
      display: none;
    }
}

@media (max-width: 500px) {
  .all{
    transform: scale(0.8);
  }
}




</style>
