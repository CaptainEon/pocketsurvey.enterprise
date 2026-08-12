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

<!-- Google Appointment Popup Script & Styles -->
<link href="https://calendar.google.com/calendar/scheduling-button-script/resources/calendar-inline-css.css" rel="stylesheet">
<script src="https://calendar.google.com/calendar/scheduling-button-script/resources/calendar-inline-js.js" async></script>

<div style="background: #F8FAFC; color: #0F172A; padding: 48px 16px 80px 16px; min-height: 85vh; box-sizing: border-box; width: 100%;">
  <div style="max-width: 880px; margin: 0 auto; width: 100%; box-sizing: border-box;">
    
    <!-- Hero Header -->
    <div style="text-align: center; margin-bottom: 36px;">
      <span style="background: rgba(52, 168, 83, 0.08); color: #1E8E3E; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(52, 168, 83, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 12px; letter-spacing: 1px; text-transform: uppercase;">
        LIVE CONSULTATION
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.5rem); font-weight: 800; color: #202124; margin: 0 0 10px 0; letter-spacing: -0.03em;">
        Book a Meeting with Our Technical Sales Team
      </h1>
      <p style="font-size: 1.05rem; color: #5F6368; max-width: 640px; margin: 0 auto; line-height: 1.5;">
        Welcome to our online diary. Choose a suitable time slot for a 1-on-1 walkthrough tailored to your mobile surveying requirements.
      </p>
    </div>

    <!-- MAIN INTERACTIVE BOOKING CARD -->
    <div style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 16px; box-shadow: 0 4px 16px rgba(0,0,0,0.04); padding: 40px 28px; text-align: center; margin-bottom: 32px;">
      
      <div style="width: 60px; height: 60px; background: #E6F4EA; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 20px auto;">
        <i class="fa-solid fa-calendar-check" style="font-size: 1.6rem; color: #34A853;"></i>
      </div>

      <h2 style="font-size: 1.35rem; font-weight: 800; color: #202124; margin: 0 0 8px 0;">Interactive Google Appointment Scheduler</h2>
      <p style="font-size: 0.92rem; color: #5F6368; max-width: 520px; margin: 0 auto 28px auto; line-height: 1.5;">
        Slots fill quickly. Click below to view available 45-minute demonstration times for the next 7 days.
      </p>

      <!-- Action Button triggering Google's Official Popup Overlay -->
      <button onclick="openGoogleBookingPopup()" style="background: #1A73E8; color: #FFFFFF; border: none; font-size: 1rem; font-weight: 700; padding: 14px 32px; border-radius: 30px; cursor: pointer; box-shadow: 0 4px 12px rgba(26, 115, 232, 0.25); transition: all 0.2s ease; display: inline-flex; align-items: center; gap: 10px;">
        <i class="fa-solid fa-calendar-days"></i> Select Appointment Time <i class="fa-solid fa-arrow-right" style="font-size: 0.85rem;"></i>
      </button>

      <!-- Direct Backup Link if script is blocked by user ad-blocker -->
      <div style="margin-top: 16px;">
        <a href="https://calendar.app.google/xw52JEBLtKsK1J6m8" target="_blank" rel="noopener noreferrer" style="font-size: 0.8rem; color: #5F6368; text-decoration: underline;">
          Or open calendar directly in a new window
        </a>
      </div>

      <!-- Feature Badges -->
      <div style="display: flex; justify-content: center; gap: 24px; margin-top: 36px; padding-top: 28px; border-top: 1px solid #E8EAED; flex-wrap: wrap;">
        <div style="display: flex; align-items: center; gap: 8px;">
          <i class="fa-solid fa-mobile-screen" style="color: #1A73E8;"></i>
          <span style="font-size: 0.85rem; font-weight: 600; color: #3C4043;">Mobile App Walkthrough</span>
        </div>
        <div style="display: flex; align-items: center; gap: 8px;">
          <i class="fa-solid fa-file-pdf" style="color: #34A853;"></i>
          <span style="font-size: 0.85rem; font-weight: 600; color: #3C4043;">Automated PDF Deliverables</span>
        </div>
        <div style="display: flex; align-items: center; gap: 8px;">
          <i class="fa-solid fa-sliders" style="color: #F29900;"></i>
          <span style="font-size: 0.85rem; font-weight: 600; color: #3C4043;">Custom Module Configuration</span>
        </div>
      </div>

    </div>

    <!-- Alternative Options Bar -->
    <div style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 12px; padding: 20px 24px; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 16px;">
      <div>
        <strong style="font-size: 0.92rem; color: #202124; display: block;">Prefer to watch recorded demos first?</strong>
        <span style="font-size: 0.82rem; color: #5F6368;">Explore quick walkthroughs of our inspection software in action.</span>
      </div>
      <a href="/demos/" style="background: #F1F3F4; color: #202124; font-size: 0.85rem; font-weight: 700; padding: 10px 18px; border-radius: 8px; border: 1px solid #DADCE0; text-decoration: none; display: inline-flex; align-items: center; gap: 6px;">
        <i class="fa-solid fa-circle-play" style="color: #1A73E8;"></i> Watch Demo Videos
      </a>
    </div>

    <!-- Meeting Join & Phone Footer -->
    <div style="margin-top: 28px; text-align: center; color: #5F6368; font-size: 0.88rem;">
      At the time of your meeting, visit <a href="https://www.pocketsurvey.com/google-demo" target="_blank" rel="noopener noreferrer" style="color: #1A73E8; font-weight: 700; text-decoration: none;">pocketsurvey.com/google-demo</a> to join.
      <br><br>
      Prefer to talk directly? Call technical sales on <a href="tel:+441615151414" style="color: #1A73E8; font-weight: 700; text-decoration: none;">0161 515 1414</a> or email <a href="mailto:sales@pocketsurvey.com" style="color: #1A73E8; font-weight: 700; text-decoration: none;">sales@pocketsurvey.com</a>.
    </div>

  </div>
</div>

<script>
  function openGoogleBookingPopup() {
    if (typeof calendar !== 'undefined' && calendar.schedulingButton) {
      calendar.schedulingButton.loadAppointmentModal({
        url: 'https://calendar.google.com/calendar/appointments/schedules/AcZssZ0Ef1kx_qWwXxjzc35suiWttsphO6FKSs7yNp1oVOuWn9mXMY5iDA_F8rn4QO9-mBUwmjPR4Fzn'
      });
    } else {
      window.open('https://calendar.app.google/xw52JEBLtKsK1J6m8', '_blank');
    }
  }
</script>