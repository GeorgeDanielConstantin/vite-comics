<script></script>

<template>
  <section>
    <header class="container">
      <img src="../assets/img/dc-logo.png" alt="Logo" />
      <ul class="d-flex">
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </header>
  </section>
</template>

<style lang="scss" scoped>
section {
  background-color: white;
  padding: 2rem;
}
header {
  display: flex;
  justify-content: space-between;
}

ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
  li {
    a {
      color: black;
      text-decoration: none;
      padding: 2rem 1rem;
      &:hover {
        color: blue;
        border-bottom: 4px solid blue;
      }
    }
  }
}
</style>
