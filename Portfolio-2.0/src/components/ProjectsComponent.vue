<template>
  <div class="container mb-5">
    <div class="child-container text-center mt-5">
      <div class="title-section">
        <h1 class="title">my projects</h1>
        <h5 class="mt-4">
          Here you will find a small sample of the projects I've done. Want to
          see more? <a href="https://wa.me/573105124961" target="_blank">Contact me</a>
        </h5>
      </div>
      <div class="cards-container">
        <div class="card">
          <div class="img-card p-2">
            <a href="https://tufisioterapeuta.netlify.app" target="_blank">
              <img
                src="../assets/fisio.jpg"
                alt=""
                width="320"
                class="img-card2"
              />
            </a>
          </div>
          <p class="mt-4">
            web page designed for the profile of a professional physiotherapist Spc. SST
          </p>
          <p class="mt-2 p-1">
            made with HTML, CSS, Bootstrap, and JavaScript.
          </p>
          <a href="https://tufisioterapeuta.netlify.app" target="_blank"
            ><b>www.tufisioterapeuta.netlify.app</b></a
          >
        </div>
        <div class="card">
          <div class="img-card p-2">
            <a href="https://tutistar.netlify.app" target="_blank">
              <img
                src="../assets/tutis.jpg"
                alt=""
                width="320"
                class="img-card2"
              />
            </a>
          </div>
          <p class="mt-4">
            It was my first portfolio applying my first knowledge in development
          </p>
          <p class="mt-2 p-1">
            made with HTML, CSS, Bootstrap, and JavaScript.
          </p>
          <a href="https://tutistar.netlify.app" target="_blank"
            ><b>www.tutistar.netlify.app</b></a
          >
        </div>
        <div class="card">
          <div class="img-card p-2">
            <a href="https://tutistar.netlify.app" target="_blank">
              <img
                src="../assets/tutis2.jpg"
                alt=""
                width="320"
                class="img-card2"
              />
            </a>
          </div>
          <p class="mt-4">
            This is my official portfolio where you will find more information about me and some of my projects
          </p>
          <p class="mt-2 p-1">
            made with VueJs, HTML, CSS, Bootstrap, and JavaScript.
          </p>
          <a href="#" target="_blank" class="mb-3"
            ><b>www.johntuti.netlify.app</b></a
          >
        </div>
      </div>
      <div class="cards-container">
        <div class="card">
          <div class="img-card p-2">
            <a href="https://my-tasks-jtutis.netlify.app" target="_blank">
              <img
                src="../assets/todolist.jpg"
                alt=""
                width="320"
                class="img-card2"
              />
            </a>
          </div>
          <p class="mt-4">
            This is a dynamic website where you can post your tasks, mark them as done and delete them
          </p>
          <p class="mt-2 p-1">
            made with HTML, CSS, Bootstrap, and JavaScript.
          </p>
          <a href="https://my-tasks-jtutis.netlify.app" target="_blank"
            ><b>www.my-tasks-jtutis.netlify.app</b></a
          >
        </div>

        <div class="card">
          <div class="img-card p-2">
            <a href="https://github.com/JohnFreddyTutistar/colorPicker-js" target="_blank">
              <img
                src="../assets/colorpicker.jpg"
                alt=""
                width="320"
                class="img-card2"
              />
            </a>
          </div>
          <p class="mt-4">
            Website to choose colors and copy it in hexadecimal in addition to choosing two view styles: dark and light
          </p>
          <p class="mt-2 p-1">
            made with HTML, CSS, Bootstrap, and JavaScript.
          </p>
          <a href="https://github.com/JohnFreddyTutistar/colorPicker-js" target="_blank"
            ><b>Code on GitHub</b></a
          >
        </div>
        <div class="card">
          <div class="img-card p-2">
            <a href="https://github.com/JohnFreddyTutistar/Exercise-website-js" target="_blank">
              <img
                src="../assets/encuesta.jpg"
                alt=""
                width="320"
                class="img-card2"
              />
            </a>
          </div>
          <p class="mt-4">
            Web page where you can choose your favorite anime and look at the statistics
          </p>
          <p class="mt-2 p-1">
            made with HTML, CSS, Bootstrap, JavaScript Jquery.
          </p>
          <a href="https://github.com/JohnFreddyTutistar/Exercise-website-js" target="_blank"
            ><b>Code on GitHub</b></a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "projectscomponents",
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Patrick+Hand&display=swap');
@import url("https://fonts.googleapis.com/css2?family=Arimo:ital@1&family=Concert+One&family=Kavoon&family=Koulen&family=Raleway:wght@100&display=swap");
.title {
  font-family: "Concert One", cursive;
  font-size: 55px;
  color: #3a4f75;
}
h5{
    font-family: 'Patrick Hand', cursive;
    font-size: 25px;
}
.title-section {
  margin-bottom: 75px;
}

.card img {
  width: 100%;
  height: 100%;
}
.img-card {
  overflow: hidden;
}
.img-card2 {
  transition: 1.4s;
}
.img-card2:hover {
  transform: scale(1.2);
}

/* .img-card{
    border-radius: 5px;
    transition: 2s;
}
.img-card:hover{
    transform: scale(1.05);
} */

.cards-container {
  display: flex;
}
.card {
  width: 350px;
  box-shadow: 1px 1px 12px #ddd8d8;
  margin: 10px;
}

</style>