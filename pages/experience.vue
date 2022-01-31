<template>
<div>
    <Header />
    <div class="section px-3 px-lg-4 pt-5" id="experience">
  <div class="container-narrow">
    <div class="text-center mb-5">
      <h2 class="marker marker-center">Experience</h2>
    </div>
    <div class="row">
      <div class="col-md-6">
        <div class="card mb-3">
          <div class="card-header px-3 py-2">
            <div class="d-flex justify-content-between">
              <div>
                <h3 class="h5 mb-1">Web Application for Report a defective device PTT Chiang Rai</h3>
              </div><img src="../static/img/notification.png" width="48" height="48" alt="ui-ux"/>
            </div>
          </div>
          <div class="card-body px-3 py-2">
            <p>PTT Denhah Chiangrai is want to have Web Application keep report defective device for the executives to know the cause and check the background problem.</p>
            <p>Click show link to Web Application here <i class="far fa-hand-point-right"></i> <button v-on:click="ptt" title="show more"> Show More </button></p>
          </div>
          <div v-if="isDetail" class="text-center">
            <a href="http://ptt.cecrru.com/" target="_blank">Web Application PTT</a>
          <img src="../static/img/ptt.jpg" class="img-fluid" alt="ptt" id="picture">
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="card mb-3">
          <div class="card-header px-3 py-2">
            <div class="d-flex justify-content-between">
              <div>
                <h3 class="h5 mb-1">Web Application for Notification Local Government</h3>
              </div><img src="../static/img/map.png" width="48" height="48" alt="app development"/>
            </div>
          </div>
          <div class="card-body px-3 py-2">
            <p>The local Government want to develop villages in the area to be villages 4.0 by using a web application to solve various complaints.</p>
            <p>Click show link to Web Application here <i class="far fa-hand-point-right"></i> <button v-on:click="thoeng" title="show more"> Show More </button></p>
          </div>
          <div v-if="isDetail2" class="text-center">
            <a href="https://wiangthoeng.thesaban.org/" target="_blank">Web Application local Government</a>
          <img src="../static/img/thoeng.jpg" class="img-fluid" alt="thoeng" id="picture">
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="footer">
      <Footer />
  </footer>
</div>
</div>
</template>
<script>
import Footer from '@/components/Footer.vue'
export default {
    name: "Skills",
    components: {
        Footer,
    },
    data: function() {
            return{
                isDetail: false,
                isDetail2: false
            }
        },
    methods: {
        ptt() {
          this.isDetail = !this.isDetail
        },
        thoeng() {
          this.isDetail2 = !this.isDetail2
        }
    }
};
</script>
<style scoped>
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
#experience{
    text-align: left !important; 
}
.marker {
  position: relative;
  display: inline;
  width: auto;
}

.marker-center {
  padding-right: 0;
}
.marker:after {
  content: "";
  width: 125px;
  height: 30px;
  position: absolute;
  bottom: -25px;
  right: -30px;
  background-image: url("../static/img/marker.svg");
  background-repeat: no-repeat;
}

.marker-center:after {
  bottom: -30px;
  left: 50%;
  margin-left: -60px;
}
.footer{
    position: relative;
    margin-top: 16%;
}
#picture{
    padding: 15px 15px;
}
</style>
