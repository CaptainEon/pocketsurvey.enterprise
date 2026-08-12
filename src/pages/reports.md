---
_schema: default
title: Sample Mobile Surveying PDF Reports | PocketSurvey
seo:
  page_description: >-
    Explore sample PDF reports generated automatically by PocketSurvey. Inspect Stock Condition, Damp & Mould, HHSRS, and Planned Maintenance sample outputs.
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

<div style="background: radial-gradient(circle at 50% 0%, #F1F5F9 0%, #FAFAFA 70%); color: #0F172A; padding: 48px 16px 80px 16px; min-height: 85vh; box-sizing: border-box; width: 100%;">
  <div style="max-width: 1240px; margin: 0 auto; width: 100%; box-sizing: border-box;">
    
    <!-- Header Section -->
    <div style="text-align: center; margin-bottom: 40px;">
      <span style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.75rem; font-weight: 700; padding: 6px 16px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 30px; display: inline-block; margin-bottom: 12px; letter-spacing: 1px; text-transform: uppercase;">
        AUTOMATED DELIVERABLES
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 800; color: #09090B; margin: 0 0 10px 0; letter-spacing: -0.03em;">
        Client-Ready Sample Reports
      </h1>
      <p style="font-size: 1.05rem; color: #64748B; max-width: 620px; margin: 0 auto 20px auto; line-height: 1.5;">
        Explore instant PDF deliverables generated directly from site surveys without post-survey manual editing or transcription.
      </p>

      <a href="/enquiry.htm" class="ps-header-cta" style="display: inline-block; padding: 10px 24px; font-size: 0.88rem;">
        Request Custom Sample Pack <i class="fa-solid fa-arrow-right" style="margin-left: 6px;"></i>
      </a>
    </div>

    <!-- Filter Pills -->
    <div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 8px; margin-bottom: 40px;">
      <button onclick="filterReports('all')" class="ps-rep-pill active-pill" id="pill-all" style="padding: 8px 20px; border-radius: 20px; border: 1px solid #2563EB; background: #2563EB; color: #FFFFFF; font-weight: 700; font-size: 0.85rem; cursor: pointer; transition: all 0.25s ease;">All Reports</button>
      <button onclick="filterReports('housing')" class="ps-rep-pill" id="pill-housing" style="padding: 8px 20px; border-radius: 20px; border: 1px solid #E2E8F0; background: #FFFFFF; color: #64748B; font-weight: 700; font-size: 0.85rem; cursor: pointer; transition: all 0.25s ease;">Housing &amp; Stock Condition</button>
      <button onclick="filterReports('compliance')" class="ps-rep-pill" id="pill-compliance" style="padding: 8px 20px; border-radius: 20px; border: 1px solid #E2E8F0; background: #FFFFFF; color: #64748B; font-weight: 700; font-size: 0.85rem; cursor: pointer; transition: all 0.25s ease;">Damp, Mould &amp; HHSRS</button>
      <button onclick="filterReports('commercial')" class="ps-rep-pill" id="pill-commercial" style="padding: 8px 20px; border-radius: 20px; border: 1px solid #E2E8F0; background: #FFFFFF; color: #64748B; font-weight: 700; font-size: 0.85rem; cursor: pointer; transition: all 0.25s ease;">Commercial &amp; PPM</button>
    </div>

    <!-- REPORT WALL GRID -->
    <div style="display: flex !important; flex-wrap: wrap !important; gap: 24px !important; justify-content: center !important; width: 100% !important; box-sizing: border-box !important;">
      
      <!-- REPORT CARD 1: HOUSING STOCK CONDITION -->
      <div class="ps-report-card housing" style="flex: 1 1 340px; max-width: 380px; background: #FFFFFF; border: 1px solid #E2E8F0; border-radius: 18px; overflow: hidden; box-shadow: 0 8px 20px rgba(0,0,0,0.03); transition: all 0.35s cubic-bezier(0.16, 1, 0.3, 1); display: flex; flex-direction: column; justify-content: space-between; position: relative; z-index: 1;">
        <div>
          <div onclick="openReportModal('https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf', 'Housing Stock Condition Sample Report')" style="position: relative; width: 100%; aspect-ratio: 16/10; background: linear-gradient(135deg, #0F172A 0%, #1E293B 100%); cursor: pointer; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; padding: 20px; box-sizing: border-box; color: #FFFFFF;">
            <div style="display: flex; justify-content: space-between; align-items: center;">
              <span style="background: rgba(37, 99, 235, 0.25); color: #60A5FA; font-size: 0.68rem; font-weight: 700; padding: 3px 10px; border-radius: 8px; border: 1px solid rgba(96, 165, 250, 0.3); text-transform: uppercase;">EXECUTIVE PDF</span>
              <i class="fa-solid fa-file-pdf" style="font-size: 1.4rem; color: #EF4444;"></i>
            </div>
            
            <div style="text-align: left;">
              <div style="font-size: 0.75rem; color: #94A3B8; font-weight: 600; text-transform: uppercase; letter-spacing: 0.8px;">Stock Condition Export</div>
              <div style="font-weight: 800; font-size: 1.15rem; color: #FFFFFF; line-height: 1.25; margin-top: 2px;">Housing Stock Condition Report</div>
            </div>

            <div style="display: flex; gap: 12px; font-size: 0.72rem; color: #CBD5E1; border-top: 1px solid rgba(255,255,255,0.1); padding-top: 10px;">
              <span><i class="fa-solid fa-layer-group" style="color: #38BDF8; margin-right: 4px;"></i> 30-Yr CapEx</span>
              <span><i class="fa-solid fa-check-double" style="color: #34D399; margin-right: 4px;"></i> Decent Homes</span>
            </div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(37, 99, 235, 0.9); display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.3s ease; backdrop-filter: blur(4px);">
              <span style="background: #FFFFFF; color: #2563EB; font-weight: 800; font-size: 0.85rem; padding: 10px 20px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Open Report Preview</span>
            </div>
          </div>

          <div style="padding: 22px;">
            <span style="background: #EFF6FF; color: #2563EB; font-size: 0.72rem; font-weight: 700; padding: 4px 12px; border-radius: 12px; border: 1px solid rgba(37,99,235,0.2); display: inline-block; margin-bottom: 10px;">HOUSING &amp; SOCIAL LANDLORDS</span>
            <h3 style="font-size: 1.12rem; font-weight: 700; color: #0F172A; margin: 0 0 6px 0; line-height: 1.35;">Stock Condition &amp; Decent Homes Report</h3>
            <p style="font-size: 0.84rem; color: #64748B; margin: 0; line-height: 1.5;">Includes elemental repair costs, 30-year component lifecycle projections, and full Decent Homes compliance tables.</p>
          </div>
        </div>

        <div style="padding: 14px 22px; background: #F8FAFC; border-top: 1px solid #E2E8F0; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf', 'Housing Stock Condition Sample Report')" style="background: transparent; border: none; padding: 0; color: #2563EB; font-weight: 700; font-size: 0.83rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #64748B; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- REPORT CARD 2: DAMP & MOULD SURVEY -->
      <div class="ps-report-card compliance housing" style="flex: 1 1 340px; max-width: 380px; background: #FFFFFF; border: 1px solid #E2E8F0; border-radius: 18px; overflow: hidden; box-shadow: 0 8px 20px rgba(0,0,0,0.03); transition: all 0.35s cubic-bezier(0.16, 1, 0.3, 1); display: flex; flex-direction: column; justify-content: space-between; position: relative; z-index: 1;">
        <div>
          <div onclick="openReportModal('https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf', 'Damp & Mould Survey Sample Report')" style="position: relative; width: 100%; aspect-ratio: 16/10; background: linear-gradient(135deg, #78350F 0%, #B45309 100%); cursor: pointer; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; padding: 20px; box-sizing: border-box; color: #FFFFFF;">
            <div style="display: flex; justify-content: space-between; align-items: center;">
              <span style="background: rgba(217, 119, 6, 0.25); color: #FDE68A; font-size: 0.68rem; font-weight: 700; padding: 3px 10px; border-radius: 8px; border: 1px solid rgba(253, 230, 138, 0.3); text-transform: uppercase;">MOULD &amp; CONDENSATION</span>
              <i class="fa-solid fa-droplet-slash" style="font-size: 1.3rem; color: #FBBF24;"></i>
            </div>
            
            <div style="text-align: left;">
              <div style="font-size: 0.75rem; color: #FEF3C7; font-weight: 600; text-transform: uppercase; letter-spacing: 0.8px;">Risk Assessment</div>
              <div style="font-weight: 800; font-size: 1.15rem; color: #FFFFFF; line-height: 1.25; margin-top: 2px;">Damp &amp; Mould Inspection Report</div>
            </div>

            <div style="display: flex; gap: 12px; font-size: 0.72rem; color: #FEF3C7; border-top: 1px solid rgba(255,255,255,0.1); padding-top: 10px;">
              <span><i class="fa-solid fa-wind" style="color: #38BDF8; margin-right: 4px;"></i> Ventilation Audit</span>
              <span><i class="fa-solid fa-camera" style="color: #34D399; margin-right: 4px;"></i> Photo Evidence</span>
            </div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(217, 119, 6, 0.9); display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.3s ease; backdrop-filter: blur(4px);">
              <span style="background: #FFFFFF; color: #D97706; font-weight: 800; font-size: 0.85rem; padding: 10px 20px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Open Report Preview</span>
            </div>
          </div>

          <div style="padding: 22px;">
            <span style="background: #FEF3C7; color: #D97706; font-size: 0.72rem; font-weight: 700; padding: 4px 12px; border-radius: 12px; border: 1px solid rgba(217,119,6,0.2); display: inline-block; margin-bottom: 10px;">DAMP &amp; MOULD ASSESSMENT</span>
            <h3 style="font-size: 1.12rem; font-weight: 700; color: #0F172A; margin: 0 0 6px 0; line-height: 1.35;">Damp &amp; Mould Risk Inspection Report</h3>
            <p style="font-size: 0.84rem; color: #64748B; margin: 0; line-height: 1.5;">Structured mobile assessment for damp ingress, condensation risk, room-by-room mould severity, and remedial action tracking.</p>
          </div>
        </div>

        <div style="padding: 14px 22px; background: #F8FAFC; border-top: 1px solid #E2E8F0; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf', 'Damp & Mould Survey Sample Report')" style="background: transparent; border: none; padding: 0; color: #2563EB; font-weight: 700; font-size: 0.83rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #64748B; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- REPORT CARD 3: HHSRS HAZARD ASSESSMENT -->
      <div class="ps-report-card compliance housing" style="flex: 1 1 340px; max-width: 380px; background: #FFFFFF; border: 1px solid #E2E8F0; border-radius: 18px; overflow: hidden; box-shadow: 0 8px 20px rgba(0,0,0,0.03); transition: all 0.35s cubic-bezier(0.16, 1, 0.3, 1); display: flex; flex-direction: column; justify-content: space-between; position: relative; z-index: 1;">
        <div>
          <div onclick="openReportModal('https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf', 'HHSRS Housing Health & Safety Sample Report')" style="position: relative; width: 100%; aspect-ratio: 16/10; background: linear-gradient(135deg, #450A0A 0%, #7F1D1D 100%); cursor: pointer; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; padding: 20px; box-sizing: border-box; color: #FFFFFF;">
            <div style="display: flex; justify-content: space-between; align-items: center;">
              <span style="background: rgba(220, 38, 38, 0.25); color: #FCA5A5; font-size: 0.68rem; font-weight: 700; padding: 3px 10px; border-radius: 8px; border: 1px solid rgba(252, 165, 165, 0.3); text-transform: uppercase;">STATUTORY HAZARDS</span>
              <i class="fa-solid fa-shield-halved" style="font-size: 1.3rem; color: #F87171;"></i>
            </div>
            
            <div style="text-align: left;">
              <div style="font-size: 0.75rem; color: #FECACA; font-weight: 600; text-transform: uppercase; letter-spacing: 0.8px;">Statutory Report</div>
              <div style="font-weight: 800; font-size: 1.15rem; color: #FFFFFF; line-height: 1.25; margin-top: 2px;">HHSRS Health &amp; Safety Report</div>
            </div>

            <div style="display: flex; gap: 12px; font-size: 0.72rem; color: #FEE2E2; border-top: 1px solid rgba(255,255,255,0.1); padding-top: 10px;">
              <span><i class="fa-solid fa-triangle-exclamation" style="color: #FBBF24; margin-right: 4px;"></i> Hazard Scoring</span>
              <span><i class="fa-solid fa-house-medical" style="color: #38BDF8; margin-right: 4px;"></i> Category 1 &amp; 2</span>
            </div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(220, 38, 38, 0.9); display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.3s ease; backdrop-filter: blur(4px);">
              <span style="background: #FFFFFF; color: #DC2626; font-weight: 800; font-size: 0.85rem; padding: 10px 20px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Open Report Preview</span>
            </div>
          </div>

          <div style="padding: 22px;">
            <span style="background: #FEE2E2; color: #DC2626; font-size: 0.72rem; font-weight: 700; padding: 4px 12px; border-radius: 12px; border: 1px solid rgba(220,38,38,0.2); display: inline-block; margin-bottom: 10px;">STATUTORY COMPLIANCE</span>
            <h3 style="font-size: 1.12rem; font-weight: 700; color: #0F172A; margin: 0 0 6px 0; line-height: 1.35;">HHSRS Housing Health &amp; Safety Rating</h3>
            <p style="font-size: 0.84rem; color: #64748B; margin: 0; line-height: 1.5;">Evaluates 29 statutory housing health and safety hazards, assigning risk likelihood scores and urgent remediation plans.</p>
          </div>
        </div>

        <div style="padding: 14px 22px; background: #F8FAFC; border-top: 1px solid #E2E8F0; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf', 'HHSRS Housing Health & Safety Sample Report')" style="background: transparent; border: none; padding: 0; color: #2563EB; font-weight: 700; font-size: 0.83rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #64748B; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- REPORT CARD 4: PLANNED PREVENTATIVE MAINTENANCE (PPM) -->
      <div class="ps-report-card commercial" style="flex: 1 1 340px; max-width: 380px; background: #FFFFFF; border: 1px solid #E2E8F0; border-radius: 18px; overflow: hidden; box-shadow: 0 8px 20px rgba(0,0,0,0.03); transition: all 0.35s cubic-bezier(0.16, 1, 0.3, 1); display: flex; flex-direction: column; justify-content: space-between; position: relative; z-index: 1;">
        <div>
          <div onclick="openReportModal('https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf', 'Commercial Planned Maintenance (PPM) Sample Report')" style="position: relative; width: 100%; aspect-ratio: 16/10; background: linear-gradient(135deg, #1E1B4B 0%, #312E81 100%); cursor: pointer; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; padding: 20px; box-sizing: border-box; color: #FFFFFF;">
            <div style="display: flex; justify-content: space-between; align-items: center;">
              <span style="background: rgba(124, 58, 237, 0.25); color: #C084FC; font-size: 0.68rem; font-weight: 700; padding: 3px 10px; border-radius: 8px; border: 1px solid rgba(192, 132, 252, 0.3); text-transform: uppercase;">RICS / SFG20</span>
              <i class="fa-solid fa-screwdriver-wrench" style="font-size: 1.3rem; color: #38BDF8;"></i>
            </div>
            
            <div style="text-align: left;">
              <div style="font-size: 0.75rem; color: #A5B4FC; font-weight: 600; text-transform: uppercase; letter-spacing: 0.8px;">Maintenance Schedule</div>
              <div style="font-weight: 800; font-size: 1.15rem; color: #FFFFFF; line-height: 1.25; margin-top: 2px;">Planned Maintenance (PPM) Report</div>
            </div>

            <div style="display: flex; gap: 12px; font-size: 0.72rem; color: #E0E7FF; border-top: 1px solid rgba(255,255,255,0.1); padding-top: 10px;">
              <span><i class="fa-solid fa-gear" style="color: #A855F7; margin-right: 4px;"></i> SFG20 Tasks</span>
              <span><i class="fa-solid fa-chart-pie" style="color: #38BDF8; margin-right: 4px;"></i> Asset Register</span>
            </div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(124, 58, 237, 0.9); display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.3s ease; backdrop-filter: blur(4px);">
              <span style="background: #FFFFFF; color: #7C3AED; font-weight: 800; font-size: 0.85rem; padding: 10px 20px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Open Report Preview</span>
            </div>
          </div>

          <div style="padding: 22px;">
            <span style="background: #F3E8FF; color: #7C3AED; font-size: 0.72rem; font-weight: 700; padding: 4px 12px; border-radius: 12px; border: 1px solid rgba(124,58,237,0.2); display: inline-block; margin-bottom: 10px;">COMMERCIAL &amp; FM</span>
            <h3 style="font-size: 1.12rem; font-weight: 700; color: #0F172A; margin: 0 0 6px 0; line-height: 1.35;">Planned Preventative Maintenance (PPM)</h3>
            <p style="font-size: 0.84rem; color: #64748B; margin: 0; line-height: 1.5;">Structured building fabric, mechanical, and electrical maintenance schedules adhering to RICS, SFG20, and NHS 6-Facet frameworks.</p>
          </div>
        </div>

        <div style="padding: 14px 22px; background: #F8FAFC; border-top: 1px solid #E2E8F0; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf', 'Commercial Planned Maintenance (PPM) Sample Report')" style="background: transparent; border: none; padding: 0; color: #2563EB; font-weight: 700; font-size: 0.83rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #64748B; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

    </div>

    <!-- Bottom Banner CTA -->
    <div style="margin-top: 60px; background: #0F172A; border-radius: 20px; padding: 40px 28px; text-align: center; color: #FFFFFF;">
      <h2 style="font-size: 1.65rem; font-weight: 800; margin: 0 0 8px 0; color: #FFFFFF;">Need Your Firm's Custom Branding on Reports?</h2>
      <p style="font-size: 0.98rem; color: #94A3B8; max-width: 560px; margin: 0 auto 24px auto;">We configure custom executive summaries, corporate logos, disclaimers, and CSV data exporters to match your exact business requirements.</p>
      <a href="/enquiry.htm" class="ps-header-cta" style="display: inline-block; padding: 12px 30px; font-size: 0.95rem;">Book Technical Consult <i class="fa-solid fa-arrow-right" style="margin-left: 6px;"></i></a>
    </div>

  </div>
