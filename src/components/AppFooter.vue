<script></script>

<template>
  <footer>
    <div class="container">
      <div class="info">
        <h3>DC COMICS</h3>
        <p>Characters</p>
        <p>Comics</p>
        <p>Movies</p>
        <p>TV</p>
        <p>Games</p>
        <p>Videos</p>
        <p>News</p>
        <h3>DC COMICS</h3>
        <p>Shop DC</p>
        <p>Shop DC Collectibles</p>
      </div>

      <div class="info">
        <h3>DC</h3>
        <p>Terms</p>
        <p>Privacy policy (New)</p>
        <p>Ad Choices</p>
        <p>Advertising</p>
        <p>Jobs</p>
        <p>Subscriptions</p>
        <p>Talent Workshops</p>
        <p>CPCS Certificates</p>
        <p>Rating</p>
        <p>Shop Help</p>
        <p>Contact Us</p>
      </div>
      <div class="info">
        <h3>SITES</h3>
        <p>DC</p>
        <p>MAD Magazine</p>
        <p>DC Kids</p>
        <p>DC Universe</p>
        <p>DC Power Visa</p>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  color: white;
  padding: 3rem;
  height: 50vh;
}
.container {
  display: flex;
}
p {
  color: grey;
  margin: 0.5rem 0;
}
.info {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  margin-right: 3rem;
}
</style>
