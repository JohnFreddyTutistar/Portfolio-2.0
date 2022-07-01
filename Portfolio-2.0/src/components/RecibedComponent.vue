<template>
  <div class="container">
    <div class="child text-center fade-in">
        <img src="../assets/keep.png" alt="" width="350">
        <h1>Message recived. Thanks!</h1>
        <h3>I'll be  in touch with you shorty</h3>
        <router-link to="/" class="btn btn-outline-primary btn-lg mt-4">Back to home</router-link>
    </div>
  </div>
</template>

<script>
export default {
    name: "recibedcomponent"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Prompt&display=swap');

.container{
    display: flex;
}
.child{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-family: 'Prompt', sans-serif;
    animation-name: aparecer;
    animation-duration: 2s;
}
@keyframes aparecer {
    0% {opacity: 0%;}
    100% {opacity: 100%;}
}

</style>