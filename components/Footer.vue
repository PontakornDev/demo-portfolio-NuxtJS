<template>
<div>
    <footer class="pt-4 pb-4 text-center bg-light">
  <div class="container">
    <div class="my-3">
      <div class="h4">Pontakorn Changpat</div>
      <p>Web Developer & Software Developer</p>
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
    <div class="text-small text-secondary">
      <div class="mb-1">&copy; Computer Engineering. CRRU.</div>
      <div>Design - <strong>Pontakorn Changpat</strong></div>
      <div>{{time}}</div>
    </div>
  </div>
</footer>
</div>
</template>

<script>
export default {
  data: function() {
return{
  time: 'You loaded this page on ' + new Date().toLocaleString()
}
  }
  };
</script>