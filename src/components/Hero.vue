<template>
  <div class="jumbotron">
    <img src="../assets/1.jpg" alt="">
    <h2>{{msg}}</h2>
  </div>
</template>

<script>
export default {
  name: "Hero",
  props: {
    msg: String,
  },
};
</script>

<style scoped lang="scss">
.jumbotron {
    width: 80%;
    height: 500px;
    overflow: hidden;
    margin: 0 auto;
    position: relative;
}
img {
    object-fit: cover;
    width: 100%;
    height: 100%;
}

h2 {
    position: absolute;
    bottom: 0;
    right: 25px;
    color: white;
}

</style>