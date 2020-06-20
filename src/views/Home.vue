<template>
  <div class="flex flex-column">
    <v-btn @click="openProject">
      Testing
    </v-btn>
    <v-btn @click="openProject2">
      Testing2
    </v-btn>

    <div style="width: 20%">
      <v-img src="https://media.gettyimages.com/photos/big-lion-showing-who-is-the-king-picture-id97992631?s=612x612" height="200" width="400" contain>
      </v-img>
      <v-img src="@/assets/lion1.jpg" height="400" width="400" contain>
      </v-img>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',

  methods: {
    openProject() {
      console.log("I was clicked !!!");
    },
    openProject2() {
      console.log("I was clicked yo!!!");}

  }
}
</script>
