<template>
  <v-footer dark padless>
    <v-card flat tile class="black white--text py-12 px-5" width="100%">
      <v-row>
        <v-col cols="12" xs="12" sm="6" md="4" class="pa-16">
          <v-toolbar color="transparent" flat>
            <v-badge color="#transparent" dot>
              <v-img src="1.png" contain width="30"></v-img>
            </v-badge>

            <v-toolbar-title class="ml-4">
              <span class="pink--text">Sanne's</span><strong>Kralen</strong>
            </v-toolbar-title>
          </v-toolbar>

        </v-col>

        <v-col cols="12" xs="12" sm="6" md="2">
          <v-card-text class="white--text pt-0">
            <h3>Hoe werkt het?</h3>
          </v-card-text>
          <v-card-text class="grey--text"> Stuur mij een berichtje via Instagram of TikTok met wat je wilt bestellen. Dan spreken we daar af hoe en waar je bestelling bezorg moet worden </v-card-text>
        </v-col>

        <v-col cols="12" xs="12" sm="6" md="4">
          <v-card-text class="white--text pt-0">
            <h3>Contact</h3>
          </v-card-text>
          <v-card-text class="mt-n4"> <a class="grey--text" style="text-decoration: none;" href="https://www.stackoverflow.com" target="_blank">TikTok</a> </v-card-text>
          <v-card-text class=" mt-n4"><a class="grey--text" style="text-decoration: none;" href="https://www.instagram.com/kraal.en.zo/" target="_blank">Instagram</a></v-card-text>
        </v-col>

      </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    
  }),
};
</script>

<style>
</style>