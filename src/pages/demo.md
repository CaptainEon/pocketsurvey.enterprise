---
_schema: default
title: Book a Live Software Demo | PocketSurvey
seo:
  page_description: >-
    Schedule a live 1-on-1 PocketSurvey software demonstration with our technical sales team directly on our calendar.
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
layout: layouts/layout.html
permalink: /demo/
eleventyExcludeFromCollections: false
templateEngineOverride: njk, html
---

<!-- Google Official Inline Scheduling Resources -->
<link href="https://calendar.google.com/calendar/scheduling-button-script/resources/calendar-inline-css.css" rel="stylesheet">
<script src="https://calendar.google.com/calendar/scheduling-button-script/resources/calendar-inline-js.js" async></script>

<div class="w3-auto w3-container w3-section" style="max-width:1040px; padding-top:24px; padding-bottom:60px;">
  
  <!-- Hero Section -->
  <div class="w3-center" style="margin-bottom:32px;">
    <span class="w3-tag w3-green w3-round" style="letter-spacing:1px; font-weight:700; text-transform:uppercase; font-size:11px; padding:4px 12px; margin-bottom:12px;">Live Consultation</span>
    <h1 style="font-weight:800; color:#202124; font-size:2.2rem; margin-top:8px; margin-bottom:12px;">Book a Meeting with Our Sales Team</h1>
    <p style="color:#5F6368; font-size:1.05rem; line-height:1.5; max-width:680px; margin:0 auto;">
      Welcome to our online diary. Choose a suitable day and time slot directly from the calendar below.
    </p>
  </div>

  <!-- Main Container Card for Inline Calendar -->
  <div class="w3-card-4 w3-white" style="border-radius:12px; overflow:hidden; border:1px solid #E8EAED; margin-bottom:28px;">
    
    <!-- Feature Banner Bar -->
    <div style="background:#FAFAFA; border-bottom:1px solid #E8EAED; padding:16px 24px; display:flex; justify-content:space-around; align-items:center; flex-wrap:wrap; gap:16px; text-align:center;">
      <div><i class="fa fa-mobile" style="color:#1A73E8; margin-right:6px;"></i> <b>Mobile App Walkthrough</b></div>
      <div><i class="fa fa-file-pdf-o" style="color:#34A853; margin-right:6px;"></i> <b>Automated PDF Deliverables</b></div>
      <div><i class="fa fa-sliders" style="color:#F29900; margin-right:6px;"></i> <b>Custom Module Configuration</b></div>
    </div>

    <!-- Inline Calendar Target Container -->
    <div id="google-calendar-inline-slot" style="width: 150%; min-height: 700px; background: #FFFFFF; padding: 12px; box-sizing: border-box;"></div>

  </div>

  <!-- Footer Help text -->
  <div class="w3-center" style="margin-top:28px; color:#5F6368; font-size:0.85rem; line-height:1.4;">
    At the time of the meeting, visit <a href="https://www.pocketsurvey.com/google-demo" target="_blank" style="color:#1A73E8; font-weight:700; text-decoration:none;">pocketsurvey.com/google-demo</a> to join.<br>
    Prefer to talk directly? Call technical sales on <a href="tel:+441615151414" style="color:#1A73E8; font-weight:700; text-decoration:none;">0161 515 1414</a>.
  </div>

</div>

<!-- Script to render the inline calendar template into our container -->
<script>
  window.addEventListener('load', function() {
    if (typeof calendar !== 'undefined' && calendar.schedulingButton) {
      calendar.schedulingButton.loadAppointmentInlineTemplate({
        url: 'https://calendar.google.com/calendar/appointments/schedules/AcZssZ0Ef1kx_qWwXxjzc35suiWttsphO6FKSs7yNp1oVOuWn9mXMY5iDA_F8rn4QO9-mBUwmjPR4Fzn',
        target: document.getElementById('google-calendar-inline-slot')
      });
    }
  });
</script>