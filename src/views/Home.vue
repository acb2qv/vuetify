<template>
  <div class="home">
    <h1>Homepage</h1>
    <v-btn class="pink white--text">Click me</v-btn>
    <v-btn dark depressed color="pink">Click me</v-btn>
    <v-btn flat color="pink">Click me</v-btn>

    <v-btn depressed class="pink white--text">
      <v-icon>email</v-icon>
    </v-btn>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
}
</script>
