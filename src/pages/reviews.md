---
_schema: default
title: Client Reviews & Testimonials | PocketSurvey
seo:
  page_description: >-
    Read what industry leaders and global organisations say about PocketSurvey. See how our mobile inspection apps deliver real-world benefits for surveying organisations.
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
layout: layouts/layout.html
permalink: /reviews/
eleventyExcludeFromCollections: false
templateEngineOverride: njk, html
---

<div style="background: radial-gradient(circle at 50% 0%, #F1F5F9 0%, #FAFAFA 70%); color: #0F172A; padding: 48px 16px 80px 16px; min-height: 85vh; box-sizing: border-box; width: 100%;">
  <div style="max-width: 1240px; margin: 0 auto; width: 100%; box-sizing: border-box;">
    
    <!-- Header Section -->
    <div style="text-align: center; margin-bottom: 48px;">
      <span style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 12px; letter-spacing: 1px; text-transform: uppercase;">
        Client Success Stories
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 800; color: #09090B; margin: 0 0 10px 0; letter-spacing: -0.03em;">
        User Reviews
      </h1>
      <p style="font-size: 1.05rem; color: #64748B; max-width: 620px; margin: 0 auto; line-height: 1.5;">
        Trusted by industry leaders and global organisations. Discover how our software transforms surveying workflows.
      </p>
    </div>

    <!-- REVIEW GRID WALL -->
    <div style="display: flex !important; flex-wrap: wrap !important; gap: 24px !important; justify-content: center !important; width: 100% !important; box-sizing: border-box !important;">
      
      {% for review in site.data.reviews %}
      <div class="ps-review-card" style="flex: 1 1 360px; max-width: 380px; background: #FFFFFF; border: 1px solid #E2E8F0; border-radius: 16px; overflow: hidden; box-shadow: 0 10px 24px rgba(0,0,0,0.04); transition: all 0.3s ease; display: flex; flex-direction: column; justify-content: space-between;">
        <div style="padding: 24px;">
          <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 16px; min-height: 40px;">
            <img src="{{ review.logo }}" alt="{{ review.company }} Logo" style="max-height: 35px; max-width: 120px; object-fit: contain;">
            <div style="color: #F59E0B; font-size: 0.8rem; display: flex; gap: 2px;">
              <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
            </div>
          </div>
          
          <h3 style="font-size: 1.1rem; font-weight: 800; color: #0F172A; margin: 0 0 8px 0; line-height: 1.3;">
            <i class="fa-solid fa-quote-left" style="color: #CBD5E1; font-size: 0.8em; margin-right: 4px;"></i>
            {{ review.quote_title }}
          </h3>
          
          <p style="font-size: 0.85rem; font-weight: 700; color: #2563EB; text-transform: uppercase; letter-spacing: 0.5px; margin: 0 0 16px 0;">
            {{ review.company }} &bull; {{ review.sector }}
          </p>
          
          <div style="background: #F8FAFC; border-left: 3px solid {{ review.border_color | default: '#2563EB' }}; padding: 12px 16px; border-radius: 0 8px 8px 0;">
            <p style="font-size: 0.88rem; color: #475569; line-height: 1.6; margin: 0 0 12px 0; font-style: italic;">
              "{{ review.quote_text }}"
            </p>
            <span style="font-size: 0.78rem; font-weight: 700; color: #64748B;">&mdash; {{ review.author }}</span>
          </div>
        </div>
        
        <div style="padding: 14px 24px; background: #F8FAFC; border-top: 1px solid #E2E8F0; display: flex; justify-content: space-between; align-items: center;">
          <a href="{{ review.app_url }}" style="color: {{ review.border_color | default: '#2563EB' }}; font-weight: 700; font-size: 0.82rem; text-decoration: none;">
            Explore App <i class="fa-solid fa-arrow-right" style="font-size: 0.7rem; margin-left: 4px;"></i>
          </a>
          <a href="{{ review.website_url }}" target="_blank" rel="noopener noreferrer" style="color: #64748B; font-weight: 600; font-size: 0.78rem; text-decoration: none;">
            Visit Website
          </a>
        </div>
      </div>
      {% endfor %}

    </div>
  </div>
</div>

<style>
  .ps-review-card:hover {
    transform: translateY(-8px) scale(1.02) !important;
    border-color: #2563EB !important;
    box-shadow: 0 20px 40px rgba(37, 99, 235, 0.12) !important;
  }
</style>