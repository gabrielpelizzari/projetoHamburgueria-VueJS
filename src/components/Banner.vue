<template>
  <div id="main-banner">
    <h1>Faça seu hambúrguer</h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
}
</script>

<style scoped>

#main-banner {
  background-image: url('/public/img/burguer.jpg');
  background-position: 0 -175px;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  
}

#main-banner h1 {
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: rgba(1, 2, 5, 0.2);
    padding: 20px 40px;

}
</style>