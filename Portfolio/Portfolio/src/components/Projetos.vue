<template>
  <v-main>
    <v-container>
      <h1 id="titulo">Projetos</h1>
    </v-container>

    <v-container>
      <v-hover>
        <template v-slot:default="{ isHovering, props }">
          <v-card
            align="center"
            max-width="1200px"
            max-height="500px"
            class="mx-auto"
            variant="elevated"
            v-bind="props"
            :color="isHovering ? 'grey-darken-3' : undefined"
          >
            <v-card-title>Make Your Burger</v-card-title>

            <v-card-text
              >Página de uma hamburgueria criada para o gerenciamento de pedidos
              feito por clientes, com uma simulação de banco feito com JSON.
            </v-card-text>

            <v-card-text>Tecnologia utilizada: Vue.js</v-card-text>

            <v-img
              src="../assets/img/burger.png"
              width="400px"
              height="400px"
            ></v-img>
          </v-card>
        </template>
      </v-hover>
      <v-divider
        class="border-opacity-100 my-16"
        :thickness="2"
        color="purple-accent-4"
      ></v-divider>
    </v-container>

    <v-container class="my-n8">
      <v-hover>
        <template v-slot:default="{ isHovering, props }">
          <v-card
            align="center"
            max-width="1200px"
            max-height="500px"
            class="mx-auto"
            variant="elevated"
            v-bind="props"
            :color="isHovering ? 'grey-darken-3' : undefined"
          >
            <v-card-title>FanClub Berserk</v-card-title>

            <v-card-text
              >Esta página foi criada para ser um FanClub de Berserk. Fiz este
              projeto na faculdade para aprimorar minha habilidade com as
              tecnologias base da programação web.
            </v-card-text>

            <v-card-text
              >Tecnologias utilizadas: HTML5, CSS3 e JavaScript</v-card-text
            >

            <v-img
              src="../assets/img/image.png"
              width="400px"
              height="400px"
            ></v-img>
          </v-card>
        </template>
      </v-hover>
      <v-divider
        class="border-opacity-100 my-16"
        :thickness="2"
        color="purple-accent-4"
      ></v-divider>
    </v-container>

    <v-container class="my-n8">
      <v-hover>
        <template v-slot:default="{ isHovering, props }">
          <v-card
            align="center"
            max-width="1200px"
            max-height="500px"
            class="mx-auto"
            variant="elevated"
            v-bind="props"
            :color="isHovering ? 'grey-darken-3' : undefined"
          >
            <v-card-title>Make Your Burger</v-card-title>

            <v-card-text
              >Página feita para vender um curso de programação para um programador iniciante. Projeto feito na faculdade.
            </v-card-text>

            <v-card-text>Tecnologia utilizada: Vuetify</v-card-text>

            <v-img
              src="../assets/img/escola.png"
              width="400px"
              height="400px"
            ></v-img>
          </v-card>
        </template>
      </v-hover>
    </v-container>
  </v-main>
</template>

<script>
</script>

<style scoped>
#titulo {
  display: inline-block;
  border-bottom: 2px solid #aa00ff;
}

</style>