<template>
  <v-footer dark padless>
    <v-card flat tile class="black white--text py-12 px-5" width="100%">
      <v-row>
        <v-col cols="12" xs="12" sm="6" md="4" class="pa-16">
          <v-toolbar color="transparent" flat>
            <v-badge color="#D5F0DB" dot>
              <v-img src="1.png" contain width="30"></v-img>
            </v-badge>

            <v-toolbar-title class="ml-4">
              <span class="green--text">e</span><strong>Grocery</strong>
            </v-toolbar-title>
          </v-toolbar>
          <v-card-text class="pt-0">
            <v-btn
              v-for="icon in icons"
              :key="icon"
              class="mx-1 white--text"
              icon
              fab
              outlined
              small
            >
              <v-icon size="20px">
                {{ icon }}
              </v-icon>
            </v-btn>
          </v-card-text>
        </v-col>
      
        <v-col cols="12" xs="12" sm="6" md="4">
          <v-card-text class="white--text pt-0">
            <h3>Contact</h3>
          </v-card-text>
          <v-card-text class="grey--text"> Bani Banthara, Lucknow </v-card-text>
          <v-card-text class="grey--text mt-n4">
            Near G-rest Hotel, Bani - 226401
          </v-card-text>
          <v-card-text class="grey--text mt-n4"> devashishverma386@gmail.com </v-card-text>
          <v-card-text class="grey--text mt-n4"> -7607235537 </v-card-text>
        </v-col>
      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    icons: [
    //   <a href = " "><i class = "fab fa-apple"></i></a>,
      <a href = "devashishverma386@gmail.com"><i class = "fab fa-google-plus-g"></i></a>,
      <a href = "https://twitter.com/Dave10924648"><i class = "fab fa-twitter"></i></a>,
      <a href = "https://www.facebook.com/devill.rock.948"><i class = "fab fa-facebook-f"></i></a>
    ],
  }),
};
</script>

<style>
</style>