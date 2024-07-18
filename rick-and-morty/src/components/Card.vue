<template>

<div class="container">
  

   <!-- Allien Googah  -->
  <div class="card">
    <img src= "../assets/svg/650.png" alt="Imagem do card 1">
    <h2>Allien Googah</h2>
    <div class="bolinha-2">
      <title>Bolinha</title>
    </div>
    <div>
      <p id="p4">Dead - Alien</p>
      <p id="p1">Last known location:</p>
      <p id="p3">Unknown</p>
      <p id="p2">First seen in:</p>
      <p id="p5">Allien Planet</p>
    </div>
  </div>

   <!-- Arcade Allien  -->
  <div class="card">
    <img src= "../assets/svg/519.png" alt="Imagem do card 2">
    <h2>Arcade Allien</h2>
    <div class="bolinha-1">
      <title>Bolinha</title>
    </div>
    <div>
      <p id="p4">Alive - Mystic Creature</p>
      <p id="p1">Last known location:</p>
      <p id="p3">Arcade Planet</p>
      <p id="p2">First seen in:</p>
      <p id="p5">Thatanos</p>
    </div>
  </div>

  <!-- Mutant Fly  -->
  <div class="card">
    <img src= "../assets/svg/543.png" alt="Imagem do card 3">
    <h2>Mutant Fly</h2>
    <div class="bolinha-1">
      <title>Bolinha</title>
    </div>
    <div>
      <p id="p4">Alive - Fly Mutant</p>
      <p id="p1">Last known location:</p>
      <p id="p3">Jupiter</p>
      <p id="p2">First seen in:</p>
      <p id="p5">Flies World</p>
    </div>
  </div>

  <!-- Teacher Rick  -->
  <div class="card">
    <img src= "../assets/svg/619.png" alt="Imagem do card 4">
    <h2>Teacher Rick</h2>
    <div class="bolinha-2">
      <title>Bolinha</title>
    </div>
    <div>
      <p id="p4">Dead - Human</p>
      <p id="p1">Last known location:</p>
      <p id="p3">Earth</p>
      <p id="p2">First seen in:</p>
      <p id="p5">Rick and Morty Portal</p>
    </div>
  </div>

  <!-- Morty  -->
  <div class="card">
    <img src= "../assets/svg/630.png" alt="Imagem do card 5">
    <h2>Morty</h2>
    <div class="bolinha-1">
      <title>Bolinha</title>
    </div>
    <div>
      <p id="p4">Alive - Human</p>
      <p id="p1">Last known location:</p>
      <p id="p3">Earth</p>
      <p id="p2">First seen in:</p>
      <p id="p5">Earth</p>
    </div>
  </div>

  <!-- Evil Summer Clone  -->
  <div class="card">
    <img src= "../assets/svg/120.png" alt="Imagem do card 6">
    <h2>Evil Clone</h2>
    <div class="bolinha-2">
      <title>Bolinha</title>
    </div>
    <div>
      <p id="p4">Dead - Robot</p>
      <p id="p1">Last known location:</p>
      <p id="p3">Earth</p>
      <p id="p2">First seen in:</p>
      <p id="p5">Meeseeks and Destroy</p>
    </div>
  </div>  
  
</div>

</template>



<script>  
export default {
  name: 'MainCard',
  props: ['imagem', 'titulo', 'localizacao', 'primeiroVisto']
}
</script>



<style scoped>


.bolinha-1, .bolinha-2 {
    width: 10px;
    height: 10px;
    background-color: rgb(166, 255, 0);
    border-radius: 50%;
    margin-bottom: 95px;
    margin-left: -240px;
}

.bolinha-2 {
  background-color: red;
}


.container {
    display: flex;
    max-width: 100%;
    width: 100%;
    background:rgb(39, 43, 51);
    margin-top: 130px;
    flex-wrap: wrap;
    padding-top: 70px;
    justify-content: center;
    align-items: center;
  }

.card {
  position: relative;
  display: flex;
  align-items: center;
  gap: 250px;
  margin: 20px;
  background: rgb(60, 62, 68);
  border-radius: 10px;
  padding-right: 80px;
  width: 500px;
  height: 100%;
  flex-shrink: 0;
  flex-grow: 0;
  overflow: hidden;
}


.card img {
  display: block;
  width: 230px;
  max-width: 100%;
  border-top-left-radius: 10px;
  border-bottom-left-radius: 10px;
}



h2 {
  position: absolute;
  margin-left: 245px;
  margin-bottom: 200px;
  font-size: 30px;
  color:white;
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
} 




#p1, #p2, #p3, #p4, #p5  {
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  padding: 0;
  margin: 0;
  position: absolute;
  display: inline;
}



#p1 {
  margin-left: -260px;
  margin-top: -20px;
  font-size: 17px;
  color:rgb(158, 158, 158);
}

#p2 {
  color:white;
  margin-left: -260px;
  font-size: 17px;
  margin-top: 55px;
  color:rgb(158, 158, 158);
}


#p3 {
  color:white;
  margin-left: -260px;
  font-size: 19px;
  margin-top: 5px;
}

#p4 {
  color:white;
  margin-left: -240px;
  margin-top: -60px;
  font-size: 18px;
}

#p5 {
  font-size: 19px;
  color:white;
  margin-left: -260px;
  margin-top: 80px;
}












</style>
