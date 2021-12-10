<template>
  <v-card
    class="mx-auto"
    max-width="324"
  >
    <v-img
      height="100%"
      src="https://cdn.vuetifyjs.com/images/cards/server-room.jpg"
    >
      <v-row
        align="end"
        class="fill-height"
      >
        <v-col
          align-self="start"
          class="pa-0"
          cols="5"
        >
          <v-avatar
            class="profile"
            size="184"
            tile
          >
            <v-img src="../assets/logonutri.png"></v-img>
          </v-avatar>
        </v-col>
        <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
            dark
          >
            <v-list-item-content>
              <v-list-item-title class="text-h6">
                BOT
              </v-list-item-title>
              <v-list-item-subtitle>Nutricionista Online</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>
      </v-row>
    </v-img>
  </v-card>
</template>