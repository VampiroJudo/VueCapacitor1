<template>
<ion-app>
<ion-header>
  <ion-toolbar color="primary">
    <ion-title>
      Vue Capacitor
    </ion-title>
  </ion-toolbar>
</ion-header>

<ion-button @click="goToAbout" full>Go to About</ion-button>
<ion-content padding>
  The world is your oyster.
  <p>
    If you get lost, the <a href="http://ionicframework.com/docs">docs</a> will be your guide.
  </p>
</ion-content>
</ion-app>
</template>

<script>
export default {
  name: 'Home',
  methods: {
    goToAbout() {
      this.$router.push('about')
    },
  }
}
</script>
