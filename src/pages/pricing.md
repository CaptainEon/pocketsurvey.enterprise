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

<section class="w3-padding-32" style="background-color: #FAFAFA; color: #18181B; border-bottom: 1px solid #E4E4E7; min-height: 80vh;">
  <div class="w3-content" style="max-width: 1100px; padding: 0 20px;">
    
    <!-- Header -->
    <div style="text-align: center; margin-bottom: 28px;">
      <span class="ps-badge-platinum" style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.8rem; padding: 4px 12px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 20px; display: inline-block; margin-bottom: 12px;">ENTERPRISE LICENSING</span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 800; color: #09090B; margin: 0 0 8px 0; letter-spacing: -0.02em;">Simple, All-Inclusive Enterprise Pricing</h1>
      <p style="font-size: 1.05rem; color: #52525B; max-width: 600px; margin: 0 auto; line-height: 1.5;">Select a plan tier below to trigger 3D axis rotation.</p>
    </div>

    <!-- Top Pill Controls -->
    <div style="display: flex; justify-content: center; margin-bottom: 32px;">
      <div style="background: #E4E4E7; padding: 4px; border-radius: 30px; display: inline-flex; gap: 4px;">
        <button id="pill-enterprise" onclick="spinCardToActive('enterprise')" style="padding: 8px 28px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.9rem; cursor: pointer; background: #2563EB; color: #FFFFFF; box-shadow: 0 2px 8px rgba(37,99,235,0.3); transition: all 0.25s ease;">Enterprise</button>
        <button id="pill-custom" onclick="spinCardToActive('custom')" style="padding: 8px 28px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.9rem; cursor: pointer; background: transparent; color: #52525B; transition: all 0.25s ease;">Custom</button>
      </div>
    </div>

    <!-- Dual Cards Container (3D Perspective Side-by-Side) -->
    <div style="perspective: 1200px; width: 100%;">
      <div class="w3-row-padding" style="margin: 0 -12px;">
        
        <!-- CARD 1: ENTERPRISE -->
        <div class="w3-half" style="margin-bottom: 24px; padding: 0 12px;">
          <div id="card-enterprise" class="ps-axis-card is-active-card" style="background: #FFFFFF; border: 2px solid #2563EB; border-radius: 16px; overflow: hidden; box-shadow: 0 16px 36px rgba(37, 99, 235, 0.12); display: flex; flex-direction: column; justify-content: space-between; transition: all 0.6s cubic-bezier(0.34, 1.56, 0.64, 1); transform-origin: center center;">
            <div>
              <div style="background: #2563EB; padding: 20px 24px; text-align: center; color: #FFFFFF;">
                <h2 style="font-size: 1.6rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Enterprise</h2>
              </div>
              <div style="text-align: center; padding: 24px 24px 18px 24px; border-bottom: 1px solid #F1F5F9;">
                <div style="font-size: 3rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">£175</div>
                <div style="font-size: 0.95rem; font-weight: 700; color: #2563EB;">Price Per App</div>
                <div style="font-size: 0.8rem; color: #71717A; margin-top: 2px;">per user / month</div>
              </div>
              <div style="padding: 24px 28px;">
                <div style="font-size: 0.75rem; font-weight: 700; color: #2563EB; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 16px;">AVAILABLE APPS</div>
                <div style="margin-bottom: 16px; display: flex; align-items: flex-start; gap: 10px;">
                  <i class="fa-solid fa-check" style="color: #2563EB; font-size: 1.1rem; margin-top: 2px;"></i>
                  <div>
                    <div style="font-weight: 700; color: #0F172A; font-size: 0.95rem;">Housing Stock Condition</div>
                    <div style="font-size: 0.82rem; color: #64748B; margin-top: 2px;">(Decent Homes, SHQS, WHQS)</div>
                  </div>
                </div>
                <div style="margin-bottom: 16px; display: flex; align-items: flex-start; gap: 10px;">
                  <i class="fa-solid fa-check" style="color: #2563EB; font-size: 1.1rem; margin-top: 2px;"></i>
                  <div>
                    <div style="font-weight: 700; color: #0F172A; font-size: 0.95rem;">Commercial Planned Maintenance</div>
                    <div style="font-size: 0.82rem; color: #64748B; margin-top: 2px;">(Standard, BCIS, SFG20, 6 Facet)</div>
                  </div>
                </div>
              </div>
              <div style="background: #ECFEFF; border-top: 1px solid #CFFAFE; padding: 20px 28px;">
                <div style="font-size: 0.75rem; font-weight: 700; color: #0891B2; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">ENTERPRISE FEATURES</div>
                <ul style="list-style: none; padding: 0; margin: 0; font-size: 0.85rem; color: #155E75; display: flex; flex-direction: column; gap: 8px;">
                  <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Segmented Databases</li>
                  <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> External Image Gallery</li>
                  <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Advanced Desktop Mode</li>
                  <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> PDF Reports</li>
                  <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Direct CSV Exports (NEC, Capita, Civica)</li>
                </ul>
              </div>
            </div>
            <div style="padding: 20px 28px; background: #ECFEFF; border-top: 1px solid #CFFAFE;">
              <a href="/enquiry.htm" class="ps-header-cta" style="display: block; width: 100%; padding: 12px 20px; font-size: 0.95rem; box-sizing: border-box; text-align: center; margin: 0;">Book Demo <i class="fa-solid fa-arrow-right" style="margin-left: 6px;"></i></a>
            </div>
          </div>
        </div>

        <!-- CARD 2: CUSTOM -->
        <div class="w3-half" style="margin-bottom: 24px; padding: 0 12px;">
          <div id="card-custom" class="ps-axis-card is-inactive-card" style="background: #FFFFFF; border: 1px solid #E4E4E7; border-radius: 16px; overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,0.04); display: flex; flex-direction: column; justify-content: space-between; transition: all 0.6s cubic-bezier(0.34, 1.56, 0.64, 1); transform-origin: center center;">
            <div>
              <div style="background: #0F172A; padding: 20px 24px; text-align: center; color: #FFFFFF;">
                <h2 style="font-size: 1.6rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Custom</h2>
              </div>
              <div style="text-align: center; padding: 24px 24px 18px 24px; border-bottom: 1px solid #F1F5F9;">
                <div style="font-size: 3rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">Quote</div>
                <div style="font-size: 0.95rem; font-weight: 700; color: #38BDF8;">Custom Development</div>
                <div style="font-size: 0.8rem; color: #71717A; margin-top: 2px;">tailored operational scope</div>
              </div>
              <div style="padding: 24px 28px;">
                <div style="font-size: 0.75rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 16px;">BESPOKE SERVICES</div>
                <div style="margin-bottom: 16px; display: flex; align-items: flex-start; gap: 10px;">
                  <i class="fa-solid fa-check" style="color: #0F172A; font-size: 1.1rem; margin-top: 2px;"></i>
                  <div>
                    <div style="font-weight: 700; color: #0F172A; font-size: 0.95rem;">Tailored Mobile Inspection Forms</div>
                    <div style="font-size: 0.82rem; color: #64748B; margin-top: 2px;">(Custom form logic, branching &amp; scoring)</div>
                  </div>
                </div>
                <div style="margin-bottom: 16px; display: flex; align-items: flex-start; gap: 10px;">
                  <i class="fa-solid fa-check" style="color: #0F172A; font-size: 1.1rem; margin-top: 2px;"></i>
                  <div>
                    <div style="font-weight: 700; color: #0F172A; font-size: 0.95rem;">Proprietary Schema Exporters</div>
                    <div style="font-size: 0.82rem; color: #64748B; margin-top: 2px;">(Custom CSV, XML, JSON exports)</div>
                  </div>
                </div>
              </div>
              <div style="background: #F8FAFC; border-top: 1px solid #E2E8F0; padding: 20px 28px;">
                <div style="font-size: 0.75rem; font-weight: 700; color: #475569; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">BESPOKE INCLUSIONS</div>
                <ul style="list-style: none; padding: 0; margin: 0; font-size: 0.85rem; color: #334155; display: flex; flex-direction: column; gap: 8px;">
                  <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Custom Defect Scoring Logic</li>
                  <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Tailored Client PDF Templates</li>
                  <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Custom Schema Mapping</li>
                  <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Dedicated UK Development Lead</li>
                  <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Continuous Regulatory Updates</li>
                </ul>
              </div>
            </div>
            <div style="padding: 20px 28px; background: #F8FAFC; border-top: 1px solid #E2E8F0;">
              <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="display: block; width: 100%; padding: 12px 20px; font-size: 0.95rem; box-sizing: border-box; text-align: center; margin: 0; border-color: #CBD5E1; color: #09090B !important;">Talk to Us <i class="fa-solid fa-comments" style="margin-left: 6px; color: #2563EB;"></i></a>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- Supported System Integrations Footer -->
    <div style="border-top: 1px solid #E2E8F0; margin-top: 24px; padding-top: 32px; text-align: center;">
      <span style="font-size: 0.8rem; font-weight: 700; color: #64748B; text-transform: uppercase; letter-spacing: 1px; display: block; margin-bottom: 16px;">Direct Automated Data Exporters Included</span>
      <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 12px; font-weight: 700; font-size: 0.88rem; color: #0F172A;">
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">NEC Software</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">Capita Housing</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">Civica Horizon</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">Keystone</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">MRI Software</span>
      </div>
    </div>

  </div>
