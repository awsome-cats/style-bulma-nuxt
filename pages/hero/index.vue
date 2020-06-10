<template>
  <section class="hero is-fullheight">
    <div class="hero-head">
      <div class="columns is-mobile is-marginless heading has-has-text-weight-bold">
        <div class="column left">
          <figure class="navbar-item image is-200x200">
            <img src="https://placehold.it/200×200" alt="">
          </figure>
        </div>
        <div class="column center desktop">
          <p class="navbar-item has-text-black">
            MODEL S
          </p>
          <p class="navbar-item has-text-black">
            MODEL X
          </p>
          <p class="navbar-item has-text-black">
            MODEL 3
          </p>
          <p class="navbar-item has-text-black">
            MODEL 4
          </p>
          <p class="navbar-item has-text-black">
            MODEL XR
          </p>
        </div>
        <div class="column right">
          <p class="navbar-item desktop has-text-black">
            SHOP
          </p>
          <p class="navbar-item desktop has-text-black">
            SIGN IN
          </p>
          <p class="navbar-item">
            HAMBURGER
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
* {
  font-size:16px;
}
.hero {
  background: black url(../../static/image/sample-1.jpg) center / cover;
}
.center, .center-column, .top, .right, .bottom, .left {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.center-column {
  flex-direction: column;
}
.top {
  align-items: flex-start;
}
.right { justify-content: flex-end;}
.bottom { align-items: flex-end;}
.left { justify-content: flex-start;}
.single-spaced, .single-spaced * {
  line-height: 1;
}
@media (max-width: 1024px) {
  .desktop {
    display: none;
  }
}
@media (max-width: 1024px) {
  .hero {
  background: url(../../static/image/sample-1.jpg) center / cover;
}
}
@media (max-width: 768px) {
  .hero {
  background: url(../../static/image/sample-1.jpg) center / cover;
}
 }
</style>
