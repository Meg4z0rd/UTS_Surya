<template>
        <v-navigation-drawer
          expand-on-hover
          rail
        >
          <v-list>
            <v-list-item
              prepend-avatar="https://asset-a.grid.id/crop/0x0:0x0/700x465/photo/2021/06/09/soeharto-mudajpg-20210609093204.jpg"
              subtitle="surya.rajab@widyatama.ac.id"
              title="Surya Rajab Sanusi"
            ></v-list-item>
          </v-list>
  
          <v-divider></v-divider>
  
          <v-list density="compact" nav>
            <v-list-item prepend-icon="mdi-folder" title="Home" :to="'/home'"></v-list-item>
            <v-list-item prepend-icon="mdi-account-multiple" title="Dosen" :to="'/dosen-entry'"></v-list-item>
            <v-list-item prepend-icon="mdi-star" title="Mahasiswa" :to="'/mahasiswa-entry'"></v-list-item>
            <v-list-item prepend-icon="mdi-star" title="Ruangan" :to="'/ruangan-entry'"></v-list-item>
          </v-list>
        </v-navigation-drawer>
  
        <v-main style="height: 250px"></v-main>
  </template>