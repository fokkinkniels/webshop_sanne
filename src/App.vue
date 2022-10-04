<template>
  <v-app>
    <Navbar />
    <br>
    <v-container fluid>
      <v-row>
        <v-col cols="12">
         
          <v-toolbar flat color="transparent" class="mt-5">
            <v-toolbar-title class="text-h6">Alle Producten</v-toolbar-title>
          </v-toolbar>
          <Product />    

        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
import Footer from "./components/Footer.vue";
import Product from "./components/Product.vue";

export default {
  name: "Home",
  data: () => ({
    toggle_exclusive: 1,
  }),
  components: {
    Navbar,
    Footer,
    Product,

  },
};
</script>
<style >
.marginLeft {
  margin-left: -90px;
}
.mtop {
  margin-top: 100px;
}
.mbottom {
  margin-bottom: 100px;
}
.v-card.borderme {
  border: 2px solid green !important;
}
.v-card.borderout {
  border: 1px solid #d5f0db !important;
}
.v-btn:not(.v-btn--round).v-size--default.add {
  min-width: 0px !important;
}
.theme--light.v-sheet--outlined.mobile {
  border: 2px solid black !important;
}
@media only screen and (max-width: 600px) {
  h2.title1 {
    font-size: 15px;
  }
  h2.title2 {
    font-size: 15px;
  }
  .top {
    margin-top: 20px;
  }
}
@media only screen and (min-width: 600px) {
  .top {
    margin-top: 70px;
  }
}
@media only screen and (min-width: 768px) {
  .top {
    margin-top: 120px;
  }
}
</style>
