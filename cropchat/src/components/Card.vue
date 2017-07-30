<template>
  <md-card>
    <md-card-media>
      <img :src="this.imageUrl" :alt="this.imageAltText">
    </md-card-media>

    <md-card-header>
      <div class="md-title">{{this.imageTitle}}</div>
      <div class="md-subhead">{{this.imageSubtitle}}</div>
    </md-card-header>
  </md-card>
</template>

<script>
  export default {
    props: {
      imageUrl: {
        type: String,
        default: 'hello imageUrl'
      },
      imageAltText: {
        type: String,
        default: 'hello imageAltText'
      },
      imageTitle: {
        type: String,
        default: 'hello imageTitle'
      },
      imageSubtitle: {
        type: String,
        default: 'hello imageSubtitle'
      }
    }
  }
</script>

<style>

</style>

