<template>
  <div>
    <h1>What The Fridge?!</h1>
    <p>Find the perfect recipe for what you have in your fridge</p>
  </div>
</template>

<script>
export default {
  name: "Jumbotron",
};
</script>

<style scoped>
div {
  width: 100%;
  background-image: linear-gradient(rgb(255, 94, 0), rgb(255, 174, 0));
  height: 50vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

h1,p {
  color: white;
  text-align: center;
}

h1{
    font-size: 100px;
}
</style>