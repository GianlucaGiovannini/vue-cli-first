<template>
<div class="container">
    <div class="card">
        <img src="https://www.themoviedb.org/t/p/original/lthkKBLe1rX6iThgVFg22O02sJw.jpg" alt="...">
    </div>
    <div class="card">
        <img src="https://www.themoviedb.org/t/p/original/fgPa2oJD8lbLaTanzlGDd32tqDE.jpg" alt="...">
    </div>
    <div class="card">
        <img src="https://www.themoviedb.org/t/p/original/lthkKBLe1rX6iThgVFg22O02sJw.jpg" alt="...">
    </div>
    <div class="card">
        <img src="https://www.themoviedb.org/t/p/original/lthkKBLe1rX6iThgVFg22O02sJw.jpg" alt="...">
    </div>
    <div class="card">
        <img src="https://www.themoviedb.org/t/p/original/k2fix3m8ojoillUdoNJp90q1uG3.jpg" alt="...">
    </div>
    <div class="card">
        <img src="https://www.themoviedb.org/t/p/original/k2fix3m8ojoillUdoNJp90q1uG3.jpg" alt="...">
    </div>
</div>
</template>

<script>
export default {
  name: 'ContainerThumb',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped >
.container {
  width: 95%;
  display: flex;
  justify-content: space-around;
  gap: 1rem;
  position: absolute;
  bottom: 1rem;
  left: 50%;
  transform: translate(-50%, -50%);
  
}

.card  {
  width: calc(100% / 6 - 16px);
  height: 50px;
  box-shadow: 0 0 10px white;
}

.card img {
    width: 100%;
    height: auto;
    object-fit: cover;
}
</style>
