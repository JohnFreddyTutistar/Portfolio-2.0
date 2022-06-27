<template>
  <div class="container">
    <div class="child-container text-center mt-5">
        <div class="title-section">
            <h1 class="title">my work</h1>
            <h5 class="mt-4">Here you will find a small sample of the projects I've done. Want to see more? <a href="https://wa.me/573105124961">Contact me</a></h5>
        </div>
        <div class="cards-container">
            <div class="card">
                <div class="img-card p-2">
                    <a href="https://tufisioterapeuta.netlify.app" target="_blank">
                        <img src="../assets/fisio.jpg" alt="" width="320" class="img-card">
                    </a>   
                </div>
                <p class="mt-4">web page designed for the profile of a professional physiotherapist</p>
                <p class="mt-2 p-1">made with HTML, CSS, Bootstrap, and JavaScript.</p>
                <a href="https://tufisioterapeuta.netlify.app" target="_blank">www.tufisioterapeuta.netlify.app</a>
            </div>
            <div class="card">
                <div class="img-card p-2">
                    <a href="https://tutistar.netlify.app" target="_blank">
                        <img src="../assets/tutis.jpg" alt="" width="320" class="img-card">
                    </a>
                </div>
                <p class="mt-4">It was my first portfolio applying my first knowledge in development</p>
                <p class="mt-2 p-1">made with HTML, CSS, Bootstrap, and JavaScript.</p>
                <a href="https://tutistar.netlify.app" target="_blank">www.tutistar.netlify.app</a>
            </div>
            <div class="card">
                <div class="img-card p-2">
                    <a href="https://tutistar.netlify.app" target="_blank">
                        <img src="../assets/tutis2.jpg" alt="" width="320" class="img-card">
                    </a>
                </div>
                <p class="mt-4">web page designed for the profile of a professional physiotherapist</p>
                <p class="mt-2 p-1">made with HTML, CSS, Bootstrap, and JavaScript.</p>
                <a href="#" target="_blank" class="mb-3">www.johntuti.netlify.app</a>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
name: "projectscomponents"
}
</script>

<style scoped>
.title-section{
    margin-bottom: 75px;
}

.img-card{
    border-radius: 5px;
}

.cards-container{
    display: flex;
}
.card{
    width: 350px;
    box-shadow: 1px 1px 12px #888888;
    margin: 10px;
}
.title{
    font-family: 'Concert One', cursive;
    font-size: 55px;
    color: #333;
}
</style>