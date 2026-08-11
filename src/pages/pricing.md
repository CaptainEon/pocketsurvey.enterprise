---
_schema: default
title: Enterprise Pricing & Licensing | PocketSurvey
seo:
  page_description: >-
    Transparent enterprise licensing for PocketSurvey Enterprise. Includes Stock Condition, Commercial Planned Maintenance, custom CSV exports for NEC, Capita, Civica, Keystone, and MRI.
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
layout: layouts/layout.html
permalink: /pricing/
eleventyExcludeFromCollections: false
---

{% raw %}
<div style="background-color: #FAFAFA; color: #18181B; padding: 40px 16px 60px 16px; min-height: 80vh; box-sizing: border-box; overflow: hidden;">
  <div style="max-width: 800px; margin: 0 auto; width: 100%;">
    
    <!-- Minimal Header -->
    <div style="text-align: center; margin-bottom: 24px;">
      <span class="ps-badge-platinum" style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.8rem; padding: 4px 12px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 20px; display: inline-block; margin-bottom: 12px;">ENTERPRISE LICENSING</span>
      <h1 style="font-size: clamp(1.8rem, 3.5vw, 2.5rem); font-weight: 800; color: #09090B; margin: 0 0 8px 0; letter-spacing: -0.02em;">Simple, All-Inclusive Enterprise Pricing</h1>
      <p style="font-size: 0.98rem; color: #52525B; margin: 0 auto; line-height: 1.5;">Select a plan tier below to orbit between pricing options.</p>
    </div>

    <!-- Top Pill Controls -->
    <div style="display: flex; justify-content: center; margin-bottom: 28px;">
      <div style="background: #E4E4E7; padding: 4px; border-radius: 30px; display: inline-flex; gap: 4px;">
        <button id="pill-enterprise" onclick="orbitToTier('enterprise')" style="padding: 8px 24px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: #2563EB; color: #FFFFFF; box-shadow: 0 2px 8px rgba(37,99,235,0.3); transition: all 0.25s ease;">Enterprise</button>
        <button id="pill-custom" onclick="orbitToTier('custom')" style="padding: 8px 24px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: transparent; color: #52525B; transition: all 0.25s ease;">Custom</button>
      </div>
    </div>

    <!-- Moon-Orbit 3D Perspective Stage -->
    <div style="perspective: 1200px; width: 100%; position: relative; height: 560px; max-height: 560px; display: flex; justify-content: center; align-items: flex-start; overflow: visible;">
      
      <!-- CARD 1: ENTERPRISE (Foreground / Active) -->
      <div id="card-enterprise" onclick="orbitToTier('enterprise')" class="ps-moon-card pos-earth-front" style="position: absolute; top: 0; left: 0; right: 0; margin: 0 auto; width: 100%; max-width: 480px; background: #FFFFFF; border: 2px solid #2563EB; border-radius: 16px; overflow: hidden; box-shadow: 0 20px 40px rgba(37, 99, 235, 0.15); box-sizing: border-box; cursor: pointer;">
        <div style="background: #2563EB; padding: 16px 20px; text-align: center; color: #FFFFFF;">
          <h2 style="font-size: 1.5rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Enterprise</h2>
        </div>
        <div style="text-align: center; padding: 18px 20px 14px 20px; border-bottom: 1px solid #F1F5F9;">
          <div style="font-size: 2.6rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">£175</div>
          <div style="font-size: 0.88rem; font-weight: 700; color: #2563EB;">Price Per App</div>
          <div style="font-size: 0.78rem; color: #71717A; margin-top: 2px;">per user / month</div>
        </div>
        <div style="padding: 16px 20px;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #2563EB; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 10px;">AVAILABLE APPS</div>
          <div style="margin-bottom: 10px; display: flex; align-items: flex-start; gap: 8px;">
            <i class="fa-solid fa-check" style="color: #2563EB; font-size: 1rem; margin-top: 2px;"></i>
            <div>
              <div style="font-weight: 700; color: #0F172A; font-size: 0.88rem;">Housing Stock Condition</div>
              <div style="font-size: 0.76rem; color: #64748B; margin-top: 1px;">(Decent Homes, SHQS, WHQS)</div>
            </div>
          </div>
          <div style="margin-bottom: 6px; display: flex; align-items: flex-start; gap: 8px;">
            <i class="fa-solid fa-check" style="color: #2563EB; font-size: 1rem; margin-top: 2px;"></i>
            <div>
              <div style="font-weight: 700; color: #0F172A; font-size: 0.88rem;">Commercial Planned Maintenance</div>
              <div style="font-size: 0.76rem; color: #64748B; margin-top: 1px;">(Standard, BCIS, SFG20, 6 Facet)</div>
            </div>
          </div>
        </div>
        <div style="background: #ECFEFF; border-top: 1px solid #CFFAFE; padding: 14px 20px;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #0891B2; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 8px;">ENTERPRISE FEATURES</div>
          <ul style="list-style: none; padding: 0; margin: 0; font-size: 0.8rem; color: #155E75; display: flex; flex-direction: column; gap: 5px;">
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Segmented Databases</li>
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> External Image Gallery</li>
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Advanced Desktop Mode</li>
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> PDF Reports</li>
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Direct CSV Export (NEC, Capita, Civica, MRI)</li>
          </ul>
        </div>
        <div style="padding: 14px 20px; background: #ECFEFF; border-top: 1px solid #CFFAFE;">
          <a href="/enquiry.htm" class="ps-header-cta" style="display: block; width: 100%; padding: 10px 16px; font-size: 0.88rem; box-sizing: border-box; text-align: center; margin: 0;">Book Demo <i class="fa-solid fa-arrow-right" style="margin-left: 4px;"></i></a>
        </div>
      </div>

      <!-- CARD 2: CUSTOM (Moon / Inactive Orbit Behind) -->
      <div id="card-custom" onclick="orbitToTier('custom')" class="ps-moon-card pos-moon-back" style="position: absolute; top: 0; left: 0; right: 0; margin: 0 auto; width: 100%; max-width: 480px; background: #FFFFFF; border: 1px solid #E4E4E7; border-radius: 16px; overflow: hidden; box-shadow: 0 10px 24px rgba(0,0,0,0.04); box-sizing: border-box; cursor: pointer;">
        <div style="background: #0F172A; padding: 16px 20px; text-align: center; color: #FFFFFF;">
          <h2 style="font-size: 1.5rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Custom</h2>
        </div>
        <div style="text-align: center; padding: 18px 20px 14px 20px; border-bottom: 1px solid #F1F5F9;">
          <div style="font-size: 2.6rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">Quote</div>
          <div style="font-size: 0.88rem; font-weight: 700; color: #38BDF8;">Custom Development</div>
          <div style="font-size: 0.78rem; color: #71717A; margin-top: 2px;">tailored operational scope</div>
        </div>
        <div style="padding: 16px 20px;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 10px;">BESPOKE SERVICES</div>
          <div style="margin-bottom: 10px; display: flex; align-items: flex-start; gap: 8px;">
            <i class="fa-solid fa-check" style="color: #0F172A; font-size: 1rem; margin-top: 2px;"></i>
            <div>
              <div style="font-weight: 700; color: #0F172A; font-size: 0.88rem;">Tailored Mobile Inspection Forms</div>
              <div style="font-size: 0.76rem; color: #64748B; margin-top: 1px;">(Custom form logic, branching &amp; scoring)</div>
            </div>
          </div>
          <div style="margin-bottom: 6px; display: flex; align-items: flex-start; gap: 8px;">
            <i class="fa-solid fa-check" style="color: #0F172A; font-size: 1rem; margin-top: 2px;"></i>
            <div>
              <div style="font-weight: 700; color: #0F172A; font-size: 0.88rem;">Proprietary Schema Exporters</div>
              <div style="font-size: 0.76rem; color: #64748B; margin-top: 1px;">(Custom CSV, XML, JSON exports)</div>
            </div>
          </div>
        </div>
        <div style="background: #F8FAFC; border-top: 1px solid #E2E8F0; padding: 14px 20px;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #475569; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 8px;">BESPOKE INCLUSIONS</div>
          <ul style="list-style: none; padding: 0; margin: 0; font-size: 0.8rem; color: #334155; display: flex; flex-direction: column; gap: 5px;">
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Custom Defect Scoring Logic</li>
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Tailored Client PDF Templates</li>
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Custom Database Schema Mapping</li>
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Dedicated UK Development Lead</li>
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Continuous Regulatory Updates</li>
          </ul>
        </div>
        <div style="padding: 14px 20px; background: #F8FAFC; border-top: 1px solid #E2E8F0;">
          <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="display: block; width: 100%; padding: 10px 16px; font-size: 0.88rem; box-sizing: border-box; text-align: center; margin: 0; border-color: #CBD5E1; color: #09090B !important;">Talk to Us <i class="fa-solid fa-comments" style="margin-left: 4px; color: #2563EB;"></i></a>
        </div>
      </div>

    </div>

    <!-- Footer Badges -->
    <div style="border-top: 1px solid #E2E8F0; margin-top: 20px; padding-top: 20px; text-align: center; clear: both;">
      <span style="font-size: 0.75rem; font-weight: 700; color: #64748B; text-transform: uppercase; letter-spacing: 1px; display: block; margin-bottom: 12px;">Direct Automated Data Exporters Included</span>
      <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 8px; font-weight: 700; font-size: 0.82rem; color: #0F172A;">
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 12px; border-radius: 8px;">NEC Software</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 12px; border-radius: 8px;">Capita Housing</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 12px; border-radius: 8px;">Civica Horizon</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 12px; border-radius: 8px;">Keystone</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 12px; border-radius: 8px;">MRI Software</span>
      </div>
    </div>

  </div>
