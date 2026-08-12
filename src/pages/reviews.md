---
title: "Building Surveying Software: Good Reviews: Client Testimonials: Mobile Apps"
layout: default
---

<div id="index" class="w3-auto">
  <div class="w3-container w3-center w3-padding-32">    
    <h1 class="w3-xxlarge" style="font-weight: 800; letter-spacing: -1px;">User Reviews</h1>    
    <p class="w3-wide w3-text-grey w3-small" style="margin-top: -10px; font-weight: 600; text-transform: uppercase;">      
      Trusted by Industry Leaders & Global Organisations    
    </p>  
  </div>

  <article class="w3-content w3-padding-32">  
    <div class="w3-row-padding" style="display: flex; flex-wrap: wrap;">
      
      {% for review in site.data.reviews %}
      <div class="w3-col l4 m6 s12 w3-margin-bottom" style="display: flex;">      
        <div class="w3-card-4 w3-white w3-round-large" style="display: flex; flex-direction: column; width: 100%;">                
          <div class="w3-container w3-padding-16" style="flex: 1;">                    
            <div style="display: flex; justify-content: space-between; align-items: center; min-height: 40px; margin-bottom: 12px;">            
              <div style="flex: 1; display: flex; align-items: center;">                              
                {% if review.logo %}
                <img src="{{ review.logo }}" alt="{{ review.logo_alt }}" style="max-height: 35px; max-width: 120px; object-fit: contain;">                          
                {% endif %}
              </div>            
              <div class="w3-text-amber w3-small">              
                <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>            
              </div>          
            </div>
            
            <h4 class="w3-large w3-text-grey" style="font-weight: 800; line-height: 1.3; margin: 10px 0;">            
              <span>              
                <i class="fa fa-quote-left" style="font-size: 0.7em; vertical-align: 2px; margin-right: 2px;"></i>              
                {{ review.quote_title }}              
                <i class="fa fa-quote-right" style="font-size: 0.7em; vertical-align: 2px; margin-left: 2px;"></i>            
              </span>          
            </h4>
            
            <h3 class="w3-medium" style="font-weight: bold; margin: 0; color: #000;">{{ review.company }}</h3>          
            <p class="w3-small" style="margin: 0; font-weight: 600;">{{ review.sector }}</p>
            
            <div class="w3-panel w3-light-grey w3-leftbar" style="border-left-color: {{ review.border_color }}; padding: 8px 12px; margin-top: 12px;">            
              <p class="w3-small" style="line-height: 1.5; margin-bottom: 12px;">              
                <i>{{ review.quote_text }}</i>            
              </p>
              <p class="w3-tiny w3-text-grey" style="font-weight: bold; margin: 0; text-transform: none;">              
                &mdash; {{ review.author }}            
              </p>          
            </div>        
          </div>
          
          <div class="w3-container w3-padding-16 w3-light-grey w3-round-bottom" style="border-top: 1px solid #ddd;">          
            <a href="{{ review.app_url }}" class="w3-button w3-block w3-white w3-border w3-round w3-small" style="font-weight: bold; border-color: {{ review.border_color }}; transition: 0.3s; white-space: normal; line-height: 1.4;">            
              {{ review.app_label }}          
            </a>                    
            <div class="w3-center w3-margin-top">            
              <a href="{{ review.website_url }}" target="_blank" class="w3-tiny w3-text-grey w3-hover-text-black" style="text-decoration: none;">              
                Visit {{ review.company }} Website            
              </a>          
            </div>        
          </div>
          
        </div>    
      </div>
      {% endfor %}

    </div>
  </article>
</div>