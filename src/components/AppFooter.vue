<template>
<v-container fluid fill-height>
  <v-footer height="0rem"
  width="auto"
  absolute=""
  dark
    padless
  >
    
    <v-card width="100%" cols="auto"
      flat
      tile
      class="white--text text-center"
    >
  


        <v-row ><v-layout ma-5 pa-5 justify-center="">
          
         <v-btn icon class="espacamento">
          <v-icon large>mdi-facebook</v-icon>
        </v-btn>


          <v-btn icon class="espacamento">
          <v-icon large>mdi-twitter</v-icon>
        </v-btn>

          <v-btn icon class="espacamento">
          <v-icon large>mdi-gmail</v-icon>
        </v-btn>

          <v-btn icon class="espacamento">
          <v-icon large>mdi-instagram</v-icon>
        </v-btn>

        </v-layout>
  </v-row>

<p>
CNPJ: 32998352000174<br>
E-Mail: comunicacoes@dioramadigital.com<br>
CEP: 14050159<br>
Endereço: Travessa Algodão<br>
Número: 424<br>
Bairro: Vila Tibério<br>
Cidade: Ribeirão Preto<br>
Estado: SP<br>
Telefone: (16) 2836-9713<br>
Celular: (16) 99556-4409</p>


      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>Diorama Digital</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</v-container>
</template>

<script>
export default {

}
</script>

<style>
 .espacamento{
   margin-left: 1.5rem;
  margin-right: 1.5rem;
  margin-bottom: 1.5rem;
 }

</style>