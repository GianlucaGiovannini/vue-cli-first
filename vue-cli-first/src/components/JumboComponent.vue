<template>
  <div>
      <div class="jumbotron">
        <div class="jumbo_info">
          <div class="jumbo_title">
            Title Anime: 
            Jujutsu Kaisen
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'JumboComponent',
}
</script>

<style scoped>
img {
    width: 100%;
}
.jumbotron {
  height: 600px;
  background-image: url(https://www.themoviedb.org/t/p/original/8DLpbLeUylcUnE4nTlRC4b6jzNz.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  
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
