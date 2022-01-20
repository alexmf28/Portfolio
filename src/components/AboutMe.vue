<template>
  <v-container class="fondoAbout" mt-3 fluid>
    <v-row class="hobbies_skills text-center" wrap>
      <v-col class="justify-start align-start" cols="12">
        <div>
          <h1>ABOUT ME</h1>
        </div>
      </v-col>
      <v-col class="" cols="12">
        <v-avatar class="profile text-center justify-center" size="300">
          <v-img class="avatar_img" src="../assets/Me.jpg"></v-img>
        </v-avatar>
        <v-row align="end">
          <v-col align-self="center" cols="12">
            <div class="mt-5">
              <h2>Who am I</h2>
            </div>
            <p>
              Bienvenidos, soy Alexis, un estudiante apasionado por el
              desarrollo web, actualmente me encuentro en los últimos
              <br />
              ciclos de mi carrera y también estoy estudiando nuevos lenguajes
              cómo Angular junto con TypeScript.
            </p>
          </v-col>
        </v-row>
      </v-col>
      <v-col class="mx-auto" cols="6">
        <v-img height="100%" max-height="500" src="../assets/Auriculares.jpg">
          <v-row align="end" class="fill-height">
            <v-col align-self="center" cols="12" class="hobbies_skills">
              <div class="mt-5 hobbies_skills">
                <h2>Hobbies</h2>
              </div>
              <ul class="lista">
                <li>Leer</li>
                <li>Escuchar música</li>
                <li>Prácticar guitarra</li>
              </ul></v-col
            >
          </v-row>
        </v-img>
      </v-col>
      <v-col class="mx-auto" cols="6">
        <v-img height="100%" max-height="500" src="../assets/Mac.jpg">
          <v-row align="end" class="fill-height">
            <v-col align-self="center" class="white--text" cols="12">
              <div class="mt-5 hobbies_skills">
                <h2>Skills</h2>
              </div>
              <div>
                <img
                  class="skill"
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg"
                  alt="vuejs"
                  width="80"
                  height="80"
                />
                <img
                  class="skill"
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg"
                  alt="nodejs"
                  width="80"
                  height="80"
                />
                <img
                  class="skill"
                  src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg"
                  alt="mssql"
                  width="80"
                  height="80"
                />
                <img
                  class="skill"
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg"
                  alt="mongodb"
                  width="80"
                  height="80"
                />
                <img
                  class="skill"
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
                  alt="javascript"
                  width="80"
                  height="80"
                />

                <img
                  class="skill"
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
                  alt="html5"
                  width="80"
                  height="80"
                />
                <img
                  class="skill"
                  src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg"
                  alt="figma"
                  width="80"
                  height="80"
                />
                <img
                  class="skill"
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
                  alt="css3"
                  width="80"
                  height="80"
                />
                <img
                  class="skill"
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg"
                  alt="csharp"
                  width="80"
                  height="80"
                />
                <img
                  class="skill"
                  src="https://bestofjs.org/logos/vuetify.svg"
                  alt="vuetify"
                  width="80"
                  height="80"
                /></div
            ></v-col>
          </v-row>
        </v-img>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style>
.fondoAbout {
  background: black;
  height: 100%;
}

.skill {
  margin: 2%;
  padding: 1%;
  background: rgba(255, 255, 255, 0.4);
  backdrop-filter: blur(10px);
  border: 1px solid;
}
.hobbies_skills {
  color: rgb(0, 255, 209);
}
.lista {
  list-style: none;
}
@media screen and (max-width: 615px) {
  .skill {
    width: 60px;
    height: 60px;
  }
}
@media screen and (max-width: 375px) {
  .skill {
    width: 40px;
    height: 40px;
  }
}
</style>