</section>

<!-- Sun-Axis Spin Keyframes & Card States -->
<style>
  /* Active Focused Card State */
  .is-active-card {
    transform: scale(1.02) rotateY(0deg) translateZ(20px);
    opacity: 1;
    filter: blur(0px);
  }

  /* Inactive Receded Card State */
  .is-inactive-card {
    transform: scale(0.95) rotateY(-12deg) translateZ(-30px);
    opacity: 0.65;
    filter: blur(0.5px);
  }

  /* Axis Spin Animation Keyframes */
  @keyframes psSunAxisSpin {
    0% { transform: scale(1) rotateY(0deg); }
    50% { transform: scale(0.85) rotateY(180deg) rotateX(10deg); opacity: 0.4; }
    100% { transform: scale(1.02) rotateY(360deg); opacity: 1; }
  }

  .is-axis-spinning {
    animation: psSunAxisSpin 0.7s cubic-bezier(0.34, 1.56, 0.64, 1);
  }
</style>

<script>
  function spinCardToActive(target) {
    var cardEnt = document.getElementById('card-enterprise');
    var cardCust = document.getElementById('card-custom');
    var pillEnt = document.getElementById('pill-enterprise');
    var pillCust = document.getElementById('pill-custom');

    if (target === 'enterprise') {
      // Trigger Spin
      cardEnt.classList.remove('is-axis-spinning');
      void cardEnt.offsetWidth; // Force Reflow
      cardEnt.classList.add('is-axis-spinning');

      // Set Focused States
      cardEnt.className = 'ps-axis-card is-active-card is-axis-spinning';
      cardCust.className = 'ps-axis-card is-inactive-card';
      cardEnt.style.borderColor = '#2563EB';
      cardCust.style.borderColor = '#E4E4E7';

      pillEnt.style.background = '#2563EB';
      pillEnt.style.color = '#FFFFFF';
      pillEnt.style.boxShadow = '0 2px 8px rgba(37,99,235,0.3)';

      pillCust.style.background = 'transparent';
      pillCust.style.color = '#52525B';
      pillCust.style.boxShadow = 'none';
    } else {
      // Trigger Spin
      cardCust.classList.remove('is-axis-spinning');
      void cardCust.offsetWidth; // Force Reflow
      cardCust.classList.add('is-axis-spinning');

      // Set Focused States
      cardCust.className = 'ps-axis-card is-active-card is-axis-spinning';
      cardEnt.className = 'ps-axis-card is-inactive-card';
      cardCust.style.borderColor = '#0F172A';
      cardEnt.style.borderColor = '#E4E4E7';

      pillCust.style.background = '#0F172A';
      pillCust.style.color = '#FFFFFF';
      pillCust.style.boxShadow = '0 2px 8px rgba(15,23,42,0.3)';

      pillEnt.style.background = 'transparent';
      pillEnt.style.color = '#52525B';
      pillEnt.style.boxShadow = 'none';
    }
  }
</script>