<template>
  <div id="app">
   <main>
     <div>
        <input type="text" class="search-bar" placeholder="Search...">
     </div>
   </main>
  </div>
</template>

<script>

export default {
  name: 'App',
 data(){
   return{
     api_key: '59000e9f4ecf440228b6f5721e9aac31'
   }
 }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: 'monserat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
}
</style>
    