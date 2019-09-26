<template>

   <v-layout >

        <v-card class="mx-5 my-5"  width="100%" height="50">
            <div class="blue">
            <p class="text-center md">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Harum maiores modi quidem veniam, expedita quis laboriosam, ullam facere adipisci, iusto, voluptate sapiente corrupti asperiores rem nemo numquam fuga ab at.</p>
            </div>
        </v-card>

    <v-flex xs12 sm6>
      <v-card class="my-5  mx-5 float-sm-left">
        <v-img
          src="https://cdn.vuetifyjs.com/images/cards/desert.jpg"
          aspect-ratio="2.22"
        ></v-img>

        <v-card-title primary-title>
          <div >
            <h3 class="headline mb-2">Lorem</h3>
            <div> {{ card_text }} </div>
          </div>
        </v-card-title>

      </v-card>
    </v-flex>


     <v-flex xs12 sm6>
      <v-card class="my-5 mx-5 float-sm-left">
        <v-img
          src="https://cdn.vuetifyjs.com/images/cards/desert.jpg"
          aspect-ratio="2.22"
        ></v-img>

        <v-card-title primary-title>
          <div >
            <h3 class="headline mb-2">Lorem</h3>
            <div> {{ card_text }} </div>
          </div>
        </v-card-title>

      </v-card>
    </v-flex>


 <v-flex xs12 sm6>
      <v-card class="my-5 mx-5 float-sm-left">
        <v-img
          src="https://cdn.vuetifyjs.com/images/cards/desert.jpg"
          aspect-ratio="2.22"
        ></v-img>

        <v-card-title primary-title>
          <div >
            <h3 class="headline mb-2">Lorem</h3>
            <div> {{ card_text }} </div>
          </div>
        </v-card-title>

      </v-card>
    </v-flex>


  </v-layout>

</template>

<script>
  export default {
    data () {
      return {
        card_text: 'Lorem ipsum dolor sit amet, brute iriure accusata ne mea. Eos suavitate referrentur ad, te duo agam libris qualisque, utroque quaestio accommodare no qui. Et percipit laboramus usu, no invidunt verterem nominati mel. Dolorem ancillae an mei, ut putant invenire splendide mel, ea nec propriae adipisci. Ignota salutandi accusamus in sed, et per malis fuisset, qui id ludus appareat.'
      }
    }
  }
</script>

