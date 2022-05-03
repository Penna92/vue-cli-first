<template>
    <div id="jumbotron">
        <h1>La mia prima app con Vue CLI!</h1>
        <img id="jumbotron" src="../assets/jumbotron-image.jpg" alt="Jumbotron image">
    </div>
</template>

<script>
export default {
  name: 'MyTitle',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
    h1{
        color: green;
    }
    #jumbotron {
        width: 100%;
        height: 100vh;
        object-fit: cover;
        object-position: center;
    }
</style>
