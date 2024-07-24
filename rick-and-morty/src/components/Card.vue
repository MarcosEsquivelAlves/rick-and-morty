<template>

  <div class="container">


    <div class="container-card">

      <div class="allcards">

        <!-- Allien Googah  -->
        <div class="card">
          <img src="../assets/svg/650.png" alt="Imagem do card 1">
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
          <img src="../assets/svg/519.png" alt="Imagem do card 2">
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
          <img src="../assets/svg/543.png" alt="Imagem do card 3">
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
          <img src="../assets/svg/619.png" alt="Imagem do card 4">
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
          <img src="../assets/svg/630.png" alt="Imagem do card 5">
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
          <img src="../assets/svg/120.png" alt="Imagem do card 6">
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
    </div>
  </div>
  
  <footer class="rodape-list">
      <div class="rodape-todos">
        <ul class="rodape-items">
          <li class="rodape-item">CHARACTERS: 826</li>
          <li class="rodape-item">LOCATIONS: 126</li>
          <li class="rodape-item">EPISODES: 51</li>
        </ul>
    

      <div class="rodape-bolinha-sv">
        <title>Bolinha</title>
      </div>

      <div class="server-status">
        <p>SERVER STATUS</p>
      </div>


      <div class="sv-logo">

        <div class="sv-logo1">
          <a href="https://www.netlify.com/" target="_blank">
            <img id="logo1" src="../assets/svg/netlify.png" alt="Netlify">
          </a>
          <p>DEPLOYS BY</p>
          <div class="net">
            <p>netlify</p>
          </div>
        </div>

        <div class="sv-logo2">
          <a href="https://stellate.co/?ref=powered-by" target="_blank">
            <img id="logo2" src="../assets/svg/stellate.png" alt="Stellate">
          </a>
          <p>POWERED BY</p>
          <div class="ste">
            <p>Stellate</p>
          </div>
        </div>
      </div>


      <div class="redesSociais">

        <div class="rede1">

          <a href="https://github.com/afuh/rick-and-morty-api">
            <img id="img-git" src="../assets/svg/github.png" alt="GitHub">
          </a>
        </div>


        <div class="rede2">

          <a href="https://x.com/i/flow/login?redirect_after_login=%2Frickandmortyapi">
            <img id="img-twitter" src="../assets/svg/twitter.png" alt="Twitter">
          </a>
        </div>

        <div class="rede3">
          <a href="https://rickandmortyapi.com/support-us">
            <img id="img-coracao" src="../assets/svg/coracao.png" alt="Coração">
          </a>
        </div>

        <div class="finalby">

          <div class="arrow-left">
            <span>
              &#10094;
            </span>
          </div>

          <div class="arrow-right">

            <span>
              &#10095;
            </span>
          </div>
        </div>

        <div class="by-name">
          <p>by</p>
        </div>

        <div class="nameby">
          <a href="https://github.com/MarcosEsquivelAlves">
            <p>Marcos Alves</p>
          </a>
        </div>

        <div class="year">
          <p>2024</p>
        </div>

      </div>
    </div>
    </footer>

</template>



<script>
export default {
  name: 'MainCard',
  props: ['imagem', 'titulo', 'localizacao', 'primeiroVisto']
}
</script>



<style scoped>


h2 {
  cursor: pointer;
}

h2:hover {
  color: orange;
}

#p3,
#p5 {
  cursor: pointer;
}

#p3:hover,
#p5:hover {
  color: orange;
}



.bolinha-1,
.bolinha-2 {
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
  background: rgb(39, 43, 51);
  width: 100vw;
  height: 69.30vh;
  margin-top: 135px;
  margin-left: -9px;
} 

.container-card {
  display: flex;
  max-width: 100%;
  width: 100vw;
  justify-content: center;
  align-items: center;
  margin-bottom: 0px;
}



.allcards {
  display: flex;
  width: 1820px;
  background: rgb(39, 43, 51);
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  padding-top: 72px;
  padding-bottom: 80px;
}

.card {
  display: flex;
  align-items: center;
  gap: 250px;
  margin: 12px;
  background: rgb(60, 62, 68);
  border-radius: 10px;
  padding-right: 80px;
  width: 500px;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
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
  color: white;
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
}




#p1,
#p2,
#p3,
#p4,
#p5 {
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
  color: rgb(158, 158, 158);
}

#p2 {
  color: white;
  margin-left: -260px;
  font-size: 17px;
  margin-top: 55px;
  color: rgb(158, 158, 158);
}


#p3 {
  color: white;
  margin-left: -260px;
  font-size: 19px;
  margin-top: 5px;
}

#p4 {
  color: white;
  margin-left: -240px;
  margin-top: -60px;
  font-size: 18px;
}

