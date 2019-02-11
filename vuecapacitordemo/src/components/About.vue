<template>
<ion-app>
<ion-header>
  <ion-toolbar color="primary">
    <ion-title>
      Vur Capacitor | About
    </ion-title>
  </ion-toolbar>
</ion-header>

<ion-button @click="goBackHome()" full>Go back!</ion-button>
<ion-content padding>
This is the about page.
</ion-content>
</ion-app>
</template>

<script>
export default {
  name: 'About',
  methods: {
    goBAckHome() {
      this.$router.push('/')
    },
  } 
}

</script>
