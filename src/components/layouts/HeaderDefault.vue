<template>
  <header>
    <img src="../../assets/ipb-logo.png">
    <nav>
      <a href="#">QUEM SOMOS</a>
      <a href="#">O QUE CREMOS</a>
      <a href="#">LOCALIZAÇÃO</a>
      <a href="#">LITURGIA</a>
    </nav>
  </header>
</template>

<style scoped>

header{
  margin: 2rem;
  padding: 0 5rem;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

header img {
  height: 5rem;
  width: 10rem;
}

header nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

header nav a {
  margin: 1rem 1rem;
  text-decoration: none;
  color: black;
}

</style>