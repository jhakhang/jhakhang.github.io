---
layout: post
---
{% include header.md %}
  
<div class="site-blocks-cover overlay inner-page-cover" style="background-image: url('{{page.banner}}');" data-aos="fade" data-stellar-background-ratio="0.5">
      <div class="container">
        <div class="row align-items-center justify-content-center text-center">
          <div class="col-md-8" data-aos="fade-up" data-aos-delay="400">
            <h2 class="text-white font-weight-light mb-2 display-4">Episode {{page.episode}} : {{page.title}}</h2>
            <div class="text-white mb-3"><span class="text-white-opacity-05"><small>By {{page.author}} <span class="sep">/</span> {{page.date}} <span class="sep">/</span> {{page.duration}}</small></span></div>
          </div>
        </div>
      </div>
    </div>    
    <div class="container site-section">  
      <div class="player mb-5">
        <audio id="player2" preload="none" controls style="max-width: 100%">
          <source src="http://www.largesound.com/ashborytour/sound/AshboryBYU.mp3" type="audio/mp3">
        </audio>
      </div>
      <div class="row justify-content-center">
        <div class="col-md-7">
          {{content}}
        </div>
      </div>
    </div>
    <div class="site-section bg-light">
      <div class="container">
        <div class="row mb-5">
          <div class="col-md-12 text-center">
            <h2 class="font-weight-bold text-black">Related Podcasts</h2>
          </div>
        </div>
        {% include related-posts.md %}
      </div>
    </div>
    


  
{% include footer.md %}