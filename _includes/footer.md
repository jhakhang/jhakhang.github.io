
  <footer class="site-footer">
      <div class="container">
        <div class="row">
          <div class="col-lg-4">
            <div class="mb-5">
               <figure>
                  <img  src="{{site.baseurl}}/assets/images/logo-footer.png" alt="Image placeholder" class="img-fluid rounded mx-auto" style="width: 200px">
                </figure>
            </div>
            <div class="col-lg-12 mb-7 mb-lg-0">
          </div>
          </div>
          <div class="col-lg-8 mb-5 mb-lg-0">
              <div class="row">
                <div class="col-md-12 ">
                  <h3 class="footer-heading mb-4 text-center">Find us on: </h3>
                </div>
                <div class="col-md-12 col-sm-3 justify-content-center">
                   <a href="{{site.spotify}}">
                    <img src="{{site.baseurl}}/assets/images/badges/badge-spotify.png" class="img-fluid brand-badge">
                  </a>
                 <a href="{{site.google-podcast}}">
                  <img src="{{site.baseurl}}/assets/images/badges/badge-googlepodcasts.png" class="img-fluid brand-badge">
                 </a>
                 <a href="{{site.soundcloud}}">
                  <img src="{{site.baseurl}}/assets/images/badges/badge-soundcloud.png" class="img-fluid brand-badge">
                 </a>
                 <a href="{{site.amazon}}">
                  <img src="{{site.baseurl}}/assets/images/badges/badge-amazonmusic.png" class="img-fluid brand-badge">
                </a>
                <a href="{{site.apple-podcast}}">
                  <img src="{{site.baseurl}}/assets/images/badges/badge-apple.png" class="img-fluid brand-badge">
                </a>
              </div>
            </div>
              <!--
                <div class="row">
                <div class="col-md-12">
                  <h3 class="footer-heading mb-4">Tell your friends about us.</h3>
                  <div>
                    <a href="https://www.facebook.com/sharer/sharer.php?u={{site.web-url}}{{page.url}}
  " class="pl-0 pr-3"><span class="icon-facebook"></span></a>
                    <a href="http://twitter.com/share?url={{site.web-url}}{{page.url}}&text={{page.title}}&via={{page.author}}" class="pl-3 pr-3"><span class="icon-twitter"></span></a>
                    <a href="{{site.web-url}}/rss.xml" class="pl-3 pr-3"><span class="icon-rss"></span></a>
                  </div>
                </div>
              </div>
            -->
          </div>      
        </div>
        <div class="row pt-5 mt-5 text-center">
          <div class="col-md-12">
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



setShareLinks(); /* call to social share function in scrpt.js */
    </script>
  <script src="{{site.baseurl}}/assets/js/main.js"></script>
  <script id="dsq-count-scr" src="//jhakhang-com.disqus.com/count.js" async></script>

  </body>
</html>