<template>
  <div id="app">
    <div>
      <div class="father-container">
        <div class="container">
          <div class="header-section">
              <div class="section-one">
                <a href="/">
                  <img src="../src/assets/t.png" alt="" width="120" class="img-laptop">
                  <!-- <div class="developer">Web Developer</div> -->
                </a>
              </div>
          
              <div class="section-two">
                <button class="btn btn-light"><a href="#about">About me</a></button>
                <button class="btn-style"><router-link to="/form" class="btn btn-outline-primary">Get in touch</router-link></button>
              </div>
          </div>
        </div>
        
      </div>
    </div>
    <router-view/>
  </div> 
</template>

<script>

</script>

<style scoped>
  a{
        text-decoration: none;
        color: #222;
    }
    .header-section{
        display: flex;
        margin-top: 25px;
    }
    .developer{
        font-family: 'Kavoon', cursive;
    }
    .section-one{
        width: 70%;
    }
    .img-laptop{
        margin-left: 15px;
    }

    .section-two{
        margin: auto;
    }
    .btn{
        width: 120px;
    }
    .btn-style{
        border: none;
        background: none;
    }
</style>
