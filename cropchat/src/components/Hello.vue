<template>
  <div>
    <md-card class="my-card">
      <md-card-media>
        <img src="https://25.media.tumblr.com/tumblr_m40h4ksiUa1qbyxr0o1_400.gif" alt="Cat">
      </md-card-media>
    </md-card>
  </div>
</template>

<script>
import data from '../data'

export default {
  props: {
    pictures: {
      type: Object,
      default: data.pictures
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.my-card {
  margin: 15px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495E;
}
</style>
