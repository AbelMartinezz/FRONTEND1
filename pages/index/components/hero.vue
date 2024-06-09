<template>
  <v-card
    class="mx-auto my-16" 
    max-width="425"
  >
    <v-list lines="two">
      <v-list-subheader>Mi Perfil</v-list-subheader>
  
      <template v-for="(person, index) in people" :key="index">
        <v-list-item
          :prepend-avatar="person.avatar"
          :title="person.title"
        >
          <template v-slot:subtitle>
            <span class="font-weight-bold">{{ person.name }}</span> &mdash; {{ person.message }}
          </template>
        </v-list-item>
  
        <v-divider inset v-if="index < people.length - 1"></v-divider> 
      </template>
    </v-list>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      people: [
        {
          avatar: "https://cdn.vuetifyjs.com/images/lists/1.jpg",
          title: "Name:",
          name: "Manuel",
          message: "I'll be in your neighborhood doing errands this weekend. Do you want to hang out?"
        }
      ]
    };
  }
};
</script>

<style>
</style>
