<script setup>
import { ref } from "vue";

</script>

<template>
  <v-app>
    <div class="appBar">
      <v-app-bar color="black" :elevation="24" :height="90">
        <v-app-bar-nav-icon icon="mdi-radio"></v-app-bar-nav-icon>
        <v-app-bar-title >WHCK</v-app-bar-title>
        <v-img class="headerImg" src="../public/images/site-logo-light.png" cover></v-img>
      </v-app-bar>
    </div>

    <v-main style="background-color: SteelBlue;">
      <div class="secondRow">
        <div class="audio">
          <p class="typewriter">Join #whck-radio to chat
            about what you're hearing!</p>
            <div class="block">
            <audio controls preload="auto">
                <source src="https://whck.formlabs.com/stream" type="audio/mpeg">
            </audio>
            </div>
          <p class="notWorking">Stream not Working? <a href="https://whck.formlabs.com/stream">Click
            Here</a> for the direct link.</p>
      </div>
      </div>
      <div class="vCard">
        <div class="myDiv1"> 
          <v-card class="card">
            <v-img src="../public/images/bp-wave (1).png" height="200px" cover class="card-img"></v-img>
            <v-card-item class="card-content">
              <v-card-title class="title"></v-card-title>
            </v-card-item>
          </v-card>
        </div>

        <div class="myDiv">
          <v-card class="card">
            <v-img src="../public/images/Weird Space 1080 nowm.png"  height="200px" cover class="card-img"></v-img>
            <v-card-item class="card-content">
              <v-card-title class="title">Friday</v-card-title>
            </v-card-item>
          </v-card>
          <div class="sheet"> 
            <v-sheet class="hide" color="white">
              <v-table class="custom-table">
                <thead>
                  <tr>
                    <th class="table-header">TIME</th>
                    <th class="table-header">SHOW</th>
                    <th class="table-header">HOST</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>8:00 AM EDT<br>14:00 CEST</td>
                    <td>Jamtastic</td>
                    <td>Jon Evans</td>
                  </tr>
                  <tr>
                    <td>9:00 AM EDT<br>14:00 CEST</td>
                    <td>Hack Caffeinated</td>
                    <td>Jon Evans</td>
                  </tr>
                  <tr>
                    <td>10:00 AM EDT<br>16:00 CEST</td>
                    <td>Selling the Dream</td>
                    <td>Rob Ortiz</td>
                  </tr>
                  <tr>
                    <td>11:00 AM EDT<br>17:00 CEST</td>
                    <td>Parallel Beats<br> Block Party</td>
                    <td>Gary Rowe</td>
                  </tr>
                  <tr>
                    <td>12:00 PM EDT<br>18:00 CEST</td>
                    <td>The Plague of<br>Sound</td>
                    <td>Declan GS</td>
                  </tr>
                  <tr>
                    <td>1:00 PM EDT<br>19:00 CEST</td>
                    <td>Open Format<br>Goodness PT.3</td>
                    <td>Dj Wordless</td>
                  </tr>
                  <tr>
                    <td>2:00 PM EDT<br>20:00 CEST</td>
                    <td>Funky, percussive<br>house and afro<br>-latin vibes</td>
                    <td>DJ Abu Pablo</td>
                  </tr>
                  <tr>
                    <td>3:00 PM EDT<br>21:00 CEST</td>
                    <td>Afternoon Dubs</td>
                    <td>Anonymous</td>
                  </tr>
                  <tr>
                    <td>4:00 PM EDT<br>22:00 CEST</td>
                    <td>Reading Wacky and<br>Wild Reddit<br>Stories</td>
                    <td>The Interns</td>
                  </tr>
                  <tr>
                    <td>5:00 PM EDT<br>23:00 CEST</td>
                    <td>Interview with<br> Stephen Hawes,<br> CEO of Opulo</td>
                    <td>Jake Misra</td>
                  </tr>
                  <tr>
                    <td>6:00 PM EDT<br>00:00 CEST</td>
                    <td>Poolside Sunset</td>
                    <td>Jake Misra</td>
                  </tr>
                  <tr>
                    <td>7:00 PM EDT<br>01:00 CEST</td>
                    <td>The Plague of<br>Sound</td>
                    <td>Declan GS</td>
                  </tr>
                  <tr>
                    <td>8:00 PM EDT<br>02:00 CEST</td>
                    <td>Twilight in the Jungle</td>
                    <td>Anonymous</td>
                  </tr>
                  <tr>
                    <td>9:00 PM EDT<br>03:00 CEST</td>
                    <td> Night FUSEion</td>
                    <td>Rob Ortiz</td>
                  </tr>
                  <tr>
                    <td>10:00 PM EDT<br>04:00 CEST</td>
                    <td>Formlabs Holiday<br> Party 2022<br>(prerecorded)</td>
                    <td>Jake Misra
                    </td>
                  </tr>
                </tbody>
              </v-table>            
          </v-sheet>
          </div>
        </div>
        <div class="myDiv3">
          <v-card class="card">
            <v-img src="../public/images/Cyberform.png"  height="200px" cover class="card-img"></v-img>
            <v-card-item class="card-content">
              <v-card-title class="title"></v-card-title>
            </v-card-item>
          </v-card>
        </div>
      </div>
    </v-main>

    <v-footer style="background-color: steelblue; color: white;">© 2024 Made with love by the #whck-radio team</v-footer>
  </v-app>
