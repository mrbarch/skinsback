<template>
  <div>
    <Header />
    <Nuxt />
  </div>
</template>

<style>
  @font-face {
    font-family: "SF Pro Display";
    src: local("SF Pro Display"),
    url(/assets/fonts/sf/SFProDisplay-Black.ttf) format('truetype');
  }

  body{
    padding: 0;
    margin: 0;
    font-family: "SF Pro Display", sans-serif;
    font-weight: normal;
    box-sizing: border-box;
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

