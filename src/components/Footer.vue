<template>
  <div class="bg-couple">
    <div class="container ">
      <div class="row">
        
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Parisienne&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");
h1 {
  font-family: "Parisienne", cursive;
  font-size: 4em;
}

h5,
a {
  font-family: "Montserrat", sans-serif;
  font-size: 1em;
}

.image-adjust img {
  height: 6rem;
}

ul li {
  list-style: none;
  text-transform: uppercase;
}

.margin-custom {
  margin-top: 50vh;
}

.bg-couple {
  width: 100%;
  height: 100vh;
  background: url("../assets/Group 9.png") no-repeat center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

@media screen and (min-device-width: 320px) and (max-device-width: 480px) {
  .bg-couple {
    width: 100%;
    height: auto;
    background: url("../assets/background-wedding.png") no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }
}
</style>