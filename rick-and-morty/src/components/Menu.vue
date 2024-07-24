<template>
  <nav>
    <img src="../assets/svg/img.nav.png" alt="Logo">
    <ul>
      <li id="doc-1"><a href="https://rickandmortyapi.com/documentation" target="_blank" class="docs">Docs</a></li>
      <li id="about-1"><a href="https://rickandmortyapi.com/about" target="_blank" class="about">About</a></li>
      <li id="sup-1"><a href="https://rickandmortyapi.com/support-us" target="_blank" class="button">SUPPORT US</a></li>
    </ul>
  </nav>

  <div class="th1">
    <img id="titulo" src="../assets/svg/titulo.png" alt="">
    <h1>The Rick and Morty API</h1>
  </div>

  
  
  

  


</template>

<script>
export default {
  name: 'MainMenu'
}
</script>

<style scoped>

::selection{
  color: orange;
  background-color: black;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
}


img {
  max-width: 100%;
  width: 96px;
  padding: 0px;
  margin-left: -9px;
  margin-top: -20px;
  cursor: pointer;
}

ul {
  display: flex;
  list-style: none;
  padding: 0;
  margin: 0;
  margin-right: 12px;
}

li {
  margin: 20px;
}

a {
  font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-weight: bold;
  text-decoration: none;
  font-size: 18px;
  color: black
}

#doc-1 {
  position: relative; 
  left: 30px;
  top: -11px;
}

#about-1 {
  position: relative; 
  left: 20px;
  top: -11px;
}

#sup-1 {
  position: relative; 
  top: -5px;
  left: 10px;

}

.button {
border: 1px orange solid;
border-radius: 9px;
font-size: 13px;
padding: 10px 18px 10px 18px;
transition: 1s;
color:black;
transition: background-color 0.2s, color 0.2s;
}

.button:hover {
  background-color: orange;
  color:white;
}

.docs .about{
  color:orange;
  transition: color 0.2s;
}

.docs:hover, .about:hover {
  color: orange;
}

.th1 {
  justify-content: center;
  text-align: center;
  align-items: center;
  flex-wrap: wrap;
  min-width: 25%;
}

#titulo {
  position: relative;
  left: 14px;
  top: -1px;
  width: 450px;
  opacity: 5%;
  margin-top: -12px;
  min-width: 20%;
  cursor: default;
}

h1{
  position: relative;
  text-align:center;
  margin-top: -337px;
  font-size: 100px;
  position:relative;
  font-weight: bold;
  bottom: 13px;
  font-family:'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol'; font-weight: 800;
  }


</style>
