---
_schema: default
title: Sample Mobile Surveying Reports | PocketSurvey
seo:
  page_description: >-
    Explore sample PDF reports generated automatically by PocketSurvey. Inspect Stock Condition, Planned Maintenance, Damp & Mould, and HHSRS sample outputs.
  canonical_url:
  featured_image:
  featured_image_alt:
  author_twitter_handle:
  open_graph_type:
  no_index: false
layout: layouts/layout.html
permalink: /reports/
eleventyExcludeFromCollections: false
templateEngineOverride: njk, html
---

<div style="background: #F8FAFC; color: #0F172A; padding: 48px 16px 80px 16px; min-height: 85vh; box-sizing: border-box; width: 100%;">
  <div style="max-width: 960px; margin: 0 auto; width: 100%; box-sizing: border-box;">
    
    <!-- Header Section -->
    <div style="text-align: center; margin-bottom: 48px;">
      <span style="background: rgba(26, 115, 232, 0.08); color: #1A73E8; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(26, 115, 232, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 12px; letter-spacing: 1px; text-transform: uppercase;">
        AUTOMATED DELIVERABLES
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 800; color: #09090B; margin: 0 0 10px 0; letter-spacing: -0.03em;">
        Client-Ready Sample Reports
      </h1>
      <p style="font-size: 1.05rem; color: #5F6368; max-width: 620px; margin: 0 auto; line-height: 1.5;">
        Explore instant PDF deliverables generated directly from site surveys without post-survey manual editing or transcription.
      </p>
    </div>

    <!-- 2x2 REPORT GRID CONTAINER -->
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(380px, 1fr)); gap: 24px; width: 100%; box-sizing: border-box;">
      
      <!-- CARD 1: HOUSING STOCK CONDITION (BLUE ACCENT) -->
      <div class="ps-report-card" style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 14px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.04); transition: all 0.25s ease; display: flex; flex-direction: column; justify-content: space-between; position: relative;">
        <div>
          <!-- Minimal Slim Header Banner -->
          <div onclick="openReportModal('https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf', 'Housing Stock Condition Sample Report')" style="position: relative; width: 100%; background: #F1F5F9; border-bottom: 3px solid #1A73E8; cursor: pointer; padding: 18px 20px; box-sizing: border-box;">
            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px;">
              <span style="background: #E8F0FE; color: #1A73E8; font-size: 0.68rem; font-weight: 700; padding: 4px 10px; border-radius: 6px; text-transform: uppercase; letter-spacing: 0.5px;">HOUSING STOCK</span>
              <i class="fa-solid fa-file-pdf" style="font-size: 1.2rem; color: #1A73E8;"></i>
            </div>
            <div style="font-weight: 800; font-size: 1.1rem; color: #202124; line-height: 1.3;">Stock Condition &amp; Decent Homes</div>
            
            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(26, 115, 232, 0.95); display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.25s ease;">
              <span style="background: #FFFFFF; color: #1A73E8; font-weight: 800; font-size: 0.82rem; padding: 8px 18px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Preview PDF</span>
            </div>
          </div>

          <div style="padding: 20px;">
            <p style="font-size: 0.85rem; color: #5F6368; margin: 0 0 14px 0; line-height: 1.5;">Includes elemental repair costs, 30-year component lifecycle projections, and full Decent Homes compliance tables.</p>
            <div style="display: flex; gap: 12px; font-size: 0.75rem; color: #5F6368; font-weight: 600;">
              <span><i class="fa-solid fa-layer-group" style="color: #1A73E8; margin-right: 4px;"></i> 30-Yr CapEx</span>
              <span><i class="fa-solid fa-check-double" style="color: #34A853; margin-right: 4px;"></i> Decent Homes</span>
            </div>
          </div>
        </div>

        <div style="padding: 12px 20px; background: #FAFAFA; border-top: 1px solid #E8EAED; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf', 'Housing Stock Condition Sample Report')" style="background: transparent; border: none; padding: 0; color: #1A73E8; font-weight: 700; font-size: 0.82rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #5F6368; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- CARD 2: COMMERCIAL PLANNED MAINTENANCE (GREEN ACCENT) -->
      <div class="ps-report-card" style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 14px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.04); transition: all 0.25s ease; display: flex; flex-direction: column; justify-content: space-between; position: relative;">
        <div>
          <!-- Minimal Slim Header Banner -->
          <div onclick="openReportModal('https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf', 'Commercial Planned Maintenance (PPM) Sample Report')" style="position: relative; width: 100%; background: #F1F5F9; border-bottom: 3px solid #34A853; cursor: pointer; padding: 18px 20px; box-sizing: border-box;">
            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px;">
              <span style="background: #E6F4EA; color: #1E8E3E; font-size: 0.68rem; font-weight: 700; padding: 4px 10px; border-radius: 6px; text-transform: uppercase; letter-spacing: 0.5px;">COMMERCIAL &amp; PPM</span>
              <i class="fa-solid fa-screwdriver-wrench" style="font-size: 1.2rem; color: #34A853;"></i>
            </div>
            <div style="font-weight: 800; font-size: 1.1rem; color: #202124; line-height: 1.3;">Planned Maintenance (PPM) Report</div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(52, 168, 83, 0.95); display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.25s ease;">
              <span style="background: #FFFFFF; color: #34A853; font-weight: 800; font-size: 0.82rem; padding: 8px 18px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Preview PDF</span>
            </div>
          </div>

          <div style="padding: 20px;">
            <p style="font-size: 0.85rem; color: #5F6368; margin: 0 0 14px 0; line-height: 1.5;">Structured building fabric, mechanical, and electrical maintenance schedules adhering to RICS and SFG20 frameworks.</p>
            <div style="display: flex; gap: 12px; font-size: 0.75rem; color: #5F6368; font-weight: 600;">
              <span><i class="fa-solid fa-gear" style="color: #34A853; margin-right: 4px;"></i> SFG20 Tasks</span>
              <span><i class="fa-solid fa-chart-pie" style="color: #1A73E8; margin-right: 4px;"></i> Asset Register</span>
            </div>
          </div>
        </div>

        <div style="padding: 12px 20px; background: #FAFAFA; border-top: 1px solid #E8EAED; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf', 'Commercial Planned Maintenance (PPM) Sample Report')" style="background: transparent; border: none; padding: 0; color: #1A73E8; font-weight: 700; font-size: 0.82rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #5F6368; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- CARD 3: DAMP & MOULD SURVEY (AMBER ACCENT) -->
      <div class="ps-report-card" style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 14px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.04); transition: all 0.25s ease; display: flex; flex-direction: column; justify-content: space-between; position: relative;">
        <div>
          <!-- Minimal Slim Header Banner -->
          <div onclick="openReportModal('https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf', 'Damp & Mould Survey Sample Report')" style="position: relative; width: 100%; background: #F1F5F9; border-bottom: 3px solid #F29900; cursor: pointer; padding: 18px 20px; box-sizing: border-box;">
            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px;">
              <span style="background: #FEF7E0; color: #B06000; font-size: 0.68rem; font-weight: 700; padding: 4px 10px; border-radius: 6px; text-transform: uppercase; letter-spacing: 0.5px;">RISK ASSESSMENT</span>
              <i class="fa-solid fa-droplet-slash" style="font-size: 1.2rem; color: #F29900;"></i>
            </div>
            <div style="font-weight: 800; font-size: 1.1rem; color: #202124; line-height: 1.3;">Damp &amp; Mould Inspection Report</div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(242, 153, 0, 0.95); display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.25s ease;">
              <span style="background: #FFFFFF; color: #B06000; font-weight: 800; font-size: 0.82rem; padding: 8px 18px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Preview PDF</span>
            </div>
          </div>

          <div style="padding: 20px;">
            <p style="font-size: 0.85rem; color: #5F6368; margin: 0 0 14px 0; line-height: 1.5;">Structured mobile assessment for damp ingress, condensation risk, room-by-room mould severity, and remedial action tracking.</p>
            <div style="display: flex; gap: 12px; font-size: 0.75rem; color: #5F6368; font-weight: 600;">
              <span><i class="fa-solid fa-wind" style="color: #1A73E8; margin-right: 4px;"></i> Ventilation Audit</span>
              <span><i class="fa-solid fa-camera" style="color: #34A853; margin-right: 4px;"></i> Photo Evidence</span>
            </div>
          </div>
        </div>

        <div style="padding: 12px 20px; background: #FAFAFA; border-top: 1px solid #E8EAED; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf', 'Damp & Mould Survey Sample Report')" style="background: transparent; border: none; padding: 0; color: #1A73E8; font-weight: 700; font-size: 0.82rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #5F6368; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- CARD 4: HHSRS HAZARD ASSESSMENT (RED ACCENT) -->
      <div class="ps-report-card" style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 14px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.04); transition: all 0.25s ease; display: flex; flex-direction: column; justify-content: space-between; position: relative;">
        <div>
          <!-- Minimal Slim Header Banner -->
          <div onclick="openReportModal('https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf', 'HHSRS Housing Health & Safety Sample Report')" style="position: relative; width: 100%; background: #F1F5F9; border-bottom: 3px solid #EA4335; cursor: pointer; padding: 18px 20px; box-sizing: border-box;">
            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 8px;">
              <span style="background: #FCE8E6; color: #C5221F; font-size: 0.68rem; font-weight: 700; padding: 4px 10px; border-radius: 6px; text-transform: uppercase; letter-spacing: 0.5px;">STATUTORY REPORT</span>
              <i class="fa-solid fa-shield-halved" style="font-size: 1.2rem; color: #EA4335;"></i>
            </div>
            <div style="font-weight: 800; font-size: 1.1rem; color: #202124; line-height: 1.3;">HHSRS Health &amp; Safety Report</div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(234, 67, 53, 0.95); display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.25s ease;">
              <span style="background: #FFFFFF; color: #EA4335; font-weight: 800; font-size: 0.82rem; padding: 8px 18px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Preview PDF</span>
            </div>
          </div>

          <div style="padding: 20px;">
            <p style="font-size: 0.85rem; color: #5F6368; margin: 0 0 14px 0; line-height: 1.5;">Evaluates 21 statutory housing health and safety hazards, assigning risk likelihood scores and urgent remediation plans.</p>
            <div style="display: flex; gap: 12px; font-size: 0.75rem; color: #5F6368; font-weight: 600;">
              <span><i class="fa-solid fa-triangle-exclamation" style="color: #F29900; margin-right: 4px;"></i> Hazard Scoring</span>
              <span><i class="fa-solid fa-house-medical" style="color: #EA4335; margin-right: 4px;"></i> Category 1 &amp; 2</span>
            </div>
          </div>
        </div>

        <div style="padding: 12px 20px; background: #FAFAFA; border-top: 1px solid #E8EAED; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf', 'HHSRS Housing Health & Safety Sample Report')" style="background: transparent; border: none; padding: 0; color: #1A73E8; font-weight: 700; font-size: 0.82rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #5F6368; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

    </div>

    <!-- Bottom Banner CTA -->
    <div style="margin-top: 56px; background: #202124; border-radius: 14px; padding: 36px 28px; text-align: center; color: #FFFFFF;">
      <h2 style="font-size: 1.55rem; font-weight: 800; margin: 0 0 8px 0; color: #FFFFFF;">Need Your Firm's Custom Branding on Reports?</h2>
      <p style="font-size: 0.95rem; color: #9AA0A6; max-width: 560px; margin: 0 auto 24px auto;">We configure custom executive summaries, corporate logos, disclaimers, and CSV data exporters to match your exact business requirements.</p>
      <a href="/enquiry.htm" class="ps-header-cta" style="display: inline-block; padding: 12px 28px; font-size: 0.9rem; background: #1A73E8;">Book Technical Consult <i class="fa-solid fa-arrow-right" style="margin-left: 6px;"></i></a>
    </div>

  </div>
