<template>
    <v-app>
        <v-content >
             <v-carousel :show-arrows="false">
               <v-carousel-item v-for="(item,i) in items" :key="i" :src="item.src">
 <v-row align="center" justify="center" >
      <v-col class="text-center" cols="12" >
        <div style="height:180px"></div>
        <h6 class="font-weight-medium mb-2 black--text"> YENİ SEZONU KEŞFEDİN</h6>
        <h1 class="display-1  mb-4">SONBAHAR/KIŞ'20</h1>
        <v-btn class="font-weight-light font-size:15 rounded-0 black--text" color="white" >ALIŞVERİŞE BAŞLA → </v-btn>
      </v-col>
    </v-row>
               </v-carousel-item>
   
             </v-carousel>
        </v-content>
    </v-app>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://cdn.shopify.com/s/files/1/1432/5782/t/10/assets/hero_slide_1.jpg?v=4170718084814245097',
          },
          {
            src: 'https://cdn.shopify.com/s/files/1/1432/5782/t/10/assets/hero_slide_2.jpg?v=14740158159152495999',
          },
         
        ],
      }
    },
  }
</script>