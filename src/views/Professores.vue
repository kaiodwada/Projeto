<template>
  <v-layout>

   


    <v-container class="grey lighten-5 ">
      <v-row no-gutters>
        <v-col v-for="n in 3" :key="n" cols="5" sm="4">
          <v-card class="pa-2">
            <v-img
              src="../assets/prof.jpg"
              aspect-ratio="1"
              max-width="250"
              max-height="300"
            ></v-img>

            <h1>Professor Lucas</h1>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos beatae dicta ex molestiae amet quam fugiat ea dolore iure perspiciatis voluptatem nemo animi, velit iusto asperiores nostrum quae officiis ducimus.
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsam, exercitationem iusto? Sequi, similique cumque. Eius dolorem animi, commodi quae fugiat libero fugit, impedit, laboriosam sint aliquid molestias inventore tempore expedita!
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. In odit quis, rem eum temporibus culpa blanditiis eligendi quaerat saepe adipisci sed autem. Aperiam nobis eaque, amet rem aliquam eum quo.
            </p>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-layout>
</template>
