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
<div style="background: radial-gradient(circle at 50% 0%, #F1F5F9 0%, #FAFAFA 70%); color: #0F172A; padding: 40px 16px 80px 16px; min-height: 85vh; box-sizing: border-box; overflow: hidden;">
  <div style="max-width: 900px; margin: 0 auto; width: 100%;">
    
    <!-- Minimalist Header -->
    <div style="text-align: center; margin-bottom: 28px;">
      <span style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 12px; letter-spacing: 1px; text-transform: uppercase;">
        ENTERPRISE LICENSING
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.6rem); font-weight: 800; color: #09090B; margin: 0 0 8px 0; letter-spacing: -0.03em;">
        Simple, All-Inclusive Pricing
      </h1>
      <p style="font-size: 1rem; color: #64748B; max-width: 540px; margin: 0 auto; line-height: 1.5;">
        Select an enterprise tier below to orbit between standard compliance suites and custom app development.
      </p>
    </div>

    <!-- High-End Pill Toggle -->
    <div style="display: flex; justify-content: center; margin-bottom: 36px;">
      <div style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 4px; border-radius: 40px; display: inline-flex; gap: 6px; box-shadow: 0 4px 16px rgba(0,0,0,0.03);">
        <button id="pill-enterprise" onclick="orbitToTier('enterprise')" style="padding: 10px 28px; border-radius: 30px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: #2563EB; color: #FFFFFF; box-shadow: 0 4px 12px rgba(37,99,235,0.3); transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);">
          Enterprise Standard
        </button>
        <button id="pill-custom" onclick="orbitToTier('custom')" style="padding: 10px 28px; border-radius: 30px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: transparent; color: #64748B; transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);">
          Custom Bespoke
        </button>
      </div>
    </div>

    <!-- 3D Orbital Perspective Stage -->
    <div style="perspective: 1200px; width: 100%; position: relative; height: 560px; max-width: 520px; margin: 0 auto 40px auto; overflow: visible;">
      
      <!-- CARD 1: ENTERPRISE (Starts Front & Active) -->
      <div id="card-enterprise" onclick="orbitToTier('enterprise')" class="ps-3d-card is-front-earth" style="position: absolute; top: 0; left: 0; width: 100%; background: #FFFFFF; border: 2px solid #2563EB; border-radius: 20px; overflow: hidden; box-shadow: 0 20px 40px rgba(37, 99, 235, 0.15); box-sizing: border-box; cursor: pointer; transition: all 0.75s cubic-bezier(0.34, 1.25, 0.64, 1);">
        <div style="height: 5px; background: linear-gradient(90deg, #2563EB, #38BDF8);"></div>
        <div style="padding: 24px 28px 18px 28px; text-align: center; border-bottom: 1px solid #F1F5F9; position: relative; background: #FFFFFF;">
          <span style="position: absolute; top: 16px; right: 20px; background: #EFF6FF; color: #2563EB; font-size: 0.7rem; font-weight: 700; padding: 4px 10px; border-radius: 12px; border: 1px solid rgba(37,99,235,0.2);">Most Popular</span>
          <div style="color: #2563EB; font-size: 0.78rem; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 6px;">Enterprise Plan</div>
          <div style="display: flex; align-items: baseline; justify-content: center; gap: 6px; margin-bottom: 2px;">
            <span style="font-size: 3rem; font-weight: 800; color: #0F172A; letter-spacing: -0.03em; line-height: 1;">£175</span>
            <span style="font-size: 0.88rem; color: #64748B; font-weight: 500;">/ user / month</span>
          </div>
          <div style="font-size: 0.78rem; color: #059669; font-weight: 600; margin-top: 4px;"><i class="fa-solid fa-circle-check" style="margin-right: 4px;"></i> Free Setup, Onboarding &amp; Support</div>
        </div>

        <div style="padding: 20px 24px; background: #FFFFFF;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 12px;">Included Frameworks &amp; Apps:</div>
          <div style="display: flex; flex-direction: column; gap: 10px; margin-bottom: 16px;">
            <div style="background: #F8FAFC; border: 1px solid #E2E8F0; padding: 10px 14px; border-radius: 10px; display: flex; align-items: center; gap: 10px;">
              <i class="fa-solid fa-house-building" style="color: #2563EB; font-size: 0.95rem;"></i>
              <div>
                <div style="font-weight: 700; color: #0F172A; font-size: 0.85rem;">Housing Stock Condition</div>
                <div style="font-size: 0.75rem; color: #64748B;">Decent Homes, SHQS, WHQS &amp; HHSRS</div>
              </div>
            </div>
            <div style="background: #F8FAFC; border: 1px solid #E2E8F0; padding: 10px 14px; border-radius: 10px; display: flex; align-items: center; gap: 10px;">
              <i class="fa-solid fa-screwdriver-wrench" style="color: #2563EB; font-size: 0.95rem;"></i>
              <div>
                <div style="font-weight: 700; color: #0F172A; font-size: 0.85rem;">Commercial Planned PPM</div>
                <div style="font-size: 0.75rem; color: #64748B;">Standard RICS, SFG20 &amp; NHS 6-Facets</div>
              </div>
            </div>
          </div>

          <div style="background: rgba(236, 254, 255, 0.7); border: 1px solid #CFFAFE; border-radius: 12px; padding: 14px;">
            <div style="font-size: 0.7rem; font-weight: 700; color: #0891B2; text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 8px;">Enterprise Platform Features:</div>
            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 6px; font-size: 0.78rem; color: #155E75; font-weight: 500;">
              <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 4px;"></i> Segmented Databases</div>
              <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 4px;"></i> Image Gallery</div>
              <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 4px;"></i> Desktop Portal</div>
              <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 4px;"></i> PDF Client Reports</div>
              <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 4px;"></i> CSV Data Exports</div>
              <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 4px;"></i> Assisted Imports</div>
            </div>
          </div>
        </div>

        <div style="padding: 18px 24px; background: #F8FAFC; border-top: 1px solid #E2E8F0; text-align: center;">
          <a href="/enquiry.htm" class="ps-header-cta" style="display: block; width: 100%; padding: 12px 20px; font-size: 0.9rem; box-sizing: border-box; text-align: center; margin: 0; box-shadow: 0 4px 12px rgba(37,99,235,0.25);">
            Book Enterprise Demo <i class="fa-solid fa-arrow-right" style="margin-left: 6px;"></i>
          </a>
        </div>
      </div>

      <!-- CARD 2: CUSTOM (Starts Back & Inactive/Greyed) -->
      <div id="card-custom" onclick="orbitToTier('custom')" class="ps-3d-card is-back-moon" style="position: absolute; top: 0; left: 0; width: 100%; background: #FFFFFF; border: 1px solid #E2E8F0; border-radius: 20px; overflow: hidden; box-shadow: 0 10px 24px rgba(0,0,0,0.04); box-sizing: border-box; cursor: pointer; transition: all 0.75s cubic-bezier(0.34, 1.25, 0.64, 1);">
        <div style="height: 5px; background: linear-gradient(90deg, #38BDF8, #8B5CF6);"></div>
        <div style="padding: 24px 28px 18px 28px; text-align: center; border-bottom: 1px solid #F1F5F9; position: relative; background: #FFFFFF;">
          <span style="position: absolute; top: 16px; right: 20px; background: #F3E8FF; color: #7C3AED; font-size: 0.7rem; font-weight: 700; padding: 4px 10px; border-radius: 12px; border: 1px solid rgba(124,58,237,0.2);">Tailored Scope</span>
          <div style="color: #7C3AED; font-size: 0.78rem; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; margin-bottom: 6px;">Custom Studio Plan</div>
          <div style="display: flex; align-items: baseline; justify-content: center; gap: 6px; margin-bottom: 2px;">
            <span style="font-size: 3rem; font-weight: 800; color: #0F172A; letter-spacing: -0.03em; line-height: 1;">Custom</span>
          </div>
          <div style="font-size: 0.78rem; color: #64748B; font-weight: 500; margin-top: 4px;">Tailored quote based on operational scope</div>
        </div>

        <div style="padding: 20px 24px; background: #FFFFFF;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 12px;">Bespoke Engineering Capabilities:</div>
          <div style="display: flex; flex-direction: column; gap: 10px; margin-bottom: 16px;">
            <div style="background: #F8FAFC; border: 1px solid #E2E8F0; padding: 10px 14px; border-radius: 10px; display: flex; align-items: center; gap: 10px;">
              <i class="fa-solid fa-code" style="color: #7C3AED; font-size: 0.95rem;"></i>
              <div>
                <div style="font-weight: 700; color: #0F172A; font-size: 0.85rem;">Tailored Inspection Forms</div>
                <div style="font-size: 0.75rem; color: #64748B;">Custom form logic, branching &amp; scoring</div>
              </div>
            </div>
            <div style="background: #F8FAFC; border: 1px solid #E2E8F0; padding: 10px 14px; border-radius: 10px; display: flex; align-items: center; gap: 10px;">
              <i class="fa-solid fa-database" style="color: #7C3AED; font-size: 0.95rem;"></i>
              <div>
                <div style="font-weight: 700; color: #0F172A; font-size: 0.85rem;">Proprietary Schema Exporters</div>
                <div style="font-size: 0.75rem; color: #64748B;">Tailored CSV, XML, or JSON legacy exports</div>
              </div>
            </div>
          </div>

          <div style="background: rgba(243, 232, 255, 0.7); border: 1px solid #E9D5FF; border-radius: 12px; padding: 14px;">
            <div style="font-size: 0.7rem; font-weight: 700; color: #6B21A8; text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 8px;">All Enterprise Features, Plus:</div>
            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 6px; font-size: 0.78rem; color: #581C87; font-weight: 500;">
              <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 4px;"></i> Defect Scoring Matrices</div>
              <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 4px;"></i> Corporate PDF Branding</div>
              <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 4px;"></i> Schema Data Mapping</div>
              <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 4px;"></i> Dedicated UK Tech Lead</div>
              <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 4px;"></i> Custom API Exporters</div>
              <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 4px;"></i> Continuous Regulatory Updates</div>
            </div>
          </div>
        </div>

        <div style="padding: 18px 24px; background: #F8FAFC; border-top: 1px solid #E2E8F0; text-align: center;">
          <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="display: block; width: 100%; padding: 12px 20px; font-size: 0.9rem; box-sizing: border-box; text-align: center; margin: 0; border-color: #CBD5E1; color: #09090B !important;">
            Discuss Custom App <i class="fa-solid fa-comments" style="margin-left: 6px; color: #2563EB;"></i>
          </a>
        </div>
      </div>

    </div>

    <!-- Supported Systems Integration Badges Footer -->
    <div style="border-top: 1px solid #E2E8F0; padding-top: 28px; text-align: center;">
      <span style="font-size: 0.78rem; font-weight: 700; color: #64748B; text-transform: uppercase; letter-spacing: 1px; display: block; margin-bottom: 14px;">
        Direct Automated Data Exporters Included
      </span>
      <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; font-weight: 700; font-size: 0.85rem; color: #0F172A;">
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">NEC Software</span>
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">Capita Housing</span>
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">Civica Horizon</span>
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">Keystone</span>
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">MRI Software</span>
      </div>
    </div>

  </div>
