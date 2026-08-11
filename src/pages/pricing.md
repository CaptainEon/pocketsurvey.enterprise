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
<div style="background: radial-gradient(circle at 50% 0%, #F1F5F9 0%, #FAFAFA 70%); color: #0F172A; padding: 48px 16px 80px 16px; min-height: 80vh; box-sizing: border-box; overflow: hidden;">
  <div style="max-width: 900px; margin: 0 auto; width: 100%;">
    
    <!-- Minimalist Premium Header -->
    <div style="text-align: center; margin-bottom: 32px;">
      <span style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 16px; letter-spacing: 1px; text-transform: uppercase;">
        Enterprise Licensing
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 800; color: #09090B; margin: 0 0 10px 0; letter-spacing: -0.03em;">
        Simple, All-Inclusive Pricing
      </h1>
      <p style="font-size: 1.05rem; color: #64748B; max-width: 540px; margin: 0 auto; line-height: 1.5;">
        Select an enterprise tier below to orbit between standard compliance suites and bespoke app development.
      </p>
    </div>

    <!-- High-End Pill Toggle -->
    <div style="display: flex; justify-content: center; margin-bottom: 40px;">
      <div style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 5px; border-radius: 40px; display: inline-flex; gap: 6px; box-shadow: 0 4px 16px rgba(0,0,0,0.03);">
        <button id="pill-enterprise" onclick="orbitToTier('enterprise')" style="padding: 10px 28px; border-radius: 30px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: #2563EB; color: #FFFFFF; box-shadow: 0 4px 12px rgba(37,99,235,0.3); transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);">
          Enterprise Standard
        </button>
        <button id="pill-custom" onclick="orbitToTier('custom')" style="padding: 10px 28px; border-radius: 30px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: transparent; color: #64748B; transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);">
          Custom Bespoke
        </button>
      </div>
    </div>

    <!-- Orbit Stage: Single Premium Card Container with 3D Orbital Axis Animation -->
    <div style="perspective: 1000px; width: 100%; max-width: 620px; margin: 0 auto 48px auto;">
      <div id="ps-orbit-stage" style="background: #FFFFFF; border: 1px solid #E2E8F0; border-radius: 24px; overflow: hidden; box-shadow: 0 20px 50px rgba(0, 0, 0, 0.06); transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1); transform-style: preserve-3d; position: relative;">
        
        <!-- CARD VIEW 1: ENTERPRISE -->
        <div id="view-enterprise" style="display: block;">
          <!-- Top Gradient Bar -->
          <div style="height: 6px; background: linear-gradient(90deg, #2563EB, #38BDF8);"></div>
          
          <div style="padding: 32px 32px 24px 32px; text-align: center; border-bottom: 1px solid #F1F5F9; position: relative;">
            <span style="position: absolute; top: 20px; right: 24px; background: #EFF6FF; color: #2563EB; font-size: 0.72rem; font-weight: 700; padding: 4px 10px; border-radius: 12px; border: 1px solid rgba(37,99,235,0.2);">
              Most Popular
            </span>
            <div style="color: #2563EB; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 1.2px; margin-bottom: 8px;">
              Enterprise Plan
            </div>
            <div style="display: flex; align-items: baseline; justify-content: center; gap: 6px; margin-bottom: 4px;">
              <span style="font-size: 3.4rem; font-weight: 800; color: #0F172A; letter-spacing: -0.03em; line-height: 1;">£175</span>
              <span style="font-size: 0.92rem; color: #64748B; font-weight: 500;">/ user / month</span>
            </div>
            <div style="font-size: 0.82rem; color: #059669; font-weight: 600; margin-top: 6px;">
              <i class="fa-solid fa-circle-check" style="margin-right: 4px;"></i> Free Setup, Onboarding &amp; Dedicated Support
            </div>
          </div>

          <div style="padding: 28px 32px;">
            <div style="font-size: 0.75rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 16px;">
              Included Compliance Frameworks &amp; Apps:
            </div>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 14px; margin-bottom: 24px;">
              <div style="background: #F8FAFC; border: 1px solid #E2E8F0; padding: 12px 16px; border-radius: 12px; display: flex; align-items: flex-start; gap: 10px;">
                <i class="fa-solid fa-house-building" style="color: #2563EB; font-size: 1rem; margin-top: 2px;"></i>
                <div>
                  <div style="font-weight: 700; color: #0F172A; font-size: 0.9rem;">Housing Stock Condition</div>
                  <div style="font-size: 0.78rem; color: #64748B;">Decent Homes, SHQS, WHQS &amp; HHSRS</div>
                </div>
              </div>

              <div style="background: #F8FAFC; border: 1px solid #E2E8F0; padding: 12px 16px; border-radius: 12px; display: flex; align-items: flex-start; gap: 10px;">
                <i class="fa-solid fa-screwdriver-wrench" style="color: #2563EB; font-size: 1rem; margin-top: 2px;"></i>
                <div>
                  <div style="font-weight: 700; color: #0F172A; font-size: 0.9rem;">Commercial Planned PPM</div>
                  <div style="font-size: 0.78rem; color: #64748B;">Standard RICS, SFG20 &amp; NHS 6-Facets</div>
                </div>
              </div>
            </div>

            <!-- Enterprise Platform Highlights -->
            <div style="background: rgba(236, 254, 255, 0.6); border: 1px solid #CFFAFE; border-radius: 14px; padding: 20px;">
              <div style="font-size: 0.75rem; font-weight: 700; color: #0891B2; text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 12px;">
                Enterprise Platform Features:
              </div>
              <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 10px; font-size: 0.85rem; color: #155E75; font-weight: 500;">
                <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Segmented Database Controls</div>
                <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> External Cloud Image Gallery</div>
                <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Advanced Desktop Management</div>
                <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Instant PDF Client Reports</div>
                <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Automated System CSV Exports</div>
                <div><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Assisted Historic Data Imports</div>
              </div>
            </div>
          </div>

          <div style="padding: 24px 32px; background: #F8FAFC; border-top: 1px solid #E2E8F0; text-align: center;">
            <a href="/enquiry.htm" class="ps-header-cta" style="display: block; width: 100%; padding: 14px 24px; font-size: 0.98rem; box-sizing: border-box; text-align: center; margin: 0; box-shadow: 0 4px 14px rgba(37,99,235,0.25);">
              Book Enterprise Demo <i class="fa-solid fa-arrow-right" style="margin-left: 8px;"></i>
            </a>
          </div>
        </div>

        <!-- CARD VIEW 2: CUSTOM BESPOKE -->
        <div id="view-custom" style="display: none;">
          <!-- Top Gradient Bar -->
          <div style="height: 6px; background: linear-gradient(90deg, #38BDF8, #8B5CF6);"></div>

          <div style="padding: 32px 32px 24px 32px; text-align: center; border-bottom: 1px solid #F1F5F9; position: relative;">
            <span style="position: absolute; top: 20px; right: 24px; background: #F3E8FF; color: #7C3AED; font-size: 0.72rem; font-weight: 700; padding: 4px 10px; border-radius: 12px; border: 1px solid rgba(124,58,237,0.2);">
              Tailored Scope
            </span>
            <div style="color: #7C3AED; font-size: 0.8rem; font-weight: 700; text-transform: uppercase; letter-spacing: 1.2px; margin-bottom: 8px;">
              Custom Studio Plan
            </div>
            <div style="display: flex; align-items: baseline; justify-content: center; gap: 6px; margin-bottom: 4px;">
              <span style="font-size: 3.4rem; font-weight: 800; color: #0F172A; letter-spacing: -0.03em; line-height: 1;">Custom</span>
            </div>
            <div style="font-size: 0.82rem; color: #64748B; font-weight: 500; margin-top: 6px;">
              Tailored quote based on operational requirements
            </div>
          </div>

          <div style="padding: 28px 32px;">
            <div style="font-size: 0.75rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 16px;">
              Bespoke Engineering Capabilities:
            </div>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 14px; margin-bottom: 24px;">
              <div style="background: #F8FAFC; border: 1px solid #E2E8F0; padding: 12px 16px; border-radius: 12px; display: flex; align-items: flex-start; gap: 10px;">
                <i class="fa-solid fa-code" style="color: #7C3AED; font-size: 1rem; margin-top: 2px;"></i>
                <div>
                  <div style="font-weight: 700; color: #0F172A; font-size: 0.9rem;">Tailored Inspection Forms</div>
                  <div style="font-size: 0.78rem; color: #64748B;">Custom form logic, branching &amp; scoring</div>
                </div>
              </div>

              <div style="background: #F8FAFC; border: 1px solid #E2E8F0; padding: 12px 16px; border-radius: 12px; display: flex; align-items: flex-start; gap: 10px;">
                <i class="fa-solid fa-database" style="color: #7C3AED; font-size: 1rem; margin-top: 2px;"></i>
                <div>
                  <div style="font-weight: 700; color: #0F172A; font-size: 0.9rem;">Proprietary Schema Exporters</div>
                  <div style="font-size: 0.78rem; color: #64748B;">Tailored CSV, XML, or JSON legacy exports</div>
                </div>
              </div>
            </div>

            <!-- Custom Studio Features -->
            <div style="background: rgba(243, 232, 255, 0.6); border: 1px solid #E9D5FF; border-radius: 14px; padding: 20px;">
              <div style="font-size: 0.75rem; font-weight: 700; color: #6B21A8; text-transform: uppercase; letter-spacing: 0.8px; margin-bottom: 12px;">
                All Enterprise Features, Plus:
              </div>
              <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 10px; font-size: 0.85rem; color: #581C87; font-weight: 500;">
                <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 8px;"></i> Tailored Defect Scoring Matrices</div>
                <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 8px;"></i> Custom Corporate PDF Templates</div>
                <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 8px;"></i> Direct Database Schema Mapping</div>
                <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 8px;"></i> Dedicated UK Technical Lead</div>
                <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 8px;"></i> Custom API Integrations</div>
                <div><i class="fa-solid fa-star" style="color: #A855F7; margin-right: 8px;"></i> Continuous Regulatory Updates</div>
              </div>
            </div>
          </div>

          <div style="padding: 24px 32px; background: #F8FAFC; border-top: 1px solid #E2E8F0; text-align: center;">
            <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="display: block; width: 100%; padding: 14px 24px; font-size: 0.98rem; box-sizing: border-box; text-align: center; margin: 0; border-color: #CBD5E1; color: #09090B !important;">
              Discuss Custom Development <i class="fa-solid fa-comments" style="margin-left: 8px; color: #2563EB;"></i>
            </a>
          </div>
        </div>

      </div>
    </div>

    <!-- Integration Badges Footer -->
    <div style="border-top: 1px solid #E2E8F0; padding-top: 32px; text-align: center;">
      <span style="font-size: 0.78rem; font-weight: 700; color: #64748B; text-transform: uppercase; letter-spacing: 1px; display: block; margin-bottom: 16px;">
        Direct Automated Data Exporters Included
      </span>
      <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 12px; font-weight: 700; font-size: 0.88rem; color: #0F172A;">
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 8px 18px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.02);">NEC Software</span>
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 8px 18px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.02);">Capita Housing</span>
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 8px 18px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.02);">Civica Horizon</span>
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 8px 18px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.02);">Keystone</span>
        <span style="background: #FFFFFF; border: 1px solid #E2E8F0; padding: 8px 18px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.02);">MRI Software</span>
      </div>
    </div>

  </div>
