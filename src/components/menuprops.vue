<template>
  <v-row align="center">
    <v-col cols="12">
      <v-select
        :items="items"
        :menu-props="{ top: true, offsetY: true }"
        label="Sexo"
      ></v-select>
    </v-col>

      <v-col cols="4">
        <v-text-field
          label="Peso atual"
          value="50.00"
          type="number"
          suffix="peso"
        ></v-text-field>
      </v-col>

 <v-col cols="4">
    <v-text-field
      v-model="idade"
      type="number"
      :error-messages="idadeErrors"
      :counter="2"
      label="Digite sua idade"
      required
      @input="$v.idade.$touch()"
      @blur="$v.idade.$touch()"
    ></v-text-field>
</v-col>
  </v-row>


</template>

<script>
  export default {
    data: () => ({
      items: ['Homem', 'Mulher'],
    }),
  }
</script>