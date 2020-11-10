<template>
  <v-app>
    <v-content>
      <v-row align="center" justify="center">
        <v-col cols="12" align="center" justify="center">
          <v-card class="pa-5" height="500px" width="400px">
            <div class="text-center">
              <h2 class="font-weight-light mt-10">Giriş</h2>
              <p class="mb-10">______</p>
              <v-text-field  v-model="eposta" :rules="epostaRules" background-color="white" outlined dense label="E-Posta" required />
              <v-text-field v-model="sifre" type="password" :rules="sifreRules" background-color="white" outlined dense label="Şifre" required/> 
              <v-btn style="fontSize:14px; background-color:black; color:white; round-0; width:350px">GİRİŞ</v-btn>
              <div class="d-flex flex-column mt-7">
                <v-btn style="text-transform:none; text-width-light" text small>Yeni Üyelik</v-btn> 
                <v-btn style="text-transform:none; text-width-light" text small>Ana Sayfa</v-btn> 
                <v-btn style="text-transform:none; text-width-light" text small>Şifreyi Unuttum</v-btn>
              </div>
             </div>
          </v-card> 
        </v-col>   
      </v-row>
    </v-content>
  </v-app>
</template>
<script>
  export default {
    data: () => ({
      valid: true,      
     eposta: '',
      epostaRules:[
        v => !!v || 'E-posta giriniz.',
        v => /.+@.+\..+/.test(v) || 'E-posta geçersiz.',
      ],
       sifre: '',
      sifreRules: [
        v => !!v || 'Şifre giriniz.',
        v => (v && v.length <= 8) || 'Şifre 8 karakterden fazla olmalıdır.',
      ]     
    }),
      }
</script>