</div>

<!-- Celestial Moon-Orbit 3D Path Animations -->
<style>
  .ps-moon-card {
    transition: transform 0.8s cubic-bezier(0.4, 0, 0.2, 1), opacity 0.8s ease, filter 0.8s ease;
    transform-style: preserve-3d;
  }

  /* FRONT POSITION (Earth Foreground) */
  .pos-earth-front {
    transform: translate3d(0, 0, 60px) scale(1) rotateY(0deg);
    z-index: 10 !important;
    opacity: 1 !important;
    filter: grayscale(0%) blur(0px) !important;
  }

  /* BACK POSITION (Moon Background Orbit) */
  .pos-moon-back {
    transform: translate3d(120px, 15px, -150px) scale(0.82) rotateY(-20deg);
    z-index: 1 !important;
    opacity: 0.38 !important;
    filter: grayscale(85%) blur(1.5px) !important;
  }

  .pos-moon-back:hover {
    opacity: 0.7 !important;
    filter: grayscale(30%) blur(0px) !important;
  }

  /* ORBITAL REVOLUTION ANIMATIONS (Sweeps around on a 3D circle) */
  @keyframes moonOrbitToFront {
    0% { transform: translate3d(120px, 15px, -150px) scale(0.82) rotateY(-20deg); opacity: 0.38; }
    40% { transform: translate3d(-180px, 0px, -50px) scale(0.9) rotateY(-90deg); opacity: 0.7; }
    100% { transform: translate3d(0, 0, 60px) scale(1) rotateY(-360deg); opacity: 1; }
  }

  @keyframes earthOrbitToBack {
    0% { transform: translate3d(0, 0, 60px) scale(1) rotateY(0deg); opacity: 1; }
    40% { transform: translate3d(200px, 15px, -80px) scale(0.88) rotateY(90deg); opacity: 0.6; }
    100% { transform: translate3d(120px, 15px, -150px) scale(0.82) rotateY(340deg); opacity: 0.38; }
  }

  .anim-orbit-to-front {
    animation: moonOrbitToFront 0.85s cubic-bezier(0.34, 1.2, 0.64, 1) forwards !important;
  }

  .anim-orbit-to-back {
    animation: earthOrbitToBack 0.85s cubic-bezier(0.34, 1.2, 0.64, 1) forwards !important;
  }
