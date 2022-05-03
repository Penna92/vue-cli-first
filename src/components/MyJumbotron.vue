<template>
    <div>
        <img id="jumbotron" src="../assets/jumbotron-image.jpg" alt="Jumbotron image">
    </div>
</template>

<script>
export default {
  name: 'MyJumbotron',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
    #jumbotron {
        width: 100%;
        height: 100vh;
        object-fit: cover;
        object-position: center;
    }
</style>