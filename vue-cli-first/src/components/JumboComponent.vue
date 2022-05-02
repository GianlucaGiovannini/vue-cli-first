<template>
  <div>
      <div class="jumbotron">
        <div class="jumbo_info">
          <div class="jumbo_title">
            Title Anime: 
            Jujutsu Kaisen
          </div>
          <ThumbsCard/>
        </div>
      </div>
  </div>
</template>

<script>
import ThumbsCard from './ThumbsCard.vue'

export default {
  name: 'JumboComponent',
  components: {
    ThumbsCard,
  }
}
</script>

<style scoped>
img {
    width: 100%;
}
.jumbotron {
  height: 70vh;
  background-image: url(https://www.themoviedb.org/t/p/original/8DLpbLeUylcUnE4nTlRC4b6jzNz.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  position: relative;
  
 }
.jumbo_info {
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.247);
  color: rgb(255, 255, 255);
  position: relative;
}

.jumbo_title {
  font-size: 2.1rem;
  position: absolute;
  top: 10%;
  left: 5%
}

</style>