</div>

<!-- 3D Orbit Axis Keyframe Animations -->
<style>
  @keyframes psOrbitalAxisSpin {
    0% { transform: rotateY(0deg) scale(1); }
    50% { transform: rotateY(90deg) scale(0.92); opacity: 0.2; }
    100% { transform: rotateY(0deg) scale(1); opacity: 1; }
  }

  .is-orbit-spinning {
    animation: psOrbitalAxisSpin 0.5s cubic-bezier(0.4, 0, 0.2, 1);
  }
</style>

<script>
  var currentTier = 'enterprise';

  function orbitToTier(targetTier) {
    if (currentTier === targetTier) return;

    var stage = document.getElementById('ps-orbit-stage');
    var viewEnt = document.getElementById('view-enterprise');
    var viewCust = document.getElementById('view-custom');
    var pillEnt = document.getElementById('pill-enterprise');
    var pillCust = document.getElementById('pill-custom');

    // Trigger 3D Orbital Axis Spin
    stage.classList.remove('is-orbit-spinning');
    void stage.offsetWidth; // Force Reflow
    stage.classList.add('is-orbit-spinning');

    // Swap content mid-point through the spin (250ms)
    setTimeout(function() {
      if (targetTier === 'enterprise') {
        viewEnt.style.display = 'block';
        viewCust.style.display = 'none';

        pillEnt.style.background = '#2563EB';
        pillEnt.style.color = '#FFFFFF';
        pillEnt.style.boxShadow = '0 4px 12px rgba(37,99,235,0.3)';

        pillCust.style.background = 'transparent';
        pillCust.style.color = '#64748B';
        pillCust.style.boxShadow = 'none';
      } else {
        viewEnt.style.display = 'none';
        viewCust.style.display = 'block';

        pillCust.style.background = '#0F172A';
        pillCust.style.color = '#FFFFFF';
        pillCust.style.boxShadow = '0 4px 12px rgba(15,23,42,0.3)';

        pillEnt.style.background = 'transparent';
        pillEnt.style.color = '#64748B';
        pillEnt.style.boxShadow = 'none';
      }
      currentTier = targetTier;
    }, 250);
  }
</script>
{% endraw %}