</div>

<!-- Modal Document Viewer Popup Container -->
<div id="ps-report-modal" style="display: none; position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; background: rgba(32, 33, 36, 0.85); backdrop-filter: blur(6px); -webkit-backdrop-filter: blur(6px); z-index: 9999999; align-items: center; justify-content: center; padding: 20px; box-sizing: border-box;">
  <div style="position: relative; width: 100%; max-width: 960px; height: 90vh; background: #202124; border-radius: 14px; overflow: hidden; box-shadow: 0 24px 48px rgba(0,0,0,0.4); display: flex; flex-direction: column;">
    
    <!-- Modal Header Toolbar -->
    <div style="padding: 14px 20px; background: #2D2E31; border-bottom: 1px solid #3C4043; display: flex; justify-content: space-between; align-items: center; color: #FFFFFF;">
      <div style="display: flex; align-items: center; gap: 10px;">
        <i class="fa-solid fa-file-contract" style="color: #8AB4F8; font-size: 1.1rem;"></i>
        <span id="ps-modal-report-title" style="font-weight: 700; font-size: 0.95rem; color: #FFFFFF;">Sample Report Preview</span>
      </div>
      
      <div style="display: flex; align-items: center; gap: 10px;">
        <a id="ps-modal-download-btn" href="#" target="_blank" rel="noopener noreferrer" style="background: #1A73E8; color: #FFFFFF; text-decoration: none; font-weight: 700; font-size: 0.8rem; padding: 8px 14px; border-radius: 6px; display: inline-flex; align-items: center; gap: 6px;">
          <i class="fa-solid fa-download"></i> Download Full PDF
        </a>
        <button onclick="closeReportModal()" style="background: rgba(255,255,255,0.1); border: none; color: #FFFFFF; font-size: 1.2rem; width: 34px; height: 34px; border-radius: 50%; cursor: pointer; display: flex; align-items: center; justify-content: center;">&times;</button>
      </div>
    </div>

    <!-- Live Document Viewer Frame -->
    <div style="flex: 1; width: 100%; background: #525659; position: relative;">
      <iframe id="ps-modal-pdf-iframe" src="" style="width: 100%; height: 100%; border: none;"></iframe>
    </div>

  </div>
