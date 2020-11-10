<template>
   <v-app>
       <v-content>
            <v-container class="fill-height about" fluid>
                <v-row class="d-flex align-content-start flex-wrap" style="height:700px">
                   <v-col cols="12" align="center">
                       <div >
                          <h1 class="font-weight-light" >BERE</h1>
                          <p>_____</p>
                       </div>
                       <div>
                          <v-card class="d-flex flex-wrap" width="900px">
                            <v-card height="450px" width="300px" v-for="n in 9" :key="n" class="ml-100 pa-4"  outlined >
                               <v-img src="https://cdn.shopify.com/s/files/1/1432/5782/products/BeyKarakoy2260copy_1024x1024.jpg?v=1602689425"></v-img>
                               <v-btn class="font-weight-light" text text-small>BEY YÜN BERE AÇIK YEŞİL - 150TL</v-btn>
                               <h6 class="font-weight-light" text-small>BEY</h6>
                            </v-card>
                          </v-card>
                       </div>
                   </v-col>
                </v-row>               
            </v-container>
       </v-content>
   </v-app>
</template>


<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://cdn.shopify.com/s/files/1/1432/5782/products/BeyKarakoy2268copy_1024x1024.jpg?v=1602688845',
          },
          {
            src: 'https://cdn.shopify.com/s/files/1/1432/5782/products/BeyKarakoy2260copy_1024x1024.jpg?v=1602689425',
          },
          {
            src: 'https://cdn.shopify.com/s/files/1/1432/5782/products/BeyKarakoy2247copy_1024x1024.jpg?v=1602752199',
          },
          {
            src: 'https://cdn.shopify.com/s/files/1/1432/5782/products/BeyKarakoy2275copy_1024x1024.jpg?v=1602751858',
          },
         
        ],
      }
    },
  }
</script>