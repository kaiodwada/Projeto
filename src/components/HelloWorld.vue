<template>
  <v-container pa-0 ma-0 fluid>
    <v-layout align-center justify-center text-center class="my-5">

      <v-row>
      <v-card min-width="auto" width="100%" max-width="auto" height="13rem" dark color="indigo"> <v-layout class="flex-wrap" justify-center="" align-center="" >
        <v-card-title> <h2 class="tituloh">Bem vindos a Diorama! </h2></v-card-title>
      
     <v-card-text> <p class="textop">Escola on-line que fornece os melhores cursos sobre design,programação e suas diversas variações, venha conhecer nossos cursos!</p>  </v-card-text>
        <v-btn min-height="100%" max-height="auto">Clique aqui para conhecer</v-btn>   
</v-layout>  
      
    </v-card>
</v-row>


    </v-layout>



  <v-row align="center" justify="center" class="spacer" >
    <v-carousel cycle height="20rem" interval="9000" hide-delimiters> 

    <v-carousel-item>  <v-img height="100%" min-height="100%" src="../assets/firstimg.png">
               <v-row align="center" justify="center"><v-card-title> Produto 1 </v-card-title> 
               <v-card-text class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea eum laudantium veniam quidem aperiam. Itaque iure molestias impedit voluptatum sit numquam, voluptatibus dicta nesciunt et id error illo corrupti consequuntur?</v-card-text>
                   </v-row> 

<v-card-title class="align-center justify-center fill-height flex-wrap"><v-btn>Clique aqui para conhecer o curso</v-btn></v-card-title>
                      </v-img>  
    </v-carousel-item>


<v-carousel-item>  <v-img height="100%" min-height="100%" src="../assets/firstimg.png">
               <v-row align="center" justify="center"><v-card-title> Produto 2 </v-card-title> 
               <v-card-text class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea eum laudantium veniam quidem aperiam. Itaque iure molestias impedit voluptatum sit numquam, voluptatibus dicta nesciunt et id error illo corrupti consequuntur?</v-card-text>
                   </v-row> 

<v-card-title class="align-center justify-center fill-height flex-wrap"><v-btn>Clique aqui para conhecer o curso</v-btn></v-card-title>
                      </v-img>  
    </v-carousel-item>


    <v-carousel-item>  <v-img height="100%" min-height="100%" src="../assets/firstimg.png">
               <v-row align="center" justify="center"><v-card-title> Produto 3 </v-card-title> 
               <v-card-text class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea eum laudantium veniam quidem aperiam. Itaque iure molestias impedit voluptatum sit numquam, voluptatibus dicta nesciunt et id error illo corrupti consequuntur?</v-card-text>
                   </v-row> 

<v-card-title class="align-center justify-center fill-height flex-wrap"><v-btn>Clique aqui para conhecer o curso</v-btn></v-card-title>
                      </v-img>  
    </v-carousel-item>


    <v-carousel-item>  <v-img height="100%" min-height="100%" src="../assets/firstimg.png">
               <v-row align="center" justify="center"><v-card-title> Produto 4 </v-card-title> 
               <v-card-text class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea eum laudantium veniam quidem aperiam. Itaque iure molestias impedit voluptatum sit numquam, voluptatibus dicta nesciunt et id error illo corrupti consequuntur?</v-card-text>
                   </v-row> 

<v-card-title class="align-center justify-center fill-height flex-wrap"><v-btn>Clique aqui para conhecer o curso</v-btn></v-card-title>
                      </v-img>  
    </v-carousel-item>
      

    </v-carousel>
    </v-row>


<v-row dense="" pa-0 ma-0 fill-height>  
    
  

     <v-col sm="12" md="6"><a href="#"><v-card><v-img src="../assets/css.jpg"></v-img>
     <v-card-title class="align-center justify-center fill-height">Coluna 1
     </v-card-title>      
    <v-card-text>Descrição breve do curso</v-card-text></v-card></a>

    <v-row dense="">
     <v-col sm="12" md="6"><a href="#"><v-card><v-img src="../assets/webcurso.jpg"></v-img>
     <v-card-title class="align-center justify-center fill-height">Item 1
     </v-card-title>      
    <v-card-text>Descrição breve do curso</v-card-text></v-card></a></v-col>

 <v-col sm="12" md="6"><a href="#"><v-card><v-img src="../assets/webcurso.jpg"></v-img>
     <v-card-title class="align-center justify-center fill-height">Item 2
     </v-card-title>      
    <v-card-text>Descrição breve do curso</v-card-text></v-card></a></v-col>
    </v-row>

    </v-col>

  <v-col sm="12" md="6"><a href="#"><v-card><v-img src="../assets/css.jpg"></v-img>
     <v-card-title class="align-center justify-center fill-height">Coluna 2
     </v-card-title>      
    <v-card-text>Descrição breve do curso</v-card-text></v-card></a>
    
    <v-row dense="">
     <v-col sm="12" md="6"><a href="#"><v-card><v-img src="../assets/csharp.jpg"></v-img>
     <v-card-title class="align-center justify-center fill-height">Item 1
     </v-card-title>      
    <v-card-text>Descrição breve do curso</v-card-text></v-card></a></v-col>

     <v-col sm="12" md="6"><a href="#"><v-card><v-img src="../assets/javascript.jpg"></v-img>
     <v-card-title class="align-center justify-center fill-height">Item 2
     </v-card-title>      
    <v-card-text>Descrição breve do curso</v-card-text></v-card></a></v-col>
    </v-row>

    </v-col>



</v-row>


  </v-container>
</template>

<script>


export default {

}
</script>


<style>

.textop{
  font-size: 1.3rem;
}
.tituloh {
  font-size: 2rem;
  margin-bottom: 1rem;
  margin-top: 1rem;
}


.spacer {
  margin-top: 0.5rem;
}

a{
  text-decoration: none;
}

  </style>