</div>

<!-- Orbital Trajectory Animations & Transforms -->
<style>
  /* FRONT/EARTH POSITION: Centered, Focused & Full Color */
  .is-front-earth {
    transform: translate3d(0, 0, 40px) scale(1) rotateY(0deg) !important;
    z-index: 10 !important;
    opacity: 1 !important;
    filter: grayscale(0%) blur(0px) !important;
    pointer-events: auto !important;
  }

  /* BACK/MOON POSITION: Offset right, scaled down & greyed out */
  .is-back-moon {
    transform: translate3d(120px, 20px, -120px) scale(0.85) rotateY(-18deg) !important;
    z-index: 1 !important;
    opacity: 0.45 !important;
    filter: grayscale(80%) blur(0.8px) !important;
    pointer-events: auto !important;
  }

  .is-back-moon:hover {
    opacity: 0.75 !important;
    filter: grayscale(20%) blur(0px) !important;
  }

  /* 360 ORBITAL SWEEP KEYFRAMES */
  @keyframes moonOrbitToFront {
    0% { transform: translate3d(120px, 20px, -120px) scale(0.85) rotateY(-18deg); opacity: 0.45; }
    50% { transform: translate3d(-180px, 0px, -40px) scale(0.9) rotateY(-90deg); opacity: 0.7; }
    100% { transform: translate3d(0, 0, 40px) scale(1) rotateY(-360deg); opacity: 1; }
  }

  @keyframes earthOrbitToBack {
    0% { transform: translate3d(0, 0, 40px) scale(1) rotateY(0deg); opacity: 1; }
    50% { transform: translate3d(200px, 20px, -60px) scale(0.88) rotateY(180deg); opacity: 0.6; }
    100% { transform: translate3d(120px, 20px, -120px) scale(0.85) rotateY(342deg); opacity: 0.45; }
  }

  .anim-orbit-to-front {
    animation: moonOrbitToFront 0.8s cubic-bezier(0.34, 1.25, 0.64, 1) forwards !important;
  }

  .anim-orbit-to-back {
    animation: earthOrbitToBack 0.8s cubic-bezier(0.34, 1.25, 0.64, 1) forwards !important;
  }
