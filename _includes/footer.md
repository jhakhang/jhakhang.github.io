
  <footer class="site-footer">
      <div class="container">
        <div class="row">
          <div class="col-lg-4">
            <div class="mb-5">
              <h3 class="footer-heading mb-4">About Us</h3>
              <p>Jhakhang is a venue where a group of friends get together from time to time to discuss global issues and social phenomena that might interest Tibetan audiences. From art and culture to politics and society, we discuss a wide range of topics that have implications and consequences for the Tibetan world.</p>
            </div>
            <div class="mb-5">
                <div class="col-lg-8 mb-5 mb-lg-0">
            <div class="row">
              <div class="col-md-12">
                <h3 class="footer-heading mb-4">Follow Us</h3>
                <div>
                  <a href="#" class="pl-0 pr-3"><span class="icon-facebook"></span></a>
                  <a href="#" class="pl-3 pr-3"><span class="icon-twitter"></span></a>
                  <a href="#" class="pl-3 pr-3"><span class="icon-instagram"></span></a>
                  <a href="#" class="pl-3 pr-3"><span class="icon-rss"></span></a>
                </div>
              </div>
            </div>
          </div>
            </div>
          </div>
          <div class="col-lg-6 mb-5 mb-lg-0">
            <div class="row">
            </div>
          </div>
          <div class="col-lg-2 mb-5 mb-lg-0">
            <div class="mb-5">
              <img src="">
              <figure>
                  <img  src="{{site.baseurl}}/assets/images/logo-footer.png" alt="Image placeholder" class="img-fluid rounded mx-auto">
                </figure>
            </div>
          </div>      
        </div>
        <div class="row pt-5 mt-5 text-center">
          <div class="col-md-12">
            <p>
            <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
            <script data-cfasync="false" src=""></script><script>document.write(new Date().getFullYear());</script> JAHANG 2021
            <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
            </p>
          </div>       
      </div>
     </div>
    </footer>
  </div>
  <script src="{{site.baseurl}}/assets/js/jquery-3.3.1.min.js"></script>
  <script src="{{site.baseurl}}/assets/js/jquery-migrate-3.0.1.min.js"></script>
  <script src="{{site.baseurl}}/assets/js/jquery-ui.js"></script>
  <script src="{{site.baseurl}}/assets/js/popper.min.js"></script>
  <script src="{{site.baseurl}}/assets/js/bootstrap.min.js"></script>
  <script src="{{site.baseurl}}/assets/js/owl.carousel.min.js"></script>
  <script src="{{site.baseurl}}/assets/js/jquery.stellar.min.js"></script>
  <script src="{{site.baseurl}}/assets/js/jquery.countdown.min.js"></script>
  <script src="{{site.baseurl}}/assets/js/jquery.magnific-popup.min.js"></script>
  <script src="{{site.baseurl}}/assets/js/aos.js"></script>

  <script src="{{site.baseurl}}/assets/js/mediaelement-and-player.min.js"></script>

  <script>
      document.addEventListener('DOMContentLoaded', function() {
                var mediaElements = document.querySelectorAll('video, audio'), total = mediaElements.length;

                for (var i = 0; i < total; i++) {
                    new MediaElementPlayer(mediaElements[i], {
                        pluginPath: 'https://cdn.jsdelivr.net/npm/mediaelement@4.2.7/build/',
                        shimScriptAccess: 'always',
                        success: function () {
                            var target = document.body.querySelectorAll('.player'), targetTotal = target.length;
                            for (var j = 0; j < targetTotal; j++) {
                                target[j].style.visibility = 'visible';
                            }
                  }
                });
                }
            });
    </script>
  <script src="{{site.baseurl}}/assets/js/main.js"></script>
  </body>
</html>