#p5 {
  font-size: 19px;
  color: white;
  margin-left: -260px;
  margin-top: 80px;
}

.rodape-todos {
  position: relative;
  top: 40px;
}



.rodape-list {
  position: relative;
  top: 400px;
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100vw;
  height: 376px;
  top: 0px;
  list-style-type: none;
  overflow: hidden;
  background: rgb(32, 35, 41);
  margin-left: -9px;
  margin-bottom: -11px;
}



.rodape-items {
  position: relative;
  font-size: 14px;
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  font-weight: bold;
  color: rgb(158, 158, 158);
  list-style-type: none;
  display: flex;
  justify-content: center;
  align-items: center;
  right: 30px;
  top: 30px;
  cursor: pointer;
}

.rodape-item:hover {
  color: orange;
}

.rodape-items li {
  display: flex;
  margin: 0 12px;
  padding: 0;
}


.server-status p {
  font-size: 14px;
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  font-weight: bold;
  color: rgb(158, 158, 158);
  margin: 0 40px;
  position: relative;
  text-align: center;
  right: 11px;
  top: -3px;
  cursor: pointer;
}

.server-status p:hover {
  color: orange;
}

.rodape-bolinha-sv {
  position: relative;
  width: 10px;
  height: 10px;
  background-color: rgb(166, 255, 0);
  border-radius: 50%;
  margin-bottom: 20px;
  margin-left: 110px;
  top: 32px;
  left: 155px;
}

.sv-logo {
  list-style-type: none;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 70px;
  color: rgb(158, 158, 158);
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  font-weight: bold;
  font-size: 10px;
  margin-right: 50px;
  padding-bottom: 20px;
}

.sv-logo #logo1 {
  position: relative;
  max-width: 100%;
  cursor: pointer;
  width: 32px;
  filter: brightness(2000%);
  top: 30px;
}

.sv-logo #logo2 {
  position: relative;
  max-width: 100%;
  cursor: pointer;
  width: 38px;
  filter: grayscale(90%);
  top: 28px;
  right: 10px;
}

.sv-logo .sv-logo1 p {
  font-size: 8px;
  position: relative;
  left: 38px;
  bottom: 13px;
  cursor: pointer;
  letter-spacing: 0.2mm;
}

.sv-logo .sv-logo2 p {
  font-size: 8px;
  position: relative;
  left: 35px;
  bottom: 18px;
  cursor: pointer;
  letter-spacing: 0.2mm;
}

.sv-logo .sv-logo2 .ste p {
  font-size: 17px;
  margin: 0;
  position: relative;
  left: 35px;
  bottom: 28px;
  color: white;
  opacity: 80%;
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  font-weight: bold;
  letter-spacing: 0.2mm;
}

.sv-logo .sv-logo1 .net p {
  font-size: 18px;
  margin: 0;
  position: relative;
  left: 38px;
  bottom: 24px;
  color: white;
  opacity: 80%;
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  font-weight: bold;
  letter-spacing: 0.2mm;
}

.redesSociais {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  bottom: 30px;
}


.redesSociais #img-twitter,
#img-git,
#img-coracao {
  position: relative;
  list-style-type: none;
  width: 18px;
  right: 20px;
}


#img-twitter {
  position: relative;
  left: 65px;
  bottom: -5px;
  filter: invert();
  opacity: 50%;
}


#img-git {
  position: relative;
  left: 38px;
  bottom: -5px;
  filter: invert();
  opacity: 50%;
}

#img-coracao {
  position: relative;
  right: -92px;
  bottom: -5px;
  filter: invert();
  opacity: 50%;
}

#img-twitter:hover,
#img-git:hover,
#img-coracao:hover {
  opacity: 100%;
}

.finalby {
  position: relative;
  font-size: 14px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: -110px;
  right: 45px;
  color: rgb(158, 158, 158);
}

.by-name {
  font-size: 14px;
  position: relative;
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  color: rgb(158, 158, 158);
  top: 54px;
  right: 40px;
}

.nameby p {
  text-decoration: none;
  font-size: 14px;
  margin: 0;
  color: white;
  text-decoration: none;
  position: relative;
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  top: 55px;
  right: 35px;
}

.nameby p:hover {
  color: orange;
}


.nameby a {
  text-decoration: none;
}


.nameby p::after {
  content: '';
  position: absolute;
  left: 0;
  bottom: 0px;
  width: 100%;
  height: 2px;
  background-color: orange;
}


.nameby p:hover::after {
  background-color: transparent;
}


.year {
  position: relative;
  font-size: 14px;
  color: rgb(158, 158, 158);
  font-family: 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  top: 56px;
  right: 30px;
}

::selection{
  color: orange;
  background-color: black;
}


</style>
