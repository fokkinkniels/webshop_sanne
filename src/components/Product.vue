<template>
  <v-row justify="center" class="space px-16">
    <v-col cols="12" xs="12" sm="6" md="4" v-for="(product, i) in products" :key="i" >
      <v-card class="mx-auto rounded-xl" max-width="300" color="" flat outlined>
        <div align="center" justify="center">
          <v-img
            max-height="300"
            max-width="300"
            :src="product.img"
            style="border-radius: 23px"
          ></v-img>
        </div>

        <v-card-title class="">{{ product.title }}</v-card-title>
        <v-card-title class="grey--text text-grey-darken-1 caption mt-n6">{{
          product.subtitle
        }}</v-card-title>
        <v-card-title class="mt-n4">{{ product.price }}</v-card-title>
        <v-card-actions class="mx-2 mt-n4">          
          <v-spacer></v-spacer>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  data: () => ({
      bpm: 1,
    products: [
      { img: "arm1.jpg", title: "Foto armbandje", subtitle: "", price: "€3" },
      { img: "arm2.jpg", title: "Kralen armbandje", subtitle: "met echte steentjes", price: "€2,95" },
      { img: "arm3.jpg", title: "Touw armbandjes", subtitle: "Met bedel met foto erin", price: "€3" },
      { img: "arm4.jpg", title: "Touw armbandjes", subtitle: "Met bedel met foto erin", price: "€3" },
      { img: "arm5.jpg", title: "Metalen armbandjes", subtitle: "met bedels naar keuze", price: "€5" },
      { img: "arm6.jpg", title: "Gevlochten armbandje", subtitle: "Met bedel met foto erin", price: "€5" },
      { img: "arm7.jpg", title: "Kralen armbandjes", subtitle: "Beschikbaar in alle kleuren", price: "€2" },
      { img: "arm8.jpg", title: "Bedel armbandje", subtitle: "Met fotos erin", price: "€3" },
      { img: "arm9.png", title: "Gouden kralen armbandje", subtitle: "Met hartjes bedel en foto erin", price: "€5" },
    ],
  }),
   methods: {
     
    },
};
</script>

<style>
</style>