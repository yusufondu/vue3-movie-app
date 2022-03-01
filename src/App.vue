<template>
<header>
  <router-link to="/">
    <h1>IMDB</h1>
  </router-link>
</header>
<main>
  <router-view/>
</main>
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Roboto-Regular;

  &::selection {
    background: transparentize(#42b883, 0.5);
  }
}

body {
  background-color: #141414;
}

a {
  text-decoration: none;
}

header {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px 16px;
  background-color: #141414;
  box-shadow: 0px 0px 6px rgba(0, 0, 0, 0.1);

  h1 {
    color: #fff;
    font-size: 28px;
    padding: 10px 0px 10px 0px;
  }
}
</style>