</style>

<script>
  var currentTier = 'enterprise';

  function orbitToTier(targetTier) {
    if (currentTier === targetTier) return;

    var cardEnt = document.getElementById('card-enterprise');
    var cardCust = document.getElementById('card-custom');
    var pillEnt = document.getElementById('pill-enterprise');
    var pillCust = document.getElementById('pill-custom');

    cardEnt.classList.remove('anim-orbit-to-front', 'anim-orbit-to-back');
    cardCust.classList.remove('anim-orbit-to-front', 'anim-orbit-to-back');
    void cardEnt.offsetWidth; // Force Reflow

    if (targetTier === 'enterprise') {
      cardEnt.className = 'ps-3d-card is-front-earth anim-orbit-to-front';
      cardCust.className = 'ps-3d-card is-back-moon anim-orbit-to-back';

      cardEnt.style.borderColor = '#2563EB';
      cardCust.style.borderColor = '#E2E8F0';

      pillEnt.style.background = '#2563EB';
      pillEnt.style.color = '#FFFFFF';
      pillEnt.style.boxShadow = '0 4px 12px rgba(37,99,235,0.3)';

      pillCust.style.background = 'transparent';
      pillCust.style.color = '#64748B';
      pillCust.style.boxShadow = 'none';
    } else {
      cardCust.className = 'ps-3d-card is-front-earth anim-orbit-to-front';
      cardEnt.className = 'ps-3d-card is-back-moon anim-orbit-to-back';

      cardCust.style.borderColor = '#0F172A';
      cardEnt.style.borderColor = '#E2E8F0';

      pillCust.style.background = '#0F172A';
      pillCust.style.color = '#FFFFFF';
      pillCust.style.boxShadow = '0 4px 12px rgba(15,23,42,0.3)';

      pillEnt.style.background = 'transparent';
      pillEnt.style.color = '#64748B';
      pillEnt.style.boxShadow = 'none';
    }

    currentTier = targetTier;
  }
</script>
{% endraw %}