<template>
  <div class="round-image"></div>
</template>

<script>
export default {};
</script>

<style>
.round-image {
  width: 250px;
  height: 250px;
  background-image: url("../assets/foto.png");
  background-size: cover;
  display: block;
  border-radius: 125px;
  -webkit-radius: 125px;
  -moz-radius: 125px;
  border-radius: 125px;
  -webkit-radius: 125px;
  -moz-radius: 125px;
  transform: translateY(-5%);
  animation: floater 3.5s infinite;
  transition: ease 0.5s;
}

@keyframes floater {
  0% {
    transform: translateY(-5%);
    transition: ease 0.5s;
  }
  50% {
    transform: translateY(5%);
    transition: ease 0.5s;
  }
}
</style>
