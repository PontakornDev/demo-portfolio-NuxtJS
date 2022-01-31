<template>
  <div>
      <Header />
      <div class="hello">
    <div class="cover bg-light">
    <div class="container px-3">
      <div class="row">
        <div class="col-lg-6 p-2"><img class="img-fluid bg-light" src="../static/picture/example-scene-2.svg" alt="hello"/></div>
        <div class="col-lg-6">
          <div class="mt-5">
            <p class="lead text-uppercase mb-1">Hello!</p>
            <h1 class="intro-title" >I’m Pontakorn Changpat</h1>
            <p class="lead fw-normal mt-3">Web Developer & Software Developer</p>
            <div class="social-nav">
              <nav role="navigation">
                <ul class="nav justify-content-center">
                  <li class="nav-item"><a class="nav-link" href="https://twitter.com" title="Twitter" target="_blank"><i class="fab fa-twitter"></i><span class="menu-title sr-only">Twitter</span></a></li>
                  <li class="nav-item"><a class="nav-link" href="https://www.facebook.com/pontakorn.changpat" title="Facebook" target="_blank"><i class="fab fa-facebook"></i><span class="menu-title sr-only">Facebook</span></a></li>
                  <li class="nav-item"><a class="nav-link" href="https://www.instagram.com/Pontakorn322" title="Instagram" target="_blank"><i class="fab fa-instagram"></i><span class="menu-title sr-only">Instagram</span></a></li>
                  <li class="nav-item"><a class="nav-link" href="https://line.me/th/" title="Line" target="_blank"><i class="fab fa-line"></i><span class="menu-title sr-only">Instagram</span></a></li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
        <div class="section pt-4 px-3 px-lg-4" id="about">
  <div class="container-narrow">
    <div class="row">
      <div class="col-md-6">
        <h2 class="h4 my-2 myname">Hello! I’m Pontakorn Changpat.</h2>
        <p>I am passionate about a Web applications. I am a skilled front-end developer tools such as Javascript CSS HTML5 jQuery and Ajax and back-end developer tools such as NodeJS Express Mysql Sequelize. I am a quick learner and a team worker that gets the job done. I want to learn new things and find new experiences, <strong> Please let me join your team.</strong></p>
        <div class="row mt-3">
          <div class="col-sm-2">
            <div class="pb-1">Age:</div>
          </div>
          <div class="col-sm-10 ">
            <div class="pb-1 fw-bolder">22</div>
          </div>
          <div class="col-sm-2 ">
            <div class="pb-1">Email:</div>
          </div>
          <div class="col-sm-10 ">
            <div class="pb-1 fw-bolder">Pontakorn322@gmail.com</div>
          </div>
          <div class="col-sm-2">
            <div class="pb-1">Phone:</div>
          </div>
          <div class="col-sm-10 ">
            <div class="pb-1 fw-bolder">0620409695</div>
          </div>
          <div class="col-sm-2">
            <div class="pb-1">Address:</div>
          </div>
          <div class="col-sm-10 ">
            <div class="pb-1 fw-bolder">Thoeng, Chiang Rai , Thailand, 57160</div>
          </div>
          <div class="col-sm-2">
            <div class="pb-1">Staus:</div>
          </div>
          <div class="col-sm-10 ">
            <div class="pb-1 fw-bolder">Single</div>
          </div>
        </div>
      </div>
      <div class="col-md-5 offset-md-1" data-aos="fade-left" data-aos-delay="100"><img class="avatar img-fluid mt-2" src="../static/picture/profile.jpg" width="400" height="400" alt="Walter Patterson"/></div>
    </div>
  </div>
</div>
      <Footer />
    
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.justify-content-center{
  justify-content: center;
}
.section {
  scroll-margin-top: 2rem;
}
img.avatar {
  border-radius: 30px;
}
.container-narrow {
  max-width: 1024px;
  margin: 0 auto;
}
#about{
    text-align: left !important; 
}

</style>
