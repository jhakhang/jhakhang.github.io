  <div class="site-blocks-cover overlay" style="background-image: url({{site.baseurl}}/assets/images/hero_bg_1.jpg);" data-aos="fade" data-stellar-background-ratio="0.5">
      <div class="container">
        <div class="row align-items-center justify-content-center text-center">
          <div class="col-md-8" data-aos="fade-up" data-aos-delay="400">
 <!-- slider content -->       
{% for post in site.posts limit:1 %}  
            <h2 class="text-white font-weight-light mb-2 display-4">{{post.title}}</h2>
            <h3>{{post.contributor}}</h3>
            <hr style="height:2px; border-bottom:3px solid red">
            <h2 class="text-white font-weight-light mb-2 display-4">{{post.title-en}}</h2>
            <h3>{{post.contributor-en}}</h3>
            <div class="text-white mb-4"><span class="text-white-opacity-05"><small>By {{post.author}} | {{post.date}} | {{post.duration}}</small></span></div>
            <p><a href="{{post.url}}" class="btn btn-primary btn-sm py-3 px-4 small">More</a></p>
            <div class="player">
              <audio id="player2" preload="none" controls style="max-width: 100%">
                <source src="{{post.audio}}" type="audio/mp3">
              </audio>
            </div>
{% endfor %}
 <!-- slider content --> 
          </div>
        </div>
      </div>
    </div>  