</div>

<style>
  /* Hover effects */
  .ps-report-card:hover {
    transform: translateY(-4px) !important;
    box-shadow: 0 12px 24px rgba(32, 33, 36, 0.08) !important;
  }
  .ps-report-card:hover .ps-preview-hover-overlay {
    opacity: 1 !important;
  }
</style>

<script>
  function openReportModal(pdfUrl, reportTitle) {
    var modal = document.getElementById('ps-report-modal');
    var iframe = document.getElementById('ps-modal-pdf-iframe');
    var titleElem = document.getElementById('ps-modal-report-title');
    var downloadBtn = document.getElementById('ps-modal-download-btn');

    var securePdfUrl = pdfUrl.replace('http://', 'https://');

    titleElem.innerText = reportTitle;
    downloadBtn.href = securePdfUrl;
    
    // Google Document Viewer Engine
    iframe.src = 'https://docs.google.com/gview?url=' + encodeURIComponent(securePdfUrl) + '&embedded=true';
    
    modal.style.display = 'flex';
  }

  function closeReportModal() {
    var modal = document.getElementById('ps-report-modal');
    var iframe = document.getElementById('ps-modal-pdf-iframe');
    iframe.src = '';
    modal.style.display = 'none';
  }

  document.getElementById('ps-report-modal').addEventListener('click', function(e) {
    if (e.target === this) closeReportModal();
  });

  document.addEventListener('keydown', function(e) {
    if (e.key === 'Escape') closeReportModal();
  });
</script>