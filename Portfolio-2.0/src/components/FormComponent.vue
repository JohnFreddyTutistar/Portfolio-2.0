<template>
    <div>
        <section class="vh-100">
            <div class="container h-100">
                <div class="row d-flex justify-content-center align-items-center h-100">
                <div class="col-lg-12 col-xl-11">
                    <div class="card text-black" style="border-radius: 25px;">
                    <div class="card-body p-md-5">
                        <div class="row justify-content-center">
                        <div class="col-md-10 col-lg-6 col-xl-5 order-2 order-lg-1">

                            <p class="text-center h1 fw-bold mb-5 mx-1 mx-md-4 mt-4">Get in touch</p>

                            <form class="mx-1 mx-md-4" >

                                <div class="d-flex flex-row align-items-center mb-4">
                                    <i class="fas fa-user fa-lg me-3 fa-fw"></i>
                                    <div class="form-outline flex-fill mb-0">
                                        <input type="text" id="form3Example1c" class="form-control" required/>
                                        <label class="form-label" for="form3Example1c">Your Name</label>
                                    </div>
                                </div>

                                <div class="d-flex flex-row align-items-center mb-4">
                                    <i class="fas fa-envelope fa-lg me-3 fa-fw"></i>
                                    <div class="form-outline flex-fill mb-0">
                                        <input type="email" id="form3Example3c" class="form-control" required/>
                                        <label class="form-label" for="form3Example3c">Your Email</label>
                                    </div>
                                </div>

                                <div class="d-flex flex-row align-items-center mb-4">
                                    <i class="fas fa-comment-dots fa-lg me-3 fa-fw"></i>
                                    <div class="form-outline flex-fill mb-0">
                                        <textarea name="" cols="30" rows="10" id="form3Example4c" class="form-control" required></textarea>
                                        <label class="form-label" for="form3Example4c">Message</label>
                                    </div>
                                </div>

                                <div class="d-flex justify-content-center mx-4 mb-3 mb-lg-4">
                                    <input type="submit" class="btn btn-primary btn-lg btn-block" value="Submit">
                                </div>

                            </form>

                        </div>
                        <div class="col-md-10 col-lg-6 col-xl-7 d-flex align-items-center order-1 order-lg-2">

                            <img src="../assets/white.png"
                            class="img-fluid" alt="Sample image">

                        </div>
                        </div>
                    </div>
                    </div>
                </div>
                </div>
            </div>
        </section>
        <footer>
      <div class="img-lap">
        <img src="../assets/laptop3.png" alt="" width="200">
      </div>
      <div class="text">
        Software Developer
      </div>
      <font-awesome-icon icon="fa-brands fa-facebook" />
      <span>Developed By <a href="#">John Tutistar</a> | <span class="far fa-copyright"></span> 2022 All rights recerved</span>
      <div>
        Made with <img src="../assets/vue.png" alt="" width="15">
      </div>
    </footer>
    </div>
</template>

<script>
export default {
    name: "FormComponent"
    
}
</script>

<style scoped>
    .card-body{
        -webkit-box-shadow: 0 10px 20px 0 rgba(0,0,0,0.3);
        box-shadow: 0 10px 20px 0 rgba(0,0,0,0.3);
      
    }

    /*footer */
    footer{
        background: radial-gradient(closest-side, #374b70, #293a5a, #161f30);;
        padding: 20px 23px;
        color: white;
        text-align: center;
        font-size: 20px;
    }
    footer span a{
        color: #5DADE2;
    }
    .text{
        margin-bottom: 40px;
    }
    .img-lap{
        margin-top: 40px;
    }
    html{
        scroll-behavior: smooth;
    }
</style>