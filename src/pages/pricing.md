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
<style>
  /* Base Container Layout */
  .ps-pricing-wrapper {
    background: radial-gradient(circle at 50% 0%, #F1F5F9 0%, #FAFAFA 70%);
    color: #0F172A;
    padding: 48px 16px 80px 16px;
    min-height: 80vh;
    box-sizing: border-box;
  }
  .ps-pricing-container {
    max-width: 920px;
    margin: 0 auto;
    width: 100%;
  }

  /* Flex Cards Layout Stage */
  .ps-cards-stage {
    display: flex;
    justify-content: center;
    align-items: stretch;
    gap: 24px;
    margin-bottom: 48px;
  }

  /* Individual Card Styling */
  .ps-pricing-card {
    flex: 1 1 400px;
    max-width: 440px;
    background: #FFFFFF;
    border-radius: 20px;
    overflow: hidden;
    box-sizing: border-box;
    cursor: pointer;
    transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1), opacity 0.4s ease, border-color 0.4s ease, box-shadow 0.4s ease, filter 0.4s ease;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  /* Active vs Inactive Card States */
  .ps-pricing-card.is-active {
    transform: scale(1.03);
    opacity: 1;
    filter: grayscale(0%);
    box-shadow: 0 20px 40px rgba(37, 99, 235, 0.12);
    z-index: 2;
  }
  .ps-pricing-card.is-inactive {
    transform: scale(0.94);
    opacity: 0.5;
    filter: grayscale(70%);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.04);
    z-index: 1;
  }
  .ps-pricing-card.is-inactive:hover {
    opacity: 0.8;
    filter: grayscale(20%);
  }

  /* Mobile Responsive Adjustment */
  @media (max-width: 768px) {
    .ps-cards-stage {
      flex-direction: column;
      align-items: center;
    }
    .ps-pricing-card {
      width: 100%;
      max-width: 100%;
    }
    .ps-pricing-card.is-active,
    .ps-pricing-card.is-inactive {
      transform: none;
      opacity: 1;
      filter: none;
    }
  }
</style>

<div class="ps-pricing-wrapper">
  <div class="ps-pricing-container">
    
    <!-- Header Section -->
    <div style="text-align: center; margin-bottom: 32px;">
      <span style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 12px; letter-spacing: 1px; text-transform: uppercase;">
        ENTERPRISE LICENSING
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.6rem); font-weight: 800; color: #09090B; margin: 0 0 8px 0; letter-spacing: -0.03em;">
        Simple, All-Inclusive Pricing
      </h1>
      <p style="font-size: 1rem; color: #64748B; max-width: 540px; margin: 0 auto; line-height: 1.5;">
        Select an enterprise tier below to toggle between standard compliance suites and custom app development.
      </p>
    </div>

    <!-- High-End Pill Toggle -->
    <div style="display: flex; justify-content: center; margin-bottom: 40px;">
      <div style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 4px; border-radius: 40px; display: inline-flex; gap: 6px; box-shadow: 0 4px 16px rgba(0,0,0,0.03);">
        <button id="pill-enterprise" onclick="orbitToTier('enterprise')" style="padding: 10px 28px; border-radius: 30px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: #2563EB; color: #FFFFFF; box-shadow: 0 4px 12px rgba(37,99,235,0.3); transition: all 0.3s ease;">
          Enterprise Standard
        </button>
        <button id="pill-custom" onclick="orbitToTier('custom')" style="padding: 10px 28px; border-radius: 30px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: transparent; color: #64748B; transition: all 0.3s ease;">
          Custom Bespoke
        </button>
      </div>
    </div>

    <!-- Pricing Cards Stage -->
    <div class="ps-cards-stage">
      
      <!-- CARD 1: ENTERPRISE -->
      <div id="card-enterprise" onclick="orbitToTier('enterprise')" class="ps-pricing-card is-active" style="border: 2px solid #2563EB;">
        <div>
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
        </div>

        <div style="padding: 18px 24px; background: #F8FAFC; border-top: 1px solid #E2E8F0; text-align: center;">
          <a href="/enquiry.htm" class="ps-header-cta" style="display: block; width: 100%; padding: 12px 20px; font-size: 0.9rem; box-sizing: border-box; text-align: center; margin: 0; box-shadow: 0 4px 12px rgba(37,99,235,0.25);">
            Book Enterprise Demo <i class="fa-solid fa-arrow-right" style="margin-left: 6px;"></i>
          </a>
        </div>
      </div>

      <!-- CARD 2: CUSTOM -->
      <div id="card-custom" onclick="orbitToTier('custom')" class="ps-pricing-card is-inactive" style="border: 1px solid #E2E8F0;">
        <div>
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
        </div>

        <div style="padding: 18px 24px; background: #F8FAFC; border-top: 1px solid #E2E8F0; text-align: center;">
          <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="display: block; width: 100%; padding: 12px 20px; font-size: 0.9rem; box-sizing: border-box; text-align: center; margin: 0; border-color: #CBD5E1; color: #09090B !important;">
            Discuss Custom App <i class="fa-solid fa-comments" style="margin-left: 6px; color: #2563EB;"></i>
          </a>
        </div>
      </div>

    </div>

    <!-- Supported Systems Integration Footer Badges -->
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

<script>
  var currentTier = 'enterprise';

  function orbitToTier(targetTier) {
    if (currentTier === targetTier) return;

    var cardEnt = document.getElementById('card-enterprise');
    var cardCust = document.getElementById('card-custom');
    var pillEnt = document.getElementById('pill-enterprise');
    var pillCust = document.getElementById('pill-custom');

    if (targetTier === 'enterprise') {
      cardEnt.className = 'ps-pricing-card is-active';
      cardCust.className = 'ps-pricing-card is-inactive';

      cardEnt.style.borderColor = '#2563EB';
      cardCust.style.borderColor = '#E2E8F0';

      pillEnt.style.background = '#2563EB';
      pillEnt.style.color = '#FFFFFF';
      pillEnt.style.boxShadow = '0 4px 12px rgba(37,99,235,0.3)';

      pillCust.style.background = 'transparent';
      pillCust.style.color = '#64748B';
      pillCust.style.boxShadow = 'none';
    } else {
      cardCust.className = 'ps-pricing-card is-active';
      cardEnt.className = 'ps-pricing-card is-inactive';

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