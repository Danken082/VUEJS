<template>
    <v-container>
      <v-row class="text-center">
        <v-col cols="12">
          <v-img
            :src="require('../assets/4G.png')"
            class="my-3"
            contain
            height="200"
          />
        </v-col>
        <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Welcome to the GroupHelloWorld
        </h1>
      </v-col>
        <v-col
          class="mb-5"
          cols="12"
        >
          <h2 class="headline font-weight-bold mb-5">
            Group
          </h2>
  
          <v-row justify="center">
            <a
              v-for="(vue, i) in Group"
              :key="i"
              :href="vue.href"
              class="subheading mx-3"
              target="_blank"
            >
              {{ vue.text }}
            </a>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </template>
<script>

export default {
  name: 'Home',

  data: () => ({
    Group: [
      {
        text: 'Our VUEJS',
        href: 'https://github.com/Danken082/VUEJS',
      },
      
    ]
}),
}
</script>

