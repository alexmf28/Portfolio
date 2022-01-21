<template>
  <v-container fluid class="fondoProjects">
    <v-row class="hobbies_skills text-center" wrap>
      <v-col cols="12">
        <div>
          <h1>Projects</h1>
        </div>
      </v-col>

      <v-col class="d-flex justify-center align-center" xs12>
        <div class="articulo">
          <img class="image_img" src="../assets/ResponsivePage.jpg" alt="" />
          <div class="image_overlay image_overlay_blur">
            <div class="image_titulo">
              Responsive Page
              <p class="image_descripcion">Utilicé tecnologías cómo:</p>
              <div class="iconos">
                <img
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
                  alt="html5"
                  width="60"
                  height="60"
                />

                <img
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
                  alt="css3"
                  width="60"
                  height="60"
                />
              </div>
            </div>
            <v-col class="d-flex justify-center align-center">
              <v-btn small dark class="mx-3">
                <a
                  style="color: rgb(0, 255, 209); text-decoration: none"
                  href="https://condescending-leakey-fb037c.netlify.app"
                  target="_blank"
                  >Demo <i class="fas fa-laptop-code"></i
                ></a>
              </v-btn>
              <v-btn small dark class="mx-3">
                <a
                  style="color: rgb(0, 255, 209); text-decoration: none"
                  href="https://github.com/alexmf28/TeamPage"
                  target="_blank"
                  >Código <i class="fab fa-github"></i
                ></a>
              </v-btn>
            </v-col>
          </div>
        </div>
      </v-col>
      <v-col cols=" d-flex justify-center align-center " xs12>
        <div class="articulo">
          <img class="image_img_team" src="../assets/TeamPage.jpg" alt="" />
          <div class="image_overlay image_overlay_blur">
            <div class="image_titulo">
              Team Page
              <p class="image_descripcion">Utilicé tecnologías cómo:</p>
              <div class="iconos">
                <img
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
                  alt="html5"
                  width="60"
                  height="60"
                />

                <img
                  src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
                  alt="css3"
                  width="60"
                  height="60"
                />
              </div>
            </div>
            <v-col class="d-flex justify-center align-center">
              <v-btn small dark class="mx-3">
                <a
                  style="color: rgb(0, 255, 209); text-decoration: none"
                  href="https://condescending-leakey-fb037c.netlify.app"
                  target="_blank"
                  >Demo <i class="fas fa-laptop-code"></i
                ></a>
              </v-btn>
              <v-btn small dark class="mx-3">
                <a
                  style="color: rgb(0, 255, 209); text-decoration: none"
                  href="https://github.com/alexmf28/TeamPage"
                  target="_blank"
                  >Código <i class="fab fa-github"></i
                ></a>
              </v-btn>
            </v-col>
          </div>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style>
.fondoProjects {
  background-image: url();
}

.articulo {
  position: relative;

  margin: 2%;
}
.image_img {
  display: block;
  width: 24rem;
  height: 18rem;
  border-radius: 20px;
}
.image_img_team {
  display: block;
  width: 24rem;
  height: 18rem;
  border-radius: 20px;
}
.image_overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  width: 24rem;
  height: 18rem;
  background: rgba(0, 0, 0, 0.5);
  color: white;
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: center;
  font-family: "Quicksand", sans-serif;
  opacity: 0;
  transition: 0.25s;
  border-radius: 20px;
}
.image_overlay_blur {
  backdrop-filter: blur(5px);
}
.image_overlay > * {
  transform: translateY(20px);
  transition: 0.5s;
}
.image_overlay:hover {
  opacity: 1;
}
.image_overlay:hover > * {
  transform: translateY(0);
}
.image_titulo {
  font-size: 2em;
  margin-top: 3%;
}
.image_descripcion {
  font-size: 0.8em;
}

.iconos {
  display: flex;
  column-gap: 50px;
  justify-content: center;
}
@media screen and (max-width: 615px) {
  .image_img {
    width: 20rem;
    height: 14rem;
  }
  .image_img_team {
    width: 20rem;
    height: 14rem;
  }
  .image_overlay {
    width: 20rem;
    height: 14rem;
  }
  .image_titulo {
    font-size: smaller;
  }
  .image_descripcion {
    font-size: small;
  }
}
@media screen and (max-width: 375px) {
  .image_img {
    width: 14rem;
    height: 10rem;
  }
  .image_img_team {
    width: 14rem;
    height: 10rem;
  }
  .image_overlay {
    width: 14rem;
    height: 10rem;
  }
}
</style>