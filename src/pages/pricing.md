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
  <div class="w3-content" style="max-width: 900px; padding: 0 20px;">
    
    <!-- Header -->
    <div style="text-align: center; margin-bottom: 24px;">
      <span class="ps-badge-platinum" style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.8rem; padding: 4px 12px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 20px; display: inline-block; margin-bottom: 12px;">ENTERPRISE LICENSING</span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 800; color: #09090B; margin: 0 0 8px 0; letter-spacing: -0.02em;">Simple, All-Inclusive Enterprise Pricing</h1>
      <p style="font-size: 1.05rem; color: #52525B; max-width: 600px; margin: 0 auto; line-height: 1.5;">Select a plan tier below to rotate between options.</p>
    </div>

    <!-- Top Pill Toggle -->
    <div style="display: flex; justify-content: center; margin-bottom: 28px;">
      <div style="background: #E4E4E7; padding: 4px; border-radius: 30px; display: inline-flex; gap: 4px;">
        <button id="pill-enterprise" onclick="spinToTier('enterprise')" style="padding: 8px 28px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.9rem; cursor: pointer; background: #2563EB; color: #FFFFFF; box-shadow: 0 2px 8px rgba(37,99,235,0.3); transition: all 0.25s ease;">Enterprise</button>
        <button id="pill-custom" onclick="spinToTier('custom')" style="padding: 8px 28px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.9rem; cursor: pointer; background: transparent; color: #52525B; transition: all 0.25s ease;">Custom</button>
      </div>
    </div>

    <!-- Centered Spin Card Container (Expanded to 720px) -->
    <div style="max-width: 720px; margin: 0 auto 48px auto; perspective: 1000px;">
      <div id="ps-spin-card" style="background: #FFFFFF; border: 1px solid #E4E4E7; border-radius: 16px; overflow: hidden; box-shadow: 0 12px 36px rgba(0,0,0,0.06); display: flex; flex-direction: column; justify-content: space-between; transform-style: preserve-3d;">
        
        <!-- Enterprise Content View -->
        <div id="view-enterprise" style="display: block;">
          <div>
            <div style="background: #2563EB; padding: 20px 24px; text-align: center; color: #FFFFFF;"><h2 style="font-size: 1.6rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Enterprise</h2></div>
            <div style="text-align: center; padding: 24px 24px 18px 24px; border-bottom: 1px solid #F1F5F9;">
              <div style="font-size: 3rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">£175</div>
              <div style="font-size: 0.95rem; font-weight: 700; color: #2563EB;">Price Per App</div>
              <div style="font-size: 0.8rem; color: #71717A; margin-top: 2px;">per user / month</div>
            </div>
            <div style="padding: 24px 32px;">
              <div style="font-size: 0.75rem; font-weight: 700; color: #2563EB; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 16px;">AVAILABLE APPS</div>
              
              <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 16px; margin-bottom: 8px;">
                <div style="display: flex; align-items: flex-start; gap: 10px;">
                  <i class="fa-solid fa-check" style="color: #2563EB; font-size: 1.1rem; margin-top: 2px;"></i>
                  <div>
                    <div style="font-weight: 700; color: #0F172A; font-size: 0.95rem;">Housing Stock Condition</div>
                    <div style="font-size: 0.82rem; color: #64748B; margin-top: 2px;">(Decent Homes, SHQS, WHQS)</div>
                  </div>
                </div>

                <div style="display: flex; align-items: flex-start; gap: 10px;">
                  <i class="fa-solid fa-check" style="color: #2563EB; font-size: 1.1rem; margin-top: 2px;"></i>
                  <div>
                    <div style="font-weight: 700; color: #0F172A; font-size: 0.95rem;">Commercial Planned Maintenance</div>
                    <div style="font-size: 0.82rem; color: #64748B; margin-top: 2px;">(Standard, BCIS, SFG20, 6 Facet)</div>
                  </div>
                </div>
              </div>

            </div>
            <div style="background: #ECFEFF; border-top: 1px solid #CFFAFE; padding: 24px 32px;">
              <div style="font-size: 0.75rem; font-weight: 700; color: #0891B2; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 14px;">ENTERPRISE FEATURES</div>
              <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 10px;">
                <div style="font-size: 0.88rem; color: #155E75;"><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Segmented Databases</div>
                <div style="font-size: 0.88rem; color: #155E75;"><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> External Image Gallery</div>
                <div style="font-size: 0.88rem; color: #155E75;"><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Advanced Desktop Mode</div>
                <div style="font-size: 0.88rem; color: #155E75;"><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> PDF Reports</div>
                <div style="font-size: 0.88rem; color: #155E75;"><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> CSV Export (NEC, Capita, Civica)</div>
                <div style="font-size: 0.88rem; color: #155E75;"><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 8px;"></i> Assisted Imports</div>
              </div>
            </div>
          </div>
          <div style="padding: 20px 32px; background: #ECFEFF; border-top: 1px solid #CFFAFE;">
            <a href="/enquiry.htm" class="ps-header-cta" style="display: block; width: 100%; padding: 12px 20px; font-size: 0.95rem; box-sizing: border-box; text-align: center; margin: 0;">Book Demo <i class="fa-solid fa-arrow-right" style="margin-left: 6px;"></i></a>
          </div>
        </div>

        <!-- Custom Content View -->
        <div id="view-custom" style="display: none;">
          <div>
            <div style="background: #0F172A; padding: 20px 24px; text-align: center; color: #FFFFFF;"><h2 style="font-size: 1.6rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Custom</h2></div>
            <div style="text-align: center; padding: 24px 24px 18px 24px; border-bottom: 1px solid #F1F5F9;">
              <div style="font-size: 3rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">Quote</div>
              <div style="font-size: 0.95rem; font-weight: 700; color: #38BDF8;">Custom Development</div>
              <div style="font-size: 0.8rem; color: #71717A; margin-top: 2px;">tailored operational scope</div>
            </div>
            <div style="padding: 24px 32px;">
              <div style="font-size: 0.75rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 16px;">BESPOKE SERVICES</div>
              
              <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 16px; margin-bottom: 8px;">
                <div style="display: flex; align-items: flex-start; gap: 10px;">
                  <i class="fa-solid fa-check" style="color: #0F172A; font-size: 1.1rem; margin-top: 2px;"></i>
                  <div>
                    <div style="font-weight: 700; color: #0F172A; font-size: 0.95rem;">Tailored Mobile Inspection Forms</div>
                    <div style="font-size: 0.82rem; color: #64748B; margin-top: 2px;">(Custom form logic, branching &amp; scoring)</div>
                  </div>
                </div>

                <div style="display: flex; align-items: flex-start; gap: 10px;">
                  <i class="fa-solid fa-check" style="color: #0F172A; font-size: 1.1rem; margin-top: 2px;"></i>
                  <div>
                    <div style="font-weight: 700; color: #0F172A; font-size: 0.95rem;">Proprietary Schema Exporters</div>
                    <div style="font-size: 0.82rem; color: #64748B; margin-top: 2px;">(Custom CSV, XML, JSON exports)</div>
                  </div>
                </div>
              </div>

            </div>
            <div style="background: #F8FAFC; border-top: 1px solid #E2E8F0; padding: 24px 32px;">
              <div style="font-size: 0.75rem; font-weight: 700; color: #475569; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 14px;">BESPOKE INCLUSIONS</div>
              <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 10px;">
                <div style="font-size: 0.88rem; color: #334155;"><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Custom Defect Scoring Logic</div>
                <div style="font-size: 0.88rem; color: #334155;"><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Tailored Client PDF Templates</div>
                <div style="font-size: 0.88rem; color: #334155;"><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Custom Schema Mapping</div>
                <div style="font-size: 0.88rem; color: #334155;"><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Dedicated UK Tech Lead</div>
                <div style="font-size: 0.88rem; color: #334155;"><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 8px;"></i> Continuous Regulatory Updates</div>
              </div>
            </div>
          </div>
          <div style="padding: 20px 32px; background: #F8FAFC; border-top: 1px solid #E2E8F0;">
            <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="display: block; width: 100%; padding: 12px 20px; font-size: 0.95rem; box-sizing: border-box; text-align: center; margin: 0; border-color: #CBD5E1; color: #09090B !important;">Talk to Us <i class="fa-solid fa-comments" style="margin-left: 6px; color: #2563EB;"></i></a>
          </div>
        </div>

      </div>
    </div>

    <!-- Supported System Integrations (Fills Out the Bottom Whitespace) -->
    <div style="border-top: 1px solid #E2E8F0; padding-top: 36px; text-align: center;">
      <span style="font-size: 0.8rem; font-weight: 700; color: #64748B; text-transform: uppercase; letter-spacing: 1px; display: block; margin-bottom: 16px;">Direct Automated Data Exporters Included</span>
      <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 16px; font-weight: 700; font-size: 0.9rem; color: #0F172A;">
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">NEC Software</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">Capita Housing</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">Civica Horizon</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">Keystone</span>
        <span style="background: #FFFFFF; border: 1px solid #E4E4E7; padding: 8px 16px; border-radius: 8px;">MRI Software</span>
      </div>
    </div>

  </div>
