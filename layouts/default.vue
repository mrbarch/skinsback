<template>
  <div>
    <Header />
    <Nuxt />
  </div>
</template>

<script>
import Questions from '/components/Questions'

export default {
  components: {
    Questions
  }
}
</script>

<style>
  @font-face {
    font-family: "SF Pro Display";
    src: local("SF Pro Display"),
    url(/assets/fonts/sf/SFProDisplay-Black.ttf) format('truetype');
  }

  body{
    padding: 0;
    margin: 0;
    font-family: SFProDisplay, sans-serif;
    font-weight: normal;
    box-sizing: border-box;
    overflow-x: hidden
  }
  * {
    list-style-type: none;
    color: white;
  }
  .container {
    width: 67vw;
    margin: 0 auto;
  }
</style>

