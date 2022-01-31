<template>
<div>
  <Header />
  <div class="section px-3 px-lg-4 pt-5" id="services">
  <div class="container-narrow">
    <div class="text-center mb-5">
      <h2 class="marker marker-center">My Services</h2>
    </div>
    <div class="text-center">
      <p class="mx-auto mb-3" style="max-width:600px"> I offer services fit for any website or work process for website. I can design web application and desing database for user requirements.</p>
    </div>
    <div class="row py-3">
      <div class="col-md-3 text-center"><img class="mb-2" src="../static/img/computer.png" width="96" height="96" alt="web design"/>
        <div class="h5">Web Design</div>
      </div>
      <div class="col-md-3 text-center"><img class="mb-2" src="../static/img/database.png" width="96" height="96" alt="Database design"/>
        <div class="h5">Database Design</div>
      </div>
      <div class="col-md-3 text-center"><img class="mb-2" src="../static/img/ux-design.png" width="96" height="96" alt="ui-ux"/>
        <div class="h5">UI/UX Design</div>
      </div>
      <div class="col-md-3 text-center"><img class="mb-2" src="../static/img/coding.png" width="96" height="96" alt="Web development"/>
        <div class="h5">Web Development</div>
      </div>
    </div>
  </div>
</div>
  <div class="section px-2 px-lg-4 pt-5" id="portfolio">
  <div class="container">
    <div class="text-center mb-5">
      <h2 class="marker marker-center">Portfolio </h2>
    </div>
    <div class="grid bp-gallery pb-5 pt-5 px-5 bg-info">
      <div class="grid-sizer"></div>
      <div class="grid-item">
          <figure class="portfolio-item"><img src="../static/img/1.jpg" />
            <figcaption>
              <h4 class="h5 mb-0">Local Government</h4>
              <div><a href="https://wiangthoeng.thesaban.org/" target="_blank"> wiangthoeng.thesaban.org</a></div>
            </figcaption>
          </figure></div>
      <div class="grid-item">
          <figure class="portfolio-item"><img src="../static/img/2.jpg"/>
            <figcaption> 
              <h4 class="h5 mb-0">Local Government</h4>
              <div><a href="https://wiangthoeng.thesaban.org/" target="_blank"> wiangthoeng.thesaban.org</a></div>
            </figcaption>
          </figure></div>
      <div class="grid-item">
          <figure class="portfolio-item"><img src="../static/img/3.jpg"/>
            <figcaption> 
              <h4 class="h5 mb-0">Local Government</h4>
              <div><a href="https://wiangthoeng.thesaban.org/" target="_blank"> wiangthoeng.thesaban.org</a></div>
            </figcaption>
          </figure></div>
      <div class="grid-item">
          <figure class="portfolio-item"><img src="../static/img/4.jpg"/>
            <figcaption>
              <h4 class="h5 mb-0">Part. PTT Den Hah ltd.</h4>
              <div><a href="http://ptt.cecrru.com/" target="_blank"> ptt.cecrru.com</a></div>
            </figcaption>
          </figure></div>
          <div class="grid-item">
          <figure class="portfolio-item"><img src="../static/img/5.jpg" />
            <figcaption>
              <h4 class="h5 mb-0">Part. PTT Den Hah ltd.</h4>
              <div><a href="http://ptt.cecrru.com/" target="_blank"> ptt.cecrru.com</a></div>
            </figcaption>
          </figure></div>
    </div>
  </div>
</div>
<footer class="footer">
      <Footer />
  </footer>
</div>
</template>
<script>
import Footer from '@/components/Footer.vue'

export default {
  name: 'About',
  components: {
    Footer
  },
}
</script>

<style scoped>
/* Portfolio */
.portolio-section .container {
  padding: 0;
}

.portfolio-item {
  position: relative;
  overflow: hidden;
  text-align: center;
  margin: 0;
}

.portfolio-item figcaption {
  position: absolute;
  top: auto;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 12px;
  background: rgba(255, 255, 255, 0.75);
  transition: transform 0.35s;
  transform: translate3d(0, 100%, 0);
}

.portfolio-item figcaption h4 {
  color: #222;
  font-size: 16px;
  text-transform: uppercase;
  font-weight: 700;
  margin-bottom: 3px;
}

.portfolio-item figcaption p {
  color: #444;
  font-size: 14px;
  font-weight: 600;
  margin-bottom: 0;
}

.portfolio-item:hover figcaption {
  transform: translate3d(0, 0, 0);
}

/* Grid Item */
.grid-sizer,
.grid-item {
  width: 100%;
}

.grid-item {
  padding-bottom: 12px;
}

@media (min-width: 48em) {
  .grid-sizer,
  .grid-item {
    width: 25%;
  }
  .grid-item {
    float: left;
    padding: 6px;
  }
}

.grid-item img {
  display: block;
  width: 100%;
  max-width: 100%;
}
.grid:after {
  content: '';
  display: block;
  clear: both;
}
/* Marker */
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
.bg-info{
  border-radius: 50px;
}
.footer{
  margin-top: 100px;
}

</style>
