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

<section class="w3-padding-64" style="background-color: #FAFAFA; color: #18181B; border-bottom: 1px solid #E4E4E7; min-height: 80vh;">
  <div class="w3-content" style="max-width: 540px; padding: 0 16px;">
    <div style="text-align: center; margin-bottom: 32px;">
      <span class="ps-badge-platinum" style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.8rem; padding: 6px 14px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 20px; display: inline-block; margin-bottom: 16px;">ENTERPRISE LICENSING</span>
      <h1 style="font-size: clamp(1.8rem, 3.5vw, 2.6rem); font-weight: 800; color: #09090B; margin: 0 0 12px 0; letter-spacing: -0.02em;">Simple, All-Inclusive Enterprise Pricing</h1>
      <p style="font-size: 1rem; color: #52525B; max-width: 580px; margin: 0 auto; line-height: 1.5;">Select a plan tier below to rotate between options.</p>
    </div>
    
    <!-- Top Pill Controls -->
    <div style="display: flex; justify-content: center; margin-bottom: 32px;">
      <div style="background: #E4E4E7; padding: 4px; border-radius: 30px; display: inline-flex; gap: 4px;">
        <button id="pill-enterprise" onclick="flipPricingCard('enterprise')" style="padding: 8px 24px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: #2563EB; color: #FFFFFF; box-shadow: 0 2px 8px rgba(37,99,235,0.3); transition: all 0.25s ease;">Enterprise</button>
        <button id="pill-custom" onclick="flipPricingCard('custom')" style="padding: 8px 24px; border-radius: 24px; border: none; font-weight: 700; font-size: 0.88rem; cursor: pointer; background: transparent; color: #52525B; transition: all 0.25s ease;">Custom</button>
      </div>
    </div>

    <!-- 3D Perspective Flip Container -->
    <div style="perspective: 1200px; width: 100%; min-height: 520px;">
      <div id="flip-card-inner" style="position: relative; width: 100%; height: 100%; transition: transform 0.7s cubic-bezier(0.4, 0.2, 0.2, 1); transform-style: preserve-3d;">
        
        <!-- FRONT SIDE: Enterprise Card -->
        <div style="position: absolute; width: 100%; backface-visibility: hidden; -webkit-backface-visibility: hidden; background: #FFFFFF; border: 1px solid #E4E4E7; border-radius: 16px; overflow: hidden; box-shadow: 0 12px 32px rgba(0,0,0,0.06); display: flex; flex-direction: column; justify-content: space-between;">
          <div>
            <div style="background: #2563EB; padding: 18px 16px; text-align: center; color: #FFFFFF;"><h2 style="font-size: 1.5rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Enterprise</h2></div>
            <div style="text-align: center; padding: 20px 16px 16px 16px; border-bottom: 1px solid #F1F5F9;">
              <div style="font-size: 2.8rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">£175</div>
              <div style="font-size: 0.88rem; font-weight: 700; color: #2563EB;">Price Per App</div>
              <div style="font-size: 0.78rem; color: #71717A; margin-top: 2px;">per user / month</div>
            </div>
            <div style="padding: 18px 16px;">
              <div style="font-size: 0.72rem; font-weight: 700; color: #2563EB; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">AVAILABLE APPS</div>
              <div style="margin-bottom: 14px; display: flex; align-items: flex-start; gap: 8px;">
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
            <div style="background: #ECFEFF; border-top: 1px solid #CFFAFE; padding: 18px 16px;">
              <div style="font-size: 0.72rem; font-weight: 700; color: #0891B2; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">ENTERPRISE FEATURES</div>
              <ul style="list-style: none; padding: 0; margin: 0; font-size: 0.82rem; color: #155E75; display: flex; flex-direction: column; gap: 8px;">
                <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Segmented Databases</li>
                <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> External Image Gallery</li>
                <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Advanced Desktop Mode</li>
                <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> PDF Reports</li>
                <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Direct CSV Export (NEC, Capita, Civica, MRI)</li>
                <li><i class="fa-solid fa-star" style="color: #06B6D4; margin-right: 6px;"></i> Assisted Imports</li>
              </ul>
            </div>
          </div>
          <div style="padding: 16px; background: #ECFEFF; border-top: 1px solid #CFFAFE;">
            <a href="/enquiry.htm" class="ps-header-cta" style="display: block; width: 100%; padding: 10px 16px; font-size: 0.88rem; box-sizing: border-box; text-align: center; margin: 0;">Book Demo <i class="fa-solid fa-arrow-right" style="margin-left: 4px;"></i></a>
          </div>
        </div>

        <!-- BACK SIDE: Custom Bespoke Card (Rotated 180deg) -->
        <div style="position: absolute; width: 100%; backface-visibility: hidden; -webkit-backface-visibility: hidden; transform: rotateY(180deg); background: #FFFFFF; border: 1px solid #E4E4E7; border-radius: 16px; overflow: hidden; box-shadow: 0 12px 32px rgba(0,0,0,0.06); display: flex; flex-direction: column; justify-content: space-between;">
          <div>
            <div style="background: #0F172A; padding: 18px 16px; text-align: center; color: #FFFFFF;"><h2 style="font-size: 1.5rem; font-weight: 800; margin: 0; color: #FFFFFF; letter-spacing: -0.01em;">Custom</h2></div>
            <div style="text-align: center; padding: 20px 16px 16px 16px; border-bottom: 1px solid #F1F5F9;">
              <div style="font-size: 2.8rem; font-weight: 800; color: #09090B; line-height: 1; margin-bottom: 4px;">Quote</div>
              <div style="font-size: 0.88rem; font-weight: 700; color: #38BDF8;">Custom Development</div>
              <div style="font-size: 0.78rem; color: #71717A; margin-top: 2px;">tailored operational scope</div>
            </div>
            <div style="padding: 18px 16px;">
              <div style="font-size: 0.72rem; font-weight: 700; color: #0F172A; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">BESPOKE SERVICES</div>
              <div style="margin-bottom: 14px; display: flex; align-items: flex-start; gap: 8px;">
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
            <div style="background: #F8FAFC; border-top: 1px solid #E2E8F0; padding: 18px 16px;">
              <div style="font-size: 0.72rem; font-weight: 700; color: #475569; text-transform: uppercase; letter-spacing: 0.5px; margin-bottom: 12px;">BESPOKE INCLUSIONS</div>
              <ul style="list-style: none; padding: 0; margin: 0; font-size: 0.82rem; color: #334155; display: flex; flex-direction: column; gap: 8px;">
                <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Custom Defect Scoring Logic</li>
                <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Tailored Client PDF Templates</li>
                <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Custom Database Schema Mapping</li>
                <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Dedicated UK Development Lead</li>
                <li><i class="fa-solid fa-star" style="color: #38BDF8; margin-right: 6px;"></i> Continuous Regulatory Updates</li>
              </ul>
            </div>
          </div>
          <div style="padding: 16px; background: #F8FAFC; border-top: 1px solid #E2E8F0;">
            <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="display: block; width: 100%; padding: 10px 16px; font-size: 0.88rem; box-sizing: border-box; text-align: center; margin: 0; border-color: #CBD5E1; color: #09090B !important;">Talk to Us <i class="fa-solid fa-comments" style="margin-left: 4px; color: #2563EB;"></i></a>
          </div>
        </div>

      </div>
    </div>
  </div>
</section>

<script>
  function flipPricingCard(type) {
    var inner = document.getElementById('flip-card-inner');
    var pillEnt = document.getElementById('pill-enterprise');
    var pillCust = document.getElementById('pill-custom');

    if (type === 'enterprise') {
      inner.style.transform = 'rotateY(0deg)';
      
      pillEnt.style.background = '#2563EB';
      pillEnt.style.color = '#FFFFFF';
      pillEnt.style.boxShadow = '0 2px 8px rgba(37,99,235,0.3)';

      pillCust.style.background = 'transparent';
      pillCust.style.color = '#52525B';
      pillCust.style.boxShadow = 'none';
    } else {
      inner.style.transform = 'rotateY(180deg)';

      pillCust.style.background = '#0F172A';
      pillCust.style.color = '#FFFFFF';
      pillCust.style.boxShadow = '0 2px 8px rgba(15,23,42,0.3)';

      pillEnt.style.background = 'transparent';
      pillEnt.style.color = '#52525B';
      pillEnt.style.boxShadow = 'none';
    }
  }
</script>