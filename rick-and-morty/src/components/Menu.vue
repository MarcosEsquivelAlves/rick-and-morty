<template>
  <nav>
    <img src="../assets/svg/img.nav.png" alt="Logo">
    <ul>
      <li><a href="#docs" class="docs">Docs</a></li>
      <li><a href="#about" class="about">About</a></li>
      <li><a href="#support" class="button">SUPPORT US</a></li>
    </ul>
  </nav>

  <img id="titulo" src="../assets/svg/titulo.png" alt="">

  <h1>The Rick and Morty API</h1>

</template>

<script>
export default {
  name: 'MainMenu'
}
</script>

<style scoped>

body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #000;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
}

img {
  max-width: 100%;
  width: 107px;
  padding: 0px;
  margin-left: -10px;
  margin-top: -5px;
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
  font-size: 19px;
  color: black
}

.button {
border: 1px orange solid;
border-radius: 9px;
font-size: 15px;
padding: 10px 17px 10px 17px;
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

#titulo {
  max-width: 100%;
  width: 450px;
  margin: auto;
  margin-left: 38%;
  opacity: 8%;
}

h1 {
  position: absolute;
  top: 30%;
  left: 50%;
  transform: translate(-50%, -50%);
  margin: 0;
  font-size: 120px;
  white-space: nowrap;
  font-family:'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol'; font-weight: bold;
}



</style>