</style>

<script>
  var activeTier = 'enterprise';

  function orbitToTier(targetTier) {
    if (activeTier === targetTier) return;

    var cardEnt = document.getElementById('card-enterprise');
    var cardCust = document.getElementById('card-custom');
    var pillEnt = document.getElementById('pill-enterprise');
    var pillCust = document.getElementById('pill-custom');

    cardEnt.classList.remove('anim-orbit-to-front', 'anim-orbit-to-back');
    cardCust.classList.remove('anim-orbit-to-front', 'anim-orbit-to-back');
    void cardEnt.offsetWidth; // Force Reflow

    if (targetTier === 'enterprise') {
      cardEnt.className = 'ps-moon-card pos-earth-front anim-orbit-to-front';
      cardCust.className = 'ps-moon-card pos-moon-back anim-orbit-to-back';

      cardEnt.style.borderColor = '#2563EB';
      cardCust.style.borderColor = '#E4E4E7';

      pillEnt.style.background = '#2563EB';
      pillEnt.style.color = '#FFFFFF';
      pillEnt.style.boxShadow = '0 2px 8px rgba(37,99,235,0.3)';

      pillCust.style.background = 'transparent';
      pillCust.style.color = '#52525B';
      pillCust.style.boxShadow = 'none';
    } else {
      cardCust.className = 'ps-moon-card pos-earth-front anim-orbit-to-front';
      cardEnt.className = 'ps-moon-card pos-moon-back anim-orbit-to-back';

      cardCust.style.borderColor = '#0F172A';
      cardEnt.style.borderColor = '#E4E4E7';

      pillCust.style.background = '#0F172A';
      pillCust.style.color = '#FFFFFF';
      pillCust.style.boxShadow = '0 2px 8px rgba(15,23,42,0.3)';

      pillEnt.style.background = 'transparent';
      pillEnt.style.color = '#52525B';
      pillEnt.style.boxShadow = 'none';
    }

    activeTier = targetTier;
  }
</script>
{% endraw %}