</div>

<!-- Modal Document Viewer Popup Container -->
<div id="ps-report-modal" style="display: none; position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; background: rgba(15, 23, 42, 0.85); backdrop-filter: blur(8px); -webkit-backdrop-filter: blur(8px); z-index: 9999999; align-items: center; justify-content: center; padding: 20px; box-sizing: border-box;">
  <div style="position: relative; width: 100%; max-width: 960px; height: 90vh; background: #0F172A; border-radius: 18px; overflow: hidden; box-shadow: 0 25px 50px rgba(0,0,0,0.5); display: flex; flex-direction: column;">
    
    <!-- Modal Header Toolbar -->
    <div style="padding: 16px 24px; background: #1E293B; border-bottom: 1px solid #334155; display: flex; justify-content: space-between; align-items: center; color: #FFFFFF;">
      <div style="display: flex; align-items: center; gap: 12px;">
        <i class="fa-solid fa-file-contract" style="color: #38BDF8; font-size: 1.2rem;"></i>
        <span id="ps-modal-report-title" style="font-weight: 700; font-size: 1rem; color: #FFFFFF;">Sample Report Preview</span>
      </div>
      
      <div style="display: flex; align-items: center; gap: 12px;">
        <a id="ps-modal-download-btn" href="#" target="_blank" rel="noopener noreferrer" style="background: #2563EB; color: #FFFFFF; text-decoration: none; font-weight: 700; font-size: 0.82rem; padding: 8px 16px; border-radius: 8px; display: inline-flex; align-items: center; gap: 6px;">
          <i class="fa-solid fa-download"></i> Download Full PDF
        </a>
        <button onclick="closeReportModal()" style="background: rgba(255,255,255,0.1); border: none; color: #FFFFFF; font-size: 1.2rem; width: 36px; height: 36px; border-radius: 50%; cursor: pointer; display: flex; align-items: center; justify-content: center;">&times;</button>
      </div>
    </div>

    <!-- Live Document Viewer Frame -->
    <div style="flex: 1; width: 100%; background: #525659; position: relative;">
      <iframe id="ps-modal-pdf-iframe" src="" style="width: 100%; height: 100%; border: none;"></iframe>
    </div>

  </div>
