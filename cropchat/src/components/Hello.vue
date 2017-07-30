<template>
  <div>
    <card
      class="my-card"
      v-for="(picture, index) in this.pictures"
      v-bind:key="picture.id"
      >
    >
    </card>
  </div>
</template>

<script>
import data from '../data'
import Card from './Card'

export default {
  components: {
    Card
  },
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
