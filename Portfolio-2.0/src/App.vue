<template>
  <div id="app">
    <div>
      <div class="father-container">
        <div class="container">
          <div class="header-section">
            <div class="section-one">
              <router-link to="/">
                <img
                  src="../src/assets/logot.png"
                  alt=""
                  width="80"
                  class="img-laptop"
                />
                <p>Web Developer</p>
              </router-link>
            </div>

            <div class="section-two">
              <button class="btn btn-light">
                <a href="#about">About me</a>
              </button>
              <button class="btn-style">
                <router-link to="/form" class="btn btn-outline-primary"
                  >Get in touch</router-link
                >
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <router-view />
  </div>
</template>

<script>
</script>

<style scoped>
img{
  transform-style: preserve-3d;
  transition: transform 0.8s;
}
img:hover{
  transform: rotateY(180deg);
}
a {
  text-decoration: none;
  color: #222;
}
.header-section {
  display: flex;
  margin-top: 25px;
}
.developer {
  font-family: "Kavoon", cursive;
}
.section-one {
  width: 70%;
}
.img-laptop {
  margin-left: 15px;
}

.section-two {
  margin: auto;
}
.btn {
  width: 120px;
}
.btn-style {
  border: none;
  background: none;
}
</style>
