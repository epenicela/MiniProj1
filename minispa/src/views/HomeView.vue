<template>

  <NavBar />
  <v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background }">
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="my-pic-1.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h4 class="red--text text-darken-4 top">Ola, sou Elton Penicela</h4>
          <h1 class="red--text">Desenvolvedor full stack</h1>
          <p class="just grey-text">
            Hello, sou Elton Penicela, licenciado e Engenharia Informática,
            actualmente trabalho no Instituto Superior Politécnico de Tete
            (em Moçambique) como investigador afecto no Centro de Investigação de Recursos Técnicos e Tecnológicos.<br>
          </p>
          <v-btn class="branco" tile color="#A7121D" dark>O que faço</v-btn>
        </v-col>

        <v-col cols="12">
          <h4></h4>
        </v-col>
        <v-col cols="12" class=" padd">
          <div id="home" style="//background: red;">
            <v-row>

              <div class="direito branco"></div>

              <div class=" branco sizeW sizeH child bgColor1">
                <v-icon x-large class="ml-3">
                  mdi-palette-swatch
                </v-icon>
                <h3 class="branco white--text ml-3mt-4">Front-end</h3>
                <p class=" branco justmine grey--text ml-3 mt-6">
                  Dominio de VUE, CSS, HTML, REACT, com as quais o utilizador interage...<br>
                </p>
                <v-btn color="#1e1e1e">
                  Saiba mais
                  <v-icon right>mdi-arrow-right</v-icon>
                </v-btn>
              </div>

              <div class="branco sizeW sizeH child bgColor2">
                <v-icon x-large class="ml-3" dark>mdi-shopping</v-icon>
                <h3 class="white--text ml-3 mt-4">Back-end</h3>
                <p class="grey--text ml-3 mt-6">
                  Dominio de JS,PHP, JAVA, PYTHON, DART<br>
                </p>
                <center>
                  <v-btn class="bgColor2">
                    Saiba mais
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </center>
              </div>

              <div class="branco sizeW sizeH child bgColor1">
                <v-icon x-large class="ml-3">mdi-book-open-page-variant</v-icon>
                <h3 class="white--text ml-3 mt-4">Sever</h3>
                <p class="grey--text ml-3 mt-6">
                  Domino de linux, centos, windows, etc<br>
                </p>
                <v-btn color="#1e1e1e">
                  Saiba mais
                  <v-icon right>mdi-arrow-right</v-icon>
                </v-btn>
              </div>

              <v-col cols="12" class="mt-10"></v-col>



              <div class="direito branco"></div>
              <div class="child sizeW bgColor2">
                <center>
                  <h1 class="branco  red--text text-darken-4 mt-4 number">6</h1>
                </center>
                <h4 class="branco white--text mt-4">Anos de experiencia</h4>
              </div>

              <div class="child2 mRight">
                <v-row>
                  <v-col cols="12" class="branco">
                    <div class="sizeW sizehhh child2 mButton padding bgColor1">
                      <h1 class="branco red--text text--darken-4">20+</h1>
                      <p class="branco grey--text">Clientes</p>
                    </div>
                  </v-col>

                  <v-col cols="12" class="branco">
                    <div class="sizeW sizehhh contrapeso child2 padding bgColor1">
                      <h1 class="red--text text--darken-4">122+</h1>
                      <p class="grey--text">Projectos</p>
                    </div>
                  </v-col>
                </v-row>
              </div>

              <div class="child2 mRight" style="margin-left: -2%;">
                <v-row>
                  <v-col cols="12" class="branco">
                    <div class="sizeW sizehhh child2 mButton padding bgColor1">
                      <h1 class="branco red--text text--darken-4">6</h1>
                      <p class="branco grey--text">Anos de experiencia</p>
                    </div>
                  </v-col>

                  <v-col cols="12" class="branco">
                    <div class="sizeW sizehhh contrapeso child2 padding bgColor1">
                      <h1 class="red--text text--darken-4">15</h1>
                      <p class="grey--text">Arquivos</p>
                    </div>
                  </v-col>
                </v-row>
              </div>

            </v-row>
          </div>
        </v-col>



        <v-col md="3" offset-md="3" id="about">

          <h4 class="white--text" style="margin-top: 10%;">PROJECTOS FUTUROS</h4>
          <p class="just grey--text">
            A abordagem sobre praticas de desenvolvimento web
            mostra-nos a necessidade de implementarmos modelos
            e padrões cientificamente comprovados para termos
            projecto bem sucedidos.
            <br>
          </p>
          <v-col md="5" class="text-end">
            <v-btn class="branco" tile color="#A7121D" dark>visualizar mais</v-btn>
          </v-col>
        </v-col>

        <div class="direito branco"></div>

        <v-col md="3" class="backcard">
          <v-card class="backcard pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
            <v-img src="pensource-web.JPG" contain>
            </v-img>
          </v-card>
        </v-col>
        <v-col md="3" class="backcard">
          <v-card class="backcard pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
            <v-img src="pensource-desk.JPG" contain>
            </v-img>
          </v-card>
        </v-col>

        <v-col md="3" class="backcard">
          <v-card class="backcard pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
            <v-img src="mobile.JPG" contain>
            </v-img>
          </v-card>
        </v-col>

        <v-col md="3" class="backcard">
          <v-card class="backcard pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
            <v-img src="bd.png" contain>
            </v-img>
          </v-card>
        </v-col>

        <div class="second" style="margin-top: 14%;">
          <v-col cols="12" class="padd topInverse">
            <div class="secondchild1" id="hobbies">
              <v-row>
                <v-col cols="1">
                  <h1 class="white--text">
                    Hobbies
                  </h1>
                  <p class="grey--text just">
                  <h3 style="margin-left:5%;">
                    ✓ Leitura (Técnico, Geral)<br>
                    ✓ Internet<br>
                    ✓ Desporto<br>
                    ✓ Investigação<br>
                    ✓ Viagens
                  </h3>
                  </p>
                  <v-col cols="5">
                    <v-btn tile color="#A71221D" dark class="mt-16">Mais</v-btn>
                  </v-col>
                </v-col>
              </v-row>
            </div>
          </v-col>
        </div>


      </v-row>
      <v-toolbar class="topToolbar branco"  style="margin-top:10%; color: #111111 !important; background: #ffffff !important;">
        <div style="position: absolute; margin-left: auto; margin-right: auto;
        left:0; right:0; text-align: center;">
          <v-btn text>QUEM SOU EU</v-btn>
          <v-btn text>O QUE FACO</v-btn>
          <v-btn text>HOBBIES</v-btn>
        </div>
      </v-toolbar>
    </v-container>
  </v-app>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import NavBar from '../components/NavBar.vue';
//import Footer from '../components/Footer.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    NavBar,
    //Footer
  },
});
</script>
<style scoped>
.top {
  margin-top: 180px;

}

.topInverse {
  margin-top: -250px;
}

.topTolbar {
  margin-top: 100px;
  text-align: center;
}

.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(to right,
      #181818,
      #181818 50%,
      #181818 50%);
  text-align: center;
  padding: 2rem 2rem;
}

.second {
  width: 100%;
  height: 400px;
  text-align: center;
  padding: 2rem 2rem;
}

.secondchildi {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}

.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}

.bgColor1 {
  background-color: #1e1e1e;
}

.bgColor2 {
  background-color: #ce1d2a;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}

.child2 {
  display: inline-block;
  vertical-align: middle;
  width: 245px;
}

.divcenter {
  //align-items: center;
  //left: 50%;
  //transform: translate(35%, 0%);

}

.mRigth {
  margin-right: 8px;
}

.mButton {
  margin-right: 8px;
}

.padding {
  padding: 8px 0px 0px;
}

.branco {
  color: #fff !important;
}

.preto {
  color: #111111 !important;
}


.footer {
  color: #fff !important;
  background: #181818 !important;
}

.backcard {
  background: #fff !important;
  height: 300px;

}

.col-12.childcol {
  padding: 0 !important;
}

.sizeW {
  width: 200px;
}

.sizehhh {
  //margin-top:-10px;
  height: 110px;
  padding-left: 10px;
  padding-top: 15px;
}

.contrapeso {
  margin-top: -15px;
}

.sizeH {
  height: 250px;
}

.just {
  text-align: justify;
  width: 400px;
}

.direito {
  width: 30%;
}

.justmine {
  text-align: justify;
  font-size: 12pt;
}

h1.number {
  font-size: 50px;
  font-weigth: bold;
}
</style>