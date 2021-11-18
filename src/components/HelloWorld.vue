<template>
  <div class="hello">
        <!-- Responsive navbar-->
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
                <a class="navbar-brand" href="#!">Portfolio</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                        <li class="nav-item"><a class="nav-link active" aria-current="page" href="#!">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#!">About</a></li>
                        <li class="nav-item"><a class="nav-link" href="#!">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>
        <!-- Header - set the background image for the header in the line below-->
        <header class="py-5 bg-image-full" style="background-image: url('https://source.unsplash.com/wfh8dDlNFOk/1600x900')">
            <div class="text-center my-5">
                <img class="img-fluid rounded-circle mb-4" src=foto.jpeg alt="https://dummyimage.com/150x150/6c757d/dee2e6.jpg" width="150px" height="150px"/>
                <h1 class="text-white fs-3 fw-bolder">San Gabriel Vanness Kenrick Erwi</h1>
                <p class="text-white-50 mb-0">2024250019</p>
            </div>
        </header>
        <!-- Content section-->
        <section class="py-5">
            <div class="container my-5">
                <div class="row justify-content-center">
                    <div class="col-lg-6">
                        <h2>Biography</h2>
                        <p class="lead">I was born in 1st August 2002 at Palembang, Indonesia. I am the third child in my family. Now i am studying in MDP University.</p>
                        <p class="mb-0">“Don't stop when you are tired. Stop when you are done!”</p>
                    </div>
                </div>
            </div>
        </section>
        <!-- Image element - set the background image for the header in the line below-->
        <div class="py-5 bg-image-full" style="background-image: url('https://source.unsplash.com/4ulffa6qoKA/1200x800')">
            <!-- Put anything you want here! The spacer below with inline CSS is just for demo purposes!-->
            <div style="height: 20rem"></div>
        </div>
        <!-- Content section-->
        <section class="py-5">
            <div class="container my-5">
                <div class="row justify-content-center">
                    <div class="col-lg-6">
                        <h2>School Background</h2>
                        <p class="lead">In 2008 - 2014, Xaverius 4 junior school <br>In 2014 - 2017, Palembang Harapan Junior High School <br>In 2017 - 2020, Xaverius 1 Senior High School <br>In 2020 - Now, MDP University(Informatics)</p>
                        <p class="mb-0">"Everybody is a genius. But if you judge a fish by its ability to climb a tree it will live its whole life believing that it is stupid." <i>Albert Einstein</i> </p>
                    </div>
                </div>
            </div>
        </section>
        <!-- Footer-->
        <footer class="py-5 bg-dark">
            <div class="container"><p class="m-0 text-center text-white">Copyright &copy; Your Website 2021</p></div>
        </footer>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

