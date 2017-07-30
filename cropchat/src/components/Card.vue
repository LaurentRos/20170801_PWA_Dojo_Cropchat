<template>
  <md-card>
    <md-card-media>
      <img src="assets/card-image-1.jpg" alt="People">
    </md-card-media>

    <md-card-header>
      <div class="md-title">Title goes here</div>
      <div class="md-subhead">Subtitle here</div>
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