</template>

<style scoped>
.table-container {
  width: 100%;
  overflow-x: auto;
}

.custom-table {
  width: 100%;
  border-collapse: collapse;
}

.table-header {
  width: 33%; 
  text-align: center;
  background-color: #f4f4f4;
  border: 1px solid #ddd;
}

.custom-table th, .custom-table td {
  border: 1px solid #ddd;
  text-align: left;
}

.custom-table td {
  white-space: nowrap; 
}

.block {
  display: grid;
  grid-template-columns: auto;
  gap: 20px;
}

.v-btn {
  margin-top: 10px;
}

.v-main {
  background-color: SteelBlue;
  min-height: 120vh;
}

.typewriter {
  font-weight: 300;
  font-size: 2em;
  display: inline-block;
  border-right: solid 3px black;
  width: 0;
  overflow: hidden;
  white-space: nowrap;
  animation: typewriter 2s steps(21) 1s forwards, blink 0.5s steps(1) infinite;
}

@keyframes typewriter {
  to { width: 42ch; }
}

@keyframes blink {
  from { border-color: transparent; }
  50% { border-color: black; }
  to { border-color: transparent; }
}

.audio {
  margin-top: 15px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.vCard {
  margin-top: 20px;
  display: grid;
  grid-template-columns: auto auto auto;
  margin: 15px;
  gap: 10px;
}

.card:hover {
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3), 0 8px 24px rgba(0, 0, 0, 0.25);
}

.card {
  position: relative;
  overflow: hidden;
  height: 200px;
  width: 100%;
}

.card-img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: 1;
}

.card-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 1;
  color: white;
  text-align: center;
}

.sheet {
  width: 120px;
  text-align: center;
  overflow: hidden;
  transition: opacity 0.5s ease, height 0.5s ease;
  font-family: Proxima Nova,proxima-nova,Helvetica Neue,Helvetica,Arial,sans-serif;
  text-transform: uppercase;
  font-weight: bolder;
}

.title {
  font-size: 24px;
  font-weight: bold;
}

.headerImg {
  margin: 20px;
  max-width: 250px;
}

span {
  margin: 10px;
}

.myDiv {
  position: relative;
}

.hide {
  opacity: 0;
  height: 0;
  transition: opacity 0.5s ease, height 0.5s ease;
  overflow: hidden;
  position: absolute;
  top: 100%;
  left: 0;
  width: 100%;
}

.myDiv:hover .hide {
  opacity: 1;
  height: auto;
}

.notWorking {
  margin: 5px;
}

main {
  overflow-x: hidden;
}


@media only screen and (max-width: 576px) {
  .vCard {
    grid-template-columns: 1fr; 
  }

  .myDiv1,.myDiv3{
    display: none;
  }

  .hide {
    opacity: 1;
    height: auto; 
  }
  .sheet {
    opacity: 1;
  }
  
  .notWorking {
    text-align: center;
  }

  .typewriter {
    display: none;
  }

  .custom-table {
    font-size: 12px;
  }

  .table-header, .custom-table th, .custom-table td {
    padding: 2px 4px;
  }

  .custom-table td {
    white-space: normal; 
    word-wrap: break-word;
    margin: 0; /* Removed margin */
    padding: 4px 8px;
  }
}

/* Small Devices (Phones) */
@media only screen and (min-width: 577px) and (max-width: 767px) {
  /* Styles for small screens (e.g., landscape phones) */
  .container {
    padding: 20px;
  }
}

/* Medium Devices (Tablets) */
@media only screen and (min-width: 768px) and (max-width: 991px) {
  /* Styles for tablets */
  .container {
    padding: 30px;
  }
}

/* Large Devices (Desktops) */
@media only screen and (min-width: 992px) and (max-width: 1199px) {
  /* Styles for desktops and larger tablets */
  .container {
    padding: 40px;
  }
}

</style>
