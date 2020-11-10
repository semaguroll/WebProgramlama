<template>
    <v-app>
        <v-content>
            <v-container>
                <v-row align="center" justify="center">
                   <v-card class="pa-5" style="background-color: darkgray" height="550px" width="300px">
                      <div class="d-flex flex-row mb-1">
                          <h3 class="font-weight-light white--text">Alışveriş sepetiniz</h3>
                          <label style="width:90px"></label>
                          <v-icon color="white" >mdi-close</v-icon>
                      </div>
                      <p class="white--text">___________________________________</p>
                      <div class="d-flex flex-row">
                          <v-img height="120px" width="40px" src="https://cdn.shopify.com/s/files/1/1432/5782/products/BeyKarakoy0042copy_1024x1024.jpg?v=1602665691"></v-img>
                          <label style="width:5px"></label>
                          <div  class="d-flex flex-column mt-5">
                              <h6 class="font-weight-light white--text">Açık Yeşil Sweatshirt</h6>
                              <h6 class="font-weight-light white--text">S</h6>
                          </div>
                          <h5 class="font-weight-light white--text mt-15">490.00TL</h5>
                      </div>
                      <div style="height:200px"></div>
                      <div class="d-flex flex-column">
                            <p class="align-end white--text">___________________________________</p>
                            <div class="d-flex flex-row mb-5">
                                <h5 class="font-weight-light white--text">TOPLAM</h5>
                                <label style="width:150px"></label>
                                <h5 class="font-weight-light white--text">490.00TL</h5>
                            </div>
                            <v-btn class="font-weight-light  rounded-0 white--text" style="background-color:brown; font-size:10px">SİPARİŞİ TAMAMLA → </v-btn>
                      </div>
                     
                   </v-card>
                </v-row>
            </v-container>
        </v-content>
    </v-app>
</template>