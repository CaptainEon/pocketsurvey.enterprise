---
_schema: default
title: Book a Live Software Demo | PocketSurvey
seo:
  page_description: >-
    Schedule a live 1-on-1 PocketSurvey software demonstration with our technical sales team. Select your preferred date and time on our interactive calendar.
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
layout: layouts/layout.html
permalink: /book-demo/
eleventyExcludeFromCollections: false
templateEngineOverride: njk, html
---

<!-- Google Appointment Inline Styles & Script -->
<link href="https://calendar.google.com/calendar/scheduling-button-script/resources/calendar-inline-css.css" rel="stylesheet">
<script src="https://calendar.google.com/calendar/scheduling-button-script/resources/calendar-inline-js.js" async></script>

<div style="background: #F8FAFC; color: #0F172A; padding: 40px 16px 80px 16px; min-height: 85vh; box-sizing: border-box; width: 100%;">
  <div style="max-width: 1200px; margin: 0 auto; width: 100%; box-sizing: border-box;">
    
    <!-- Hero Header -->
    <div style="text-align: center; margin-bottom: 32px;">
      <span style="background: rgba(52, 168, 83, 0.08); color: #1E8E3E; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(52, 168, 83, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 12px; letter-spacing: 1px; text-transform: uppercase;">
        LIVE CONSULTATION
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.5rem); font-weight: 800; color: #202124; margin: 0 0 10px 0; letter-spacing: -0.03em;">
        Book a Meeting with Our Technical Sales Team
      </h1>
      <p style="font-size: 1.05rem; color: #5F6368; max-width: 720px; margin: 0 auto 16px auto; line-height: 1.5;">
        Welcome to our online diary for booking online demonstrations. Start by choosing a suitable day from the calendar below.
      </p>

      <!-- Video Watch Alternative Bar -->
      <div style="display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #FFFFFF; border: 1px solid #E8EAED; padding: 10px 20px; border-radius: 30px; box-shadow: 0 2px 8px rgba(0,0,0,0.03); flex-wrap: wrap; font-size: 0.88rem; color: #5F6368;">
        <span>Because PocketSurvey apps are popular, slots fill quickly. Prefer a quick video?</span>
        <a href="/demos/" style="color: #1A73E8; font-weight: 700; text-decoration: none; display: inline-flex; align-items: center; gap: 4px;">
          Watch a Demo Video Here <i class="fa fa-arrow-right" style="font-size: 0.75rem;"></i>
        </a>
      </div>
    </div>

    <!-- MAIN CALENDAR CONTAINER CARD -->
    <div style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 16px; box-shadow: 0 4px 16px rgba(0,0,0,0.04); overflow: hidden; width: 100%; box-sizing: border-box;">
      
      <!-- Top Benefit Tags Bar -->
      <div style="background: #FAFAFA; border-bottom: 1px solid #E8EAED; padding: 16px 24px; display: flex; justify-content: space-around; align-items: center; flex-wrap: wrap; gap: 16px;">
        <div style="display: flex; align-items: center; gap: 8px;">
          <i class="fa-solid fa-mobile-screen" style="color: #1A73E8;"></i>
          <span style="font-size: 0.85rem; font-weight: 700; color: #3C4043;">Mobile App Walkthrough</span>
        </div>
        <div style="display: flex; align-items: center; gap: 8px;">
          <i class="fa-solid fa-file-pdf" style="color: #34A853;"></i>
          <span style="font-size: 0.85rem; font-weight: 700; color: #3C4043;">Automated PDF Deliverables</span>
        </div>
        <div style="display: flex; align-items: center; gap: 8px;">
          <i class="fa-solid fa-sliders" style="color: #F29900;"></i>
          <span style="font-size: 0.85rem; font-weight: 700; color: #3C4043;">Custom Module Configuration</span>
        </div>
      </div>

      <!-- GOOGLE INLINE SCHEDULER WIDGET TARGET CONTAINER -->
      <div id="ps-google-calendar-container" style="width: 100%; min-height: 650px; background: #FFFFFF; box-sizing: border-box;"></div>

    </div>

    <!-- Direct Meeting Link & Phone Footer -->
    <div style="margin-top: 24px; text-align: center; color: #5F6368; font-size: 0.88rem;">
      At the time of your meeting, visit <a href="https://www.pocketsurvey.com/google-demo" target="_blank" rel="noopener noreferrer" style="color: #1A73E8; font-weight: 700; text-decoration: none;">pocketsurvey.com/google-demo</a> to join.
      <br><br>
      Prefer to talk directly? Call technical sales on <a href="tel:+441615151414" style="color: #1A73E8; font-weight: 700; text-decoration: none;">0161 515 1414</a> or email <a href="mailto:sales@pocketsurvey.com" style="color: #1A73E8; font-weight: 700; text-decoration: none;">sales@pocketsurvey.com</a>.
    </div>

  </div>
</div>

<script>
  window.addEventListener('load', function() {
    if (typeof calendar !== 'undefined' && calendar.schedulingButton) {
      calendar.schedulingButton.loadAppointmentInlineTemplate({
        url: 'https://calendar.google.com/calendar/appointments/schedules/AcZssZ0Ef1kx_qWwXxjzc35suiWttsphO6FKSs7yNp1oVOuWn9mXMY5iDA_F8rn4QO9-mBUwmjPR4Fzn',
        target: document.getElementById('ps-google-calendar-container')
      });
    }
  });
</script>