</div>

<style>
  /* Brings Hovered Card to Front */
  .ps-report-card:hover {
    transform: translateY(-8px) scale(1.02) !important;
    border-color: #2563EB !important;
    box-shadow: 0 20px 40px rgba(37, 99, 235, 0.18) !important;
    z-index: 10 !important;
  }
  .ps-report-card:hover .ps-preview-hover-overlay {
    opacity: 1 !important;
  }
</style>

<script>
  function filterReports(category) {
    var cards = document.getElementsByClassName('ps-report-card');
    var pills = document.getElementsByClassName('ps-rep-pill');

    for (var i = 0; i < pills.length; i++) {
      pills[i].style.background = '#FFFFFF';
      pills[i].style.color = '#64748B';
      pills[i].style.borderColor = '#E2E8F0';
    }

    var activePill = document.getElementById('pill-' + category);
    if (activePill) {
      activePill.style.background = '#2563EB';
      activePill.style.color = '#FFFFFF';
      activePill.style.borderColor = '#2563EB';
    }

    for (var j = 0; j < cards.length; j++) {
      if (category === 'all' || cards[j].classList.contains(category)) {
        cards[j].style.display = 'flex';
      } else {
        cards[j].style.display = 'none';
      }
    }
  }

  function openReportModal(pdfUrl, reportTitle) {
    var modal = document.getElementById('ps-report-modal');
    var iframe = document.getElementById('ps-modal-pdf-iframe');
    var titleElem = document.getElementById('ps-modal-report-title');
    var downloadBtn = document.getElementById('ps-modal-download-btn');

    // Ensure link uses HTTPS
    var securePdfUrl = pdfUrl.replace('http://', 'https://');

    titleElem.innerText = reportTitle;
    downloadBtn.href = securePdfUrl;
    
    // Uses Google's Document Embedder to safely render cross-domain PDFs inside the modal
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