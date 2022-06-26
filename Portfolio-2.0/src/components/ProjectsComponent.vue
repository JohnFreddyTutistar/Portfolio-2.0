<template>
  <div class="container">
    <div class="child-container text-center mt-5">
        <h1>my work</h1>
        <p class="mt-4">Here you will find a small sample of the projects I've done</p>
        <div class="cards-container">
            <div class="card">
                <div class="img-card p-2">
                    <img src="../assets/fisio.jpg" alt="" width="320">
                </div>
                <p class="mt-4">web page designed for the profile of a professional physiotherapist</p>
                <p class="mt-2 p-1">made with HTML, CSS, Bootstrap, and JavaScript.</p>
                <a href="#">www.tufisioterapeuta.netlify.app</a>
            </div>
            <div class="card">
                <div class="img-card p-2">
                    <img src="../assets/tutis.jpg" alt="" width="320">
                </div>
                <p class="mt-4">It was my first portfolio applying my first knowledge in development</p>
                <p class="mt-2 p-1">made with HTML, CSS, Bootstrap, and JavaScript.</p>
                <a href="#">www.tutistar.netlify.app</a>
            </div>
            <div class="card">
                <div class="img-card p-2">
                    <img src="../assets/fisio.jpg" alt="" width="320">
                </div>
                <p class="mt-4">web page designed for the profile of a professional physiotherapist</p>
                <p class="mt-2 p-1">made with HTML, CSS, Bootstrap, and JavaScript.</p>
                <a href="#" class="mb-3">www.tufisioterapeuta.netlify.app</a>
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
.cards-container{
    display: flex;
}
.card{
    width: 350px;
    box-shadow: 2px 2px 18px #888888;
    margin: 10px;
}
</style>