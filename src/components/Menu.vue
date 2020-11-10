<template>
    <v-app>
        <v-content >
             <v-parallax dark src="https://cdn.shopify.com/s/files/1/1432/5782/t/10/assets/hero_slide_1.jpg?v=4170718084814245097">
               <v-row>
                 <v-col>
                   <div class="d-flex flex-row mt-10">
                   <v-btn style="padding:0 !important" text> <v-img width="120px" height="80px" src="https://cdn.shopify.com/s/files/1/1432/5782/t/10/assets/logo.png?v=7023560698388380414"></v-img></v-btn>
                   <label style="width:500px"></label>
                    <v-combobox class="styleDiv" width="50px" value="ÜST"></v-combobox>
                    <v-combobox class="styleDiv" value="ALT"></v-combobox>  
                    <v-combobox class="styleDiv" :items="items" value="DİĞER"></v-combobox>           
                    <v-btn style="padding:0 !important" text ><v-icon>mdi-account</v-icon></v-btn>
                    <v-btn style="padding:0 !important" text ><v-icon>mdi-shopping</v-icon></v-btn>
                    <v-btn style="padding:0 !important" text ><v-icon>mdi-shopping</v-icon></v-btn>
                    <label style="width:50px"></label>
                  </div>
                 </v-col>
               </v-row>
               <v-row align="top" justify="center" >
                 <v-col class="text-center" cols="12" >
                   <h6 class="font-weight-medium mb-2 black--text"> YENİ SEZONU KEŞFEDİN</h6>
                   <h1 class="display-1  mb-4">SONBAHAR/KIŞ'20</h1>
                   <v-btn class="font-weight-light font-size:15 rounded-0" >ALIŞVERİŞE BAŞLA → </v-btn>
                 </v-col>
               </v-row>
             </v-parallax>
        </v-content>
    </v-app>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          'Cüzdan',
          'Gözlük',
          'Anahtarlık',          
          'Defter',
        ],
      }
    },
  }
</script>

<style>
.styleDiv{
  height: 50px;
  width: 100px;
  padding:0 !important;
}
</style>
