<template>
  <v-layout justify-center align-center>
    <v-flex xl4 lg5 md6 sm8 xs4>
      <v-card class="elevation-15">
        <v-toolbar color="primary" dark card>
          <v-toolbar-title>Ingresa tus credenciales</v-toolbar-title>
        </v-toolbar>
        <v-card-text>
          <v-text-field label="Email"></v-text-field>
          <v-text-field label="Password" type="password"></v-text-field>
        </v-card-text>
        <v-card-text>
          <v-layout justify-end>
            <v-btn @click="vista++" color="secondary">Siguiente</v-btn>
          </v-layout>
        </v-card-text>
      </v-card>
    </v-flex>
  </v-layout>
</template>