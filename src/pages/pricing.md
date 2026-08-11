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

<div style="background-color: #FAFAFA; color: #18181B; padding: 48px 16px 80px 16px; min-height: 80vh; box-sizing: border-box; overflow: hidden;">
  <div style="max-width: 800px; margin: 0 auto; width: 100%;">
    
    <!-- Minimal Header -->
    <div style="text-align: center; margin-bottom: 24px;">
      <span class="ps-badge-platinum" style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.8rem; padding: 4px 12px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 20px; display: inline-block; margin-bottom: 12px;">ENTERPRISE LICENSING</span>
      <h1 style="font-size: clamp(1.8rem, 3.5vw, 2.5rem); font-weight: 800; color: #09090B; margin: 0 0 8px 0; letter-spacing: -0.02em;">Simple, All-Inclusive Enterprise Pricing</h1>
      <p style="font-size: 0.98rem; color: #52525B; margin: 0 auto; line-height: 1.5;">Select a plan tier below to orbit between pricing options.</p>
    </div>

    <!-- Top Pill Controls -->
    <div style="display: flex; justify-content: center; margin-bottom: 32px;">
      <div style="background: #E4E4E7; padding: 4px; border-radius: 30px; display: inline-flex; gap: 4px;">
        <button id="pill-enterprise" onclick="orbitToTier('enterprise')" style="padding: 8px 24px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: #2563EB; color: #FFFFFF; box-shadow: 0 2px 8px rgba(37,99,235,0.3); transition: all 0.25s ease;">Enterprise</button>
        <button id="pill-custom" onclick="orbitToTier('custom')" style="padding: 8px 24px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: transparent; color: #52525B; transition: all 0.25s ease;">Custom</button>
      </div>
    </div>

    <!-- 3D Orbit Perspective Stage -->
    <div style="perspective: 1200px; width: 100%; position: relative; min-height: 580px; display: flex; justify-content: center; align-items: flex-start;">
      
      <!-- CARD 1: ENTERPRISE (Starts Front & Active) -->
      <div id="card-enterprise" onclick="orbitToTier('enterprise')" class="ps-orbit-card is-front-active" style="position: absolute; width: 100%; max-width: 480px; background: #FFFFFF; border: 2px solid #2563EB; border-radius: 16px; overflow: hidden; box-shadow: 0 20px 40px rgba(37, 99, 235, 0.15); box-sizing: border-box; cursor: pointer; transition: all 0.7s cubic-bezier(0.34, 1.35, 0.64, 1); transform-origin: center center;">
        <div style="background: #2563EB; padding: 18px 20px; text-align: center; color: #FFFFFF;">
          <h2 style="font-size: 1.6rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Enterprise</h2>
        </div>
        <div style="text-align: center; padding: 22px 20px 16px 20px; border-bottom: 1px solid #F1F5F9;">
          <div style="font-size: 2.8rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">£175</div>
          <div style="font-size: 0.9rem; font-weight: 700; color: #2563EB;">Price Per App</div>
          <div style="font-size: 0.78rem; color: #71717A; margin-top: 2px;">per user / month</div>
        </div>
        <div style="padding: 20px;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #2563EB; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">AVAILABLE APPS</div>
          <div style="margin-bottom: 12px; display: flex; align-items: flex-start; gap: 8px;">
            <i class="fa-solid fa-check" style="color: #2563EB; font-size: 1rem; margin-top: 2px;"></i>
            <div>
              <div style="font-weight: 700; color: #0F172A; font-size: 0.9rem;">Housing Stock Condition</div>
              <div style="font-size: 0.78rem; color: #64748B; margin-top: 2px;">(Decent Homes, SHQS, WHQS)</div>
            </div>
          </div>
          <div style="margin-bottom: 8px; display: flex; align-items: flex-start; gap: 8px;">
            <i class="fa-solid fa-check" style="color: #2563EB; font-size: 1rem; margin-top: 2px;"></i>
            <div>
              <div style="font-weight: 700; color: #0F172A; font-size: 0.9rem;">Commercial Planned Maintenance</div>
              <div style="font-size: 0.78rem; color: #64748B; margin-top: 2px;">(Standard, BCIS, SFG20, 6 Facet)</div>
            </div>
          </div>
        </div>
        <div style="background: #ECFEFF; border-top: 1px solid #CFFAFE; padding: 18px 20px;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #0891B2; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 10px;">ENTERPRISE FEATURES</div>
          <ul style="list-style: none; padding: 0; margin: 0; font-size: 0.82rem; color: #155E75; display: flex; flex-direction: column; gap: 6px;">
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Segmented Databases</li>
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> External Image Gallery</li>
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Advanced Desktop Mode</li>
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> PDF Reports</li>
            <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Direct CSV Export (NEC, Capita, Civica, MRI)</li>
          </ul>
        </div>
        <div style="padding: 16px 20px; background: #ECFEFF; border-top: 1px solid #CFFAFE;">
          <a href="/enquiry.htm" class="ps-header-cta" style="display: block; width: 100%; padding: 10px 16px; font-size: 0.9rem; box-sizing: border-box; text-align: center; margin: 0;">Book Demo <i class="fa-solid fa-arrow-right" style="margin-left: 4px;"></i></a>
        </div>
      </div>

      <!-- CARD 2: CUSTOM (Starts Back & Inactive/Greyed) -->
      <div id="card-custom" onclick="orbitToTier('custom')" class="ps-orbit-card is-back-inactive" style="position: absolute; width: 100%; max-width: 480px; background: #FFFFFF; border: 1px solid #E4E4E7; border-radius: 16px; overflow: hidden; box-shadow: 0 10px 24px rgba(0,0,0,0.04); box-sizing: border-box; cursor: pointer; transition: all 0.7s cubic-bezier(0.34, 1.35, 0.64, 1); transform-origin: center center;">
        <div style="background: #0F172A; padding: 18px 20px; text-align: center; color: #FFFFFF;">
          <h2 style="font-size: 1.6rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Custom</h2>
        </div>
        <div style="text-align: center; padding: 22px 20px 16px 20px; border-bottom: 1px solid #F1F5F9;">
          <div style="font-size: 2.8rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">Quote</div>
          <div style="font-size: 0.9rem; font-weight: 700; color: #38BDF8;">Custom Development</div>
          <div style="font-size: 0.78rem; color: #71717A; margin-top: 2px;">tailored operational scope</div>
        </div>
        <div style="padding: 20px;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">BESPOKE SERVICES</div>
          <div style="margin-bottom: 12px; display: flex; align-items: flex-start; gap: 8px;">
            <i class="fa-solid fa-check" style="color: #0F172A; font-size: 1rem; margin-top: 2px;"></i>
            <div>
              <div style="font-weight: 700; color: #0F172A; font-size: 0.9rem;">Tailored Mobile Inspection Forms</div>
              <div style="font-size: 0.78rem; color: #64748B; margin-top: 2px;">(Custom form logic, branching &amp; scoring)</div>
            </div>
          </div>
          <div style="margin-bottom: 8px; display: flex; align-items: flex-start; gap: 8px;">
            <i class="fa-solid fa-check" style="color: #0F172A; font-size: 1rem; margin-top: 2px;"></i>
            <div>
              <div style="font-weight: 700; color: #0F172A; font-size: 0.9rem;">Proprietary Schema Exporters</div>
              <div style="font-size: 0.78rem; color: #64748B; margin-top: 2px;">(Custom CSV, XML, JSON exports)</div>
            </div>
          </div>
        </div>
        <div style="background: #F8FAFC; border-top: 1px solid #E2E8F0; padding: 18px 20px;">
          <div style="font-size: 0.72rem; font-weight: 700; color: #475569; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 10px;">BESPOKE INCLUSIONS</div>
          <ul style="list-style: none; padding: 0; margin: 0; font-size: 0.82rem; color: #334155; display: flex; flex-direction: column; gap: 6px;">
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Custom Defect Scoring Logic</li>
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Tailored Client PDF Templates</li>
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Custom Database Schema Mapping</li>
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Dedicated UK Development Lead</li>
            <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Continuous Regulatory Updates</li>
          </ul>
        </div>
        <div style="padding: 16px 20px; background: #F8FAFC; border-top: 1px solid #E2E8F0;">
          <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="display: block; width: 100%; padding: 10px 16px; font-size: 0.9rem; box-sizing: border-box; text-align: center; margin: 0; border-color: #CBD5E1; color: #09090B !important;">Talk to Us <i class="fa-solid fa-comments" style="margin-left: 4px; color: #2563EB;"></i></a>
        </div>
      </div>

    </div>

    <!-- Supported System Integrations Footer Badges -->
    <div style="border-top: 1px solid #E2E8F0; margin-top: 20px; padding-top: 24px; text-align: center; clear: both;">
      <span style="font-size: 0.78rem; font-weight: 700; color: #64748B; text-transform: uppercase; letter-spacing: 1px; display: block; margin-bottom: 14px;">Direct Automated Data Exporters Included</span>
      <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; font-weight: 700; font-size: 0.85rem; color: #0F172A;">
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">NEC Software</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">Capita Housing</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">Civica Horizon</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">Keystone</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 6px 14px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">MRI Software</span>
      </div>
    </div>

  </div>