</section>

<!-- Smooth Axis Spin Keyframes & Toggle Logic -->
<style>
  @keyframes psYAxisSpin {
    0% { transform: rotateY(0deg); }
    50% { transform: rotateY(90deg); }
    100% { transform: rotateY(0deg); }
  }
  .is-spinning {
    animation: psYAxisSpin 0.5s cubic-bezier(0.4, 0, 0.2, 1);
  }
</style>

<script>
  var currentActiveTier = 'enterprise';

  function spinToTier(targetTier) {
    if (currentActiveTier === targetTier) return;
    
    var card = document.getElementById('ps-spin-card');
    var viewEnt = document.getElementById('view-enterprise');
    var viewCust = document.getElementById('view-custom');
    var pillEnt = document.getElementById('pill-enterprise');
    var pillCust = document.getElementById('pill-custom');

    // Trigger Y-Axis Spin Animation
    card.classList.remove('is-spinning');
    void card.offsetWidth; // Force Reflow
    card.classList.add('is-spinning');

    // Swap content at the 90-degree mid-point (250ms)
    setTimeout(function() {
      if (targetTier === 'enterprise') {
        viewEnt.style.display = 'block';
        viewCust.style.display = 'none';

        pillEnt.style.background = '#2563EB';
        pillEnt.style.color = '#FFFFFF';
        pillEnt.style.boxShadow = '0 2px 8px rgba(37,99,235,0.3)';

        pillCust.style.background = 'transparent';
        pillCust.style.color = '#52525B';
        pillCust.style.boxShadow = 'none';
      } else {
        viewEnt.style.display = 'none';
        viewCust.style.display = 'block';

        pillCust.style.background = '#0F172A';
        pillCust.style.color = '#FFFFFF';
        pillCust.style.boxShadow = '0 2px 8px rgba(15,23,42,0.3)';

        pillEnt.style.background = 'transparent';
        pillEnt.style.color = '#52525B';
        pillEnt.style.boxShadow = 'none';
      }
      currentActiveTier = targetTier;
    }, 250);
  }
</script>