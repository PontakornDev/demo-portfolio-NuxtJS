<template>
<div>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.0/css/all.min.css">  
    <div class="container-fluid" id="Nav-bar">
  <div class="row mt-4">
    <div class="col-sm-12">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark" >
  <div class="container-fluid">
    <h1 class="link-dark navbar-brand site-title mb-0"><b>NUXT-APP-TEST</b></h1>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
        <div class="collapse navbar-collapse">
          <ul class="navbar-nav ">
            <li class="nav-item active">
              <router-link class="nav-link" to="/"><i class="fas fa-home"></i> Home </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/Experience">
              <i class="fas fa-paste"></i> Experience</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/service"><i class="fas fa-address-card"></i> Service</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/reactivity"><i class="fab fa-react"></i> Reactivity</router-link>
            </li>
          </ul>
        </div>
        </div>
      </nav>
    </div>
  </div>
  </div>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

a.nuxt-link-exact-active {
  background-color:rgb(46, 114, 240) ;
  padding: 15px 5px;
  font-size: 17px;
  border-radius: 5px;
}
h1.navbar-nav{
  color: aliceblue;
}

</style>

<script>
export default {}
</script>