---
_schema: default
title: Expert Technical Support & Training | PocketSurvey
seo:
  page_description: >-
    Get expert technical support, log a support ticket, or schedule a 1-on-1 Zoom troubleshooting and training session with the PocketSurvey team.
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
layout: layouts/layout.html
permalink: /support/
eleventyExcludeFromCollections: false
templateEngineOverride: njk, html
---

<div style="background: radial-gradient(circle at 50% 0%, #F1F5F9 0%, #FAFAFA 70%); color: #0F172A; padding: 48px 16px 80px 16px; min-height: 85vh; box-sizing: border-box; width: 100%;">
  <div style="max-width: 960px; margin: 0 auto; width: 100%; box-sizing: border-box;">
    
    <!-- Hero Section -->
    <div style="text-align: center; margin-bottom: 40px;">
      <span style="background: rgba(16, 185, 129, 0.1); color: #059669; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(16, 185, 129, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 12px; letter-spacing: 1px; text-transform: uppercase;">Enterprise Support Hub</span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.6rem); font-weight: 800; color: #09090B; margin: 0 0 10px 0; letter-spacing: -0.03em;">How Can We Help You Today?</h1>
      <p style="font-size: 1.02rem; color: #64748B; max-width: 580px; margin: 0 auto; line-height: 1.5;">Log a technical ticket with our engineering desk or schedule a live 1-on-1 Zoom support session with our team.</p>
    </div>

    <!-- Main Grid Container for Ticket Form & Zoom Booking -->
    <div style="display: grid; grid-template-columns: 1fr; gap: 32px;">

      <!-- SECTION 1: Modern Ticket Submission Form -->
      <div style="background: #FFFFFF; border: 1px solid #E2E8F0; border-radius: 20px; overflow: hidden; box-shadow: 0 12px 35px rgba(0,0,0,0.04); box-sizing: border-box;">
        
        <!-- Shaded Top Header Box -->
        <div style="background: #F8FAFC; border-bottom: 1px solid #E2E8F0; padding: 24px 32px; display: flex; align-items: center; gap: 14px;">
          <div style="width: 44px; height: 44px; background: #EFF6FF; border: 1px solid #DBEAFE; border-radius: 12px; display: flex; align-items: center; justify-content: center; color: #2563EB; font-size: 1.15rem;">
            <i class="fa-solid fa-ticket"></i>
          </div>
          <div>
            <h3 style="font-size: 1.15rem; font-weight: 800; color: #09090B; margin: 0;">Submit a Support Request</h3>
            <p style="font-size: 0.85rem; color: #64748B; margin: 0;">We typically respond to requests within 1 business hour.</p>
          </div>
        </div>

        <!-- Form Body -->
        <div style="padding: 36px 32px;">
          <form action="#" method="POST" style="display: flex; flex-direction: column; gap: 20px;">
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 20px;">
              <div>
                <label style="display: block; font-size: 0.82rem; font-weight: 700; color: #334155; margin-bottom: 6px; text-transform: uppercase; letter-spacing: 0.5px;">Your Name</label>
                <input type="text" name="name" placeholder="e.g. John Smith" required style="width: 100%; padding: 12px 16px; border: 1px solid #CBD5E1; border-radius: 10px; font-size: 0.95rem; background: #F8FAFC; color: #0F172A; box-sizing: border-box; outline: none; transition: all 0.2s;" onfocus="this.style.borderColor='#2563EB'; this.style.background='#FFFFFF'; this.style.boxShadow='0 0 0 3px rgba(37,99,235,0.1)'" onblur="this.style.borderColor='#CBD5E1'; this.style.background='#F8FAFC'; this.style.boxShadow='none'">
              </div>
              <div>
                <label style="display: block; font-size: 0.82rem; font-weight: 700; color: #334155; margin-bottom: 6px; text-transform: uppercase; letter-spacing: 0.5px;">Email Address</label>
                <input type="email" name="email" placeholder="john@company.com" required style="width: 100%; padding: 12px 16px; border: 1px solid #CBD5E1; border-radius: 10px; font-size: 0.95rem; background: #F8FAFC; color: #0F172A; box-sizing: border-box; outline: none; transition: all 0.2s;" onfocus="this.style.borderColor='#2563EB'; this.style.background='#FFFFFF'; this.style.boxShadow='0 0 0 3px rgba(37,99,235,0.1)'" onblur="this.style.borderColor='#CBD5E1'; this.style.background='#F8FAFC'; this.style.boxShadow='none'">
              </div>
            </div>

            <div>
              <label style="display: block; font-size: 0.82rem; font-weight: 700; color: #334155; margin-bottom: 6px; text-transform: uppercase; letter-spacing: 0.5px;">Phone Number</label>
              <input type="tel" name="phone" placeholder="0161 515 1414" style="width: 100%; padding: 12px 16px; border: 1px solid #CBD5E1; border-radius: 10px; font-size: 0.95rem; background: #F8FAFC; color: #0F172A; box-sizing: border-box; outline: none; transition: all 0.2s;" onfocus="this.style.borderColor='#2563EB'; this.style.background='#FFFFFF'; this.style.boxShadow='0 0 0 3px rgba(37,99,235,0.1)'" onblur="this.style.borderColor='#CBD5E1'; this.style.background='#F8FAFC'; this.style.boxShadow='none'">
            </div>

            <div>
              <label style="display: block; font-size: 0.82rem; font-weight: 700; color: #334155; margin-bottom: 6px; text-transform: uppercase; letter-spacing: 0.5px;">Problem Description / Details</label>
              <textarea name="description" rows="4" placeholder="Please describe the issue or features you need help with..." required style="width: 100%; padding: 12px 16px; border: 1px solid #CBD5E1; border-radius: 10px; font-size: 0.95rem; background: #F8FAFC; color: #0F172A; box-sizing: border-box; outline: none; transition: all 0.2s; resize: vertical;" onfocus="this.style.borderColor='#2563EB'; this.style.background='#FFFFFF'; this.style.boxShadow='0 0 0 3px rgba(37,99,235,0.1)'" onblur="this.style.borderColor='#CBD5E1'; this.style.background='#F8FAFC'; this.style.boxShadow='none'"></textarea>
            </div>

            <div style="display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 16px; margin-top: 4px; border-top: 1px solid #F1F5F9; padding-top: 20px;">
              <div style="font-size: 0.78rem; color: #64748B;">
                <i class="fa-solid fa-shield-halved" style="color: #059669; margin-right: 4px;"></i> Protected by secure enterprise SSL.
              </div>
              <button type="submit" class="ps-header-cta" style="padding: 12px 28px; font-size: 0.92rem; border: none; cursor: pointer;">
                <i class="fa-solid fa-paper-plane" style="margin-right: 6px;"></i> Log Support Request
              </button>
            </div>
          </form>
        </div>

      </div>

      <!-- SECTION 2: Zoom Support & Training Suite -->
      <div style="background: linear-gradient(135deg, #0F172A 0%, #1E293B 100%); border-radius: 20px; padding: 36px 32px; color: #FFFFFF; box-shadow: 0 15px 35px rgba(15, 23, 42, 0.2); box-sizing: border-box; position: relative; overflow: hidden;">
        
        <!-- Decorative Background Glow -->
        <div style="position: absolute; top: -50px; right: -50px; width: 200px; height: 200px; background: rgba(37, 99, 235, 0.2); border-radius: 50%; filter: blur(40px); pointer-events: none;"></div>

        <div style="display: flex; align-items: center; gap: 12px; margin-bottom: 20px;">
          <div style="width: 44px; height: 44px; background: rgba(255, 255, 255, 0.1); border: 1px solid rgba(255, 255, 255, 0.15); border-radius: 12px; display: flex; align-items: center; justify-content: center; color: #38BDF8; font-size: 1.15rem; backdrop-filter: blur(8px);">
            <i class="fa-solid fa-video"></i>
          </div>
          <div>
            <h3 style="font-size: 1.15rem; font-weight: 800; color: #FFFFFF; margin: 0;">Expert Technical Support &amp; Training via Zoom</h3>
            <p style="font-size: 0.85rem; color: #94A3B8; margin: 0;">Connect directly with our senior engineers for live troubleshooting.</p>
          </div>
        </div>

        <p style="font-size: 0.92rem; color: #CBD5E1; line-height: 1.6; margin-bottom: 24px; max-width: 700px;">
          Choose an option below to book or start an online Support or Training meeting. Our team can quickly diagnose issues, configure custom layouts, and guide you through advanced workflows.
        </p>

        <div style="display: flex; flex-wrap: wrap; gap: 16px; align-items: center;">
          <!-- Link to Support Booking Page -->
          <a href="/support/book.htm" style="background: #2563EB; color: #FFFFFF; font-weight: 700; text-decoration: none; padding: 12px 24px; border-radius: 10px; font-size: 0.9rem; display: inline-flex; align-items: center; gap: 8px; box-shadow: 0 4px 14px rgba(37,99,235,0.4); transition: transform 0.2s;" onmouseover="this.style.transform='translateY(-1px)'" onmouseout="this.style.transform='translateY(0)'">
            <i class="fa-solid fa-calendar-days"></i> Book Support Meeting
          </a>

          <!-- Zoom Launch Button -->
          <a href="https://zoom.us" target="_blank" rel="noopener noreferrer" style="background: rgba(255, 255, 255, 0.1); border: 1px solid rgba(255, 255, 255, 0.2); color: #FFFFFF; font-weight: 700; text-decoration: none; padding: 12px 24px; border-radius: 10px; font-size: 0.9rem; display: inline-flex; align-items: center; gap: 8px; backdrop-filter: blur(8px); transition: background 0.2s;" onmouseover="this.style.background='rgba(255, 255, 255, 0.15)'" onmouseout="this.style.background='rgba(255, 255, 255, 0.1)'">
            <i class="fa-solid fa-video" style="color: #38BDF8;"></i> Join Zoom Meeting Room
          </a>
        </div>

        <div style="margin-top: 20px; font-size: 0.78rem; color: #94A3B8; border-top: 1px solid rgba(255,255,255,0.1); padding-top: 16px;">
          <i class="fa-solid fa-circle-info" style="color: #38BDF8; margin-right: 4px;"></i> Please ensure you have scheduled a time slot via the support booking page prior to joining an active Zoom room.
        </div>

      </div>

    </div>

  </div>
</div>