</div>

<!-- Orbital 3D Axis Transforms & Keyframes -->
<style>
  /* FRONT / ACTIVE CARD POSITIONING */
  .is-front-active {
    transform: translate3d(0, 0, 80px) scale(1) rotateY(0deg);
    z-index: 10;
    opacity: 1;
    filter: grayscale(0%) blur(0px);
    pointer-events: auto;
  }

  /* BACK / INACTIVE CARD POSITIONING (Greyed & Behind) */
  .is-back-inactive {
    transform: translate3d(60px, 30px, -120px) scale(0.85) rotateY(-18deg);
    z-index: 1;
    opacity: 0.45;
    filter: grayscale(80%) blur(1px);
    pointer-events: auto;
  }

  .is-back-inactive:hover {
    opacity: 0.7;
    filter: grayscale(40%) blur(0px);
  }

  /* ORBIT SWAP KEYFRAMES (360° Arc Swing) */
  @keyframes orbitSwapToFront {
    0% { transform: translate3d(60px, 30px, -120px) scale(0.85) rotateY(-18deg); opacity: 0.45; }
    50% { transform: translate3d(-180px, 0, 0px) scale(0.92) rotateY(-90deg); opacity: 0.75; }
    100% { transform: translate3d(0, 0, 80px) scale(1) rotateY(-360deg); opacity: 1; }
  }

  @keyframes orbitSwapToBack {
    0% { transform: translate3d(0, 0, 80px) scale(1) rotateY(0deg); opacity: 1; }
    50% { transform: translate3d(180px, 30px, -60px) scale(0.88) rotateY(180deg); opacity: 0.6; }
    100% { transform: translate3d(60px, 30px, -120px) scale(0.85) rotateY(342deg); opacity: 0.45; }
  }

  .anim-orbit-front {
    animation: orbitSwapToFront 0.75s cubic-bezier(0.34, 1.25, 0.64, 1) forwards;
  }

  .anim-orbit-back {
    animation: orbitSwapToBack 0.75s cubic-bezier(0.34, 1.25, 0.64, 1) forwards;
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

    // Remove existing animation classes
    cardEnt.classList.remove('anim-orbit-front', 'anim-orbit-back');
    cardCust.classList.remove('anim-orbit-front', 'anim-orbit-back');
    void cardEnt.offsetWidth; // Force Reflow

    if (targetTier === 'enterprise') {
      // Bring Enterprise forward, push Custom back
      cardEnt.className = 'ps-orbit-card is-front-active anim-orbit-front';
      cardCust.className = 'ps-orbit-card is-back-inactive anim-orbit-back';

      cardEnt.style.borderColor = '#2563EB';
      cardCust.style.borderColor = '#E4E4E7';

      pillEnt.style.background = '#2563EB';
      pillEnt.style.color = '#FFFFFF';
      pillEnt.style.boxShadow = '0 2px 8px rgba(37,99,235,0.3)';

      pillCust.style.background = 'transparent';
      pillCust.style.color = '#52525B';
      pillCust.style.boxShadow = 'none';
    } else {
      // Bring Custom forward, push Enterprise back
      cardCust.className = 'ps-orbit-card is-front-active anim-orbit-front';
      cardEnt.className = 'ps-orbit-card is-back-inactive anim-orbit-back';

      cardCust.style.borderColor = '#0F172A';
      cardEnt.style.borderColor = '#E4E4E7';

      pillCust.style.background = '#0F172A';
      pillCust.style.color = '#FFFFFF';
      pillCust.style.boxShadow = '0 2px 8px rgba(15,23,42,0.3)';

      pillEnt.style.background = 'transparent';
      pillEnt.style.color = '#52525B';
      pillEnt.style.boxShadow = 'none';
    }

    currentTier = targetTier;
  }
</script>