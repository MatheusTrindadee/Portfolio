<template>
  <v-main>
    <v-container>
      <v-card class="mx-auto my-16" color="transparent" id="card" variant="flat">
      <div align="center">
        <v-avatar size="250">
          <v-img src="../assets/img/avatar.jpg" cover></v-img>
        </v-avatar>

        <v-card-title>Desenvolvedor Full-Stack</v-card-title>

        <v-card-text
          >Olá! Me chamo Matheus e sou desenvolvedor full-stack, e ao longo da
          minha carreira, tive a oportunidade de trabalhar em uma variedade de
          projetos desafiadores, desde aplicativos web dinâmicos até sistemas
          complexos de gerenciamento de dados. Atualmente estou cursando Análise
          e Desenvolvimento de Sistemas pelo UniSenai. Principais tecnologias:
          Vue.js, JavaScript, PHP, MySQL e Git.</v-card-text
        >

        <div>
          <v-hover>
            <template v-slot:default="{ isHovering, props }">
              <v-btn
                variant="outlined"
                class="mx-4"
                v-bind="props"
                :color="isHovering ? 'light-green-accent-4' : undefined"
              ><a href="https://wa.me/47996280420" target="_blank" id="link1">WhatsApp</a>
                
              </v-btn>
            </template>
          </v-hover>

          <v-hover>
            <template v-slot:default="{ isHovering, props }">
              <v-btn
                variant="outlined"
                class="mx-4"
                v-bind="props"
                :color="isHovering ? 'purple-darken-2' : undefined"
              ><a href="https://github.com/MatheusTrindadee" target="_blank" id="link2">
                GitHub
                </a>
              </v-btn>
            </template>
          </v-hover>
          
          <v-hover>
            <template v-slot:default="{ isHovering, props }">
              <v-btn
                variant="outlined"
                class="mx-4"
                v-bind="props"
                :color="isHovering ? 'primary' : undefined"
              ><a href="https://www.linkedin.com/in/matheus-willian-b0623a26a/" target="_blank" id="link3">
                LinkedIn
                </a>
              </v-btn>
            </template>
          </v-hover>
        </div>
      </div>
    </v-card>
      <v-divider class="border-opacity-100 my-16" :thickness="2" color="purple-accent-4" id="divisor" inset></v-divider>
    </v-container>
  </v-main>
</template>

<script>
</script>

<style scoped>
#card {
  width: 75%;
}

#link1 {
  text-decoration: none;
  color: #64DD17;
}

#link2 {
  text-decoration: none;
  color: #7B1FA2;
}

#link3 {
  text-decoration: none;
  color: #303F9F;
}

</style>
