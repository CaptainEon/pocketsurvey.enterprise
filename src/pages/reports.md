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

<div style="background: radial-gradient(circle at 50% 0%, #F8FAFC 0%, #FAFAFA 70%); color: #0F172A; padding: 48px 16px 80px 16px; min-height: 85vh; box-sizing: border-box; width: 100%;">
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
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(380px, 1fr)); gap: 28px; width: 100%; box-sizing: border-box;">
      
      <!-- CARD 1: HOUSING STOCK CONDITION (UK TERRACED HOUSES) -->
      <div class="ps-report-card" style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 16px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.03); transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1); display: flex; flex-direction: column; justify-content: space-between; position: relative;">
        <div>
          <!-- UK Terraced Houses Image -->
          <div onclick="openReportModal('https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf', 'Housing Stock Condition Sample Report')" style="position: relative; width: 100%; aspect-ratio: 16/9; background: #202124 url('https://images.unsplash.com/photo-1592595896616-c37162298647?auto=format&fit=crop&w=800&q=80') center/cover no-repeat; cursor: pointer; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; padding: 18px; box-sizing: border-box; color: #FFFFFF;">
            
            <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: linear-gradient(180deg, rgba(15,23,42,0.4) 0%, rgba(15,23,42,0.85) 100%); z-index: 1;"></div>

            <div style="position: relative; z-index: 2; display: flex; justify-content: space-between; align-items: center;">
              <span style="background: rgba(255, 255, 255, 0.2); backdrop-filter: blur(4px); color: #FFFFFF; font-size: 0.68rem; font-weight: 700; padding: 4px 10px; border-radius: 6px; letter-spacing: 0.5px; text-transform: uppercase;">SAMPLE PDF</span>
              <i class="fa-solid fa-file-pdf" style="font-size: 1.3rem; color: #FFFFFF;"></i>
            </div>
            
            <div style="position: relative; z-index: 2; text-align: left;">
              <div style="font-size: 0.72rem; color: rgba(255,255,255,0.8); font-weight: 600; text-transform: uppercase; letter-spacing: 0.8px;">Housing Stock</div>
              <div style="font-weight: 800; font-size: 1.15rem; color: #FFFFFF; line-height: 1.25; margin-top: 2px;">Stock Condition &amp; Decent Homes</div>
            </div>

            <!-- Sleek Bottom Strip -->
            <div style="position: relative; z-index: 2; display: flex; gap: 14px; font-size: 0.75rem; color: rgba(255,255,255,0.9); border-top: 1px solid rgba(255,255,255,0.25); padding-top: 8px; margin-top: 6px;">
              <span><i class="fa-solid fa-layer-group" style="margin-right: 4px; color: #8AB4F8;"></i> 30-Yr CapEx</span>
              <span><i class="fa-solid fa-check-double" style="margin-right: 4px; color: #81C995;"></i> Decent Homes</span>
            </div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(26, 115, 232, 0.92); z-index: 3; display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.3s ease; backdrop-filter: blur(4px);">
              <span style="background: #FFFFFF; color: #1A73E8; font-weight: 800; font-size: 0.85rem; padding: 10px 22px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Open Report Preview</span>
            </div>
          </div>

          <div style="padding: 22px;">
            <span style="background: rgba(26, 115, 232, 0.08); color: #1A73E8; font-size: 0.72rem; font-weight: 700; padding: 4px 12px; border-radius: 12px; border: 1px solid rgba(26, 115, 232, 0.2); display: inline-block; margin-bottom: 10px;">HOUSING &amp; SOCIAL LANDLORDS</span>
            <h3 style="font-size: 1.1rem; font-weight: 700; color: #202124; margin: 0 0 6px 0; line-height: 1.35;">Stock Condition &amp; Decent Homes Report</h3>
            <p style="font-size: 0.85rem; color: #5F6368; margin: 0; line-height: 1.5;">Includes elemental repair costs, 30-year component lifecycle projections, and full Decent Homes compliance tables.</p>
          </div>
        </div>

        <div style="padding: 14px 22px; background: #F8F9FA; border-top: 1px solid #E8EAED; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf', 'Housing Stock Condition Sample Report')" style="background: transparent; border: none; padding: 0; color: #1A73E8; font-weight: 700; font-size: 0.83rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/stock-condition/housing-stock-condition-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #5F6368; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- CARD 2: COMMERCIAL PLANNED MAINTENANCE (COMMERCIAL HIGH RISE) -->
      <div class="ps-report-card" style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 16px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.03); transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1); display: flex; flex-direction: column; justify-content: space-between; position: relative;">
        <div>
          <div onclick="openReportModal('https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf', 'Commercial Planned Maintenance (PPM) Sample Report')" style="position: relative; width: 100%; aspect-ratio: 16/9; background: #202124 url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=800&q=80') center/cover no-repeat; cursor: pointer; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; padding: 18px; box-sizing: border-box; color: #FFFFFF;">
            
            <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: linear-gradient(180deg, rgba(15,23,42,0.4) 0%, rgba(15,23,42,0.85) 100%); z-index: 1;"></div>

            <div style="position: relative; z-index: 2; display: flex; justify-content: space-between; align-items: center;">
              <span style="background: rgba(255, 255, 255, 0.2); backdrop-filter: blur(4px); color: #FFFFFF; font-size: 0.68rem; font-weight: 700; padding: 4px 10px; border-radius: 6px; letter-spacing: 0.5px; text-transform: uppercase;">RICS / SFG20</span>
              <i class="fa-solid fa-screwdriver-wrench" style="font-size: 1.3rem; color: #FFFFFF;"></i>
            </div>
            
            <div style="position: relative; z-index: 2; text-align: left;">
              <div style="font-size: 0.72rem; color: rgba(255,255,255,0.8); font-weight: 600; text-transform: uppercase; letter-spacing: 0.8px;">Maintenance Schedule</div>
              <div style="font-weight: 800; font-size: 1.15rem; color: #FFFFFF; line-height: 1.25; margin-top: 2px;">Planned Maintenance (PPM) Report</div>
            </div>

            <!-- Sleek Bottom Strip -->
            <div style="position: relative; z-index: 2; display: flex; gap: 14px; font-size: 0.75rem; color: rgba(255,255,255,0.9); border-top: 1px solid rgba(255,255,255,0.25); padding-top: 8px; margin-top: 6px;">
              <span><i class="fa-solid fa-gear" style="margin-right: 4px; color: #8AB4F8;"></i> SFG20 Tasks</span>
              <span><i class="fa-solid fa-chart-pie" style="margin-right: 4px; color: #FDE293;"></i> Asset Register</span>
            </div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(26, 115, 232, 0.92); z-index: 3; display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.3s ease; backdrop-filter: blur(4px);">
              <span style="background: #FFFFFF; color: #1A73E8; font-weight: 800; font-size: 0.85rem; padding: 10px 22px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Open Report Preview</span>
            </div>
          </div>

          <div style="padding: 22px;">
            <span style="background: rgba(26, 115, 232, 0.08); color: #1A73E8; font-size: 0.72rem; font-weight: 700; padding: 4px 12px; border-radius: 12px; border: 1px solid rgba(26, 115, 232, 0.2); display: inline-block; margin-bottom: 10px;">COMMERCIAL &amp; FM</span>
            <h3 style="font-size: 1.1rem; font-weight: 700; color: #202124; margin: 0 0 6px 0; line-height: 1.35;">Planned Preventative Maintenance (PPM)</h3>
            <p style="font-size: 0.85rem; color: #5F6368; margin: 0; line-height: 1.5;">Structured building fabric, mechanical, and electrical maintenance schedules adhering to RICS and SFG20 frameworks.</p>
          </div>
        </div>

        <div style="padding: 14px 22px; background: #F8F9FA; border-top: 1px solid #E8EAED; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf', 'Commercial Planned Maintenance (PPM) Sample Report')" style="background: transparent; border: none; padding: 0; color: #1A73E8; font-weight: 700; font-size: 0.83rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/planned-maintenance/planned-maintenance-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #5F6368; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- CARD 3: DAMP & MOULD SURVEY (VENTILATION / TIMBER FOCUS) -->
      <div class="ps-report-card" style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 16px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.03); transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1); display: flex; flex-direction: column; justify-content: space-between; position: relative;">
        <div>
          <!-- Ventilation & Airflow Focus Image -->
          <div onclick="openReportModal('https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf', 'Damp & Mould Survey Sample Report')" style="position: relative; width: 100%; aspect-ratio: 16/9; background: #202124 url('https://images.unsplash.com/photo-1621905251189-08b45d6a269e?auto=format&fit=crop&w=800&q=80') center/cover no-repeat; cursor: pointer; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; padding: 18px; box-sizing: border-box; color: #FFFFFF;">
            
            <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: linear-gradient(180deg, rgba(15,23,42,0.4) 0%, rgba(15,23,42,0.85) 100%); z-index: 1;"></div>

            <div style="position: relative; z-index: 2; display: flex; justify-content: space-between; align-items: center;">
              <span style="background: rgba(255, 255, 255, 0.2); backdrop-filter: blur(4px); color: #FFFFFF; font-size: 0.68rem; font-weight: 700; padding: 4px 10px; border-radius: 6px; letter-spacing: 0.5px; text-transform: uppercase;">RISK ASSESSMENT</span>
              <i class="fa-solid fa-droplet-slash" style="font-size: 1.3rem; color: #FFFFFF;"></i>
            </div>
            
            <div style="position: relative; z-index: 2; text-align: left;">
              <div style="font-size: 0.72rem; color: rgba(255,255,255,0.8); font-weight: 600; text-transform: uppercase; letter-spacing: 0.8px;">Mould &amp; Condensation</div>
              <div style="font-weight: 800; font-size: 1.15rem; color: #FFFFFF; line-height: 1.25; margin-top: 2px;">Damp &amp; Mould Inspection Report</div>
            </div>

            <!-- Sleek Bottom Strip -->
            <div style="position: relative; z-index: 2; display: flex; gap: 14px; font-size: 0.75rem; color: rgba(255,255,255,0.9); border-top: 1px solid rgba(255,255,255,0.25); padding-top: 8px; margin-top: 6px;">
              <span><i class="fa-solid fa-wind" style="margin-right: 4px; color: #8AB4F8;"></i> Ventilation Audit</span>
              <span><i class="fa-solid fa-camera" style="margin-right: 4px; color: #81C995;"></i> Photo Evidence</span>
            </div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(26, 115, 232, 0.92); z-index: 3; display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.3s ease; backdrop-filter: blur(4px);">
              <span style="background: #FFFFFF; color: #1A73E8; font-weight: 800; font-size: 0.85rem; padding: 10px 22px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Open Report Preview</span>
            </div>
          </div>

          <div style="padding: 22px;">
            <span style="background: rgba(26, 115, 232, 0.08); color: #1A73E8; font-size: 0.72rem; font-weight: 700; padding: 4px 12px; border-radius: 12px; border: 1px solid rgba(26, 115, 232, 0.2); display: inline-block; margin-bottom: 10px;">DAMP &amp; MOULD ASSESSMENT</span>
            <h3 style="font-size: 1.1rem; font-weight: 700; color: #202124; margin: 0 0 6px 0; line-height: 1.35;">Damp &amp; Mould Risk Inspection Report</h3>
            <p style="font-size: 0.85rem; color: #5F6368; margin: 0; line-height: 1.5;">Structured mobile assessment for damp ingress, condensation risk, room-by-room mould severity, and remedial action tracking.</p>
          </div>
        </div>

        <div style="padding: 14px 22px; background: #F8F9FA; border-top: 1px solid #E8EAED; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf', 'Damp & Mould Survey Sample Report')" style="background: transparent; border: none; padding: 0; color: #1A73E8; font-weight: 700; font-size: 0.83rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/damp-mould/damp-mould-survey-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #5F6368; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

      <!-- CARD 4: HHSRS HAZARD ASSESSMENT (HAZARD WARNING SIGN) -->
      <div class="ps-report-card" style="background: #FFFFFF; border: 1px solid #E8EAED; border-radius: 16px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.03); transition: all 0.3s cubic-bezier(0.16, 1, 0.3, 1); display: flex; flex-direction: column; justify-content: space-between; position: relative;">
        <div>
          <!-- Hazard Warning Sign Imagery -->
          <div onclick="openReportModal('https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf', 'HHSRS Housing Health & Safety Sample Report')" style="position: relative; width: 100%; aspect-ratio: 16/9; background: #202124 url('https://images.unsplash.com/photo-1584036561566-baf8f5f1b144?auto=format&fit=crop&w=800&q=80') center/cover no-repeat; cursor: pointer; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; padding: 18px; box-sizing: border-box; color: #FFFFFF;">
            
            <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: linear-gradient(180deg, rgba(15,23,42,0.4) 0%, rgba(15,23,42,0.85) 100%); z-index: 1;"></div>

            <div style="position: relative; z-index: 2; display: flex; justify-content: space-between; align-items: center;">
              <span style="background: rgba(255, 255, 255, 0.2); backdrop-filter: blur(4px); color: #FFFFFF; font-size: 0.68rem; font-weight: 700; padding: 4px 10px; border-radius: 6px; letter-spacing: 0.5px; text-transform: uppercase;">STATUTORY REPORT</span>
              <i class="fa-solid fa-shield-halved" style="font-size: 1.3rem; color: #FFFFFF;"></i>
            </div>
            
            <div style="position: relative; z-index: 2; text-align: left;">
              <div style="font-size: 0.72rem; color: rgba(255,255,255,0.8); font-weight: 600; text-transform: uppercase; letter-spacing: 0.8px;">Statutory Hazards</div>
              <div style="font-weight: 800; font-size: 1.15rem; color: #FFFFFF; line-height: 1.25; margin-top: 2px;">HHSRS Health &amp; Safety Report</div>
            </div>

            <!-- Sleek Bottom Strip -->
            <div style="position: relative; z-index: 2; display: flex; gap: 14px; font-size: 0.75rem; color: rgba(255,255,255,0.9); border-top: 1px solid rgba(255,255,255,0.25); padding-top: 8px; margin-top: 6px;">
              <span><i class="fa-solid fa-triangle-exclamation" style="margin-right: 4px; color: #FDE293;"></i> Hazard Scoring</span>
              <span><i class="fa-solid fa-house-medical" style="margin-right: 4px; color: #F87171;"></i> Category 1 &amp; 2</span>
            </div>

            <div class="ps-preview-hover-overlay" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(26, 115, 232, 0.92); z-index: 3; display: flex; align-items: center; justify-content: center; opacity: 0; transition: all 0.3s ease; backdrop-filter: blur(4px);">
              <span style="background: #FFFFFF; color: #1A73E8; font-weight: 800; font-size: 0.85rem; padding: 10px 22px; border-radius: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);"><i class="fa-solid fa-expand" style="margin-right: 6px;"></i> Open Report Preview</span>
            </div>
          </div>

          <div style="padding: 22px;">
            <span style="background: rgba(26, 115, 232, 0.08); color: #1A73E8; font-size: 0.72rem; font-weight: 700; padding: 4px 12px; border-radius: 12px; border: 1px solid rgba(26, 115, 232, 0.2); display: inline-block; margin-bottom: 10px;">STATUTORY COMPLIANCE</span>
            <h3 style="font-size: 1.1rem; font-weight: 700; color: #202124; margin: 0 0 6px 0; line-height: 1.35;">HHSRS Housing Health &amp; Safety Rating</h3>
            <p style="font-size: 0.85rem; color: #5F6368; margin: 0; line-height: 1.5;">Evaluates 29 statutory housing health and safety hazards, assigning risk likelihood scores and urgent remediation plans.</p>
          </div>
        </div>

        <div style="padding: 14px 22px; background: #F8F9FA; border-top: 1px solid #E8EAED; display: flex; justify-content: space-between; align-items: center;">
          <button onclick="openReportModal('https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf', 'HHSRS Housing Health & Safety Sample Report')" style="background: transparent; border: none; padding: 0; color: #1A73E8; font-weight: 700; font-size: 0.83rem; cursor: pointer;">Preview PDF <i class="fa-solid fa-eye" style="font-size: 0.75rem; margin-left: 4px;"></i></button>
          <a href="https://www.pocketsurvey.org/hhsrs/hhsrs-housing-health-and-safety-report.pdf" target="_blank" rel="noopener noreferrer" style="color: #5F6368; font-weight: 600; font-size: 0.78rem; text-decoration: none;">Download PDF <i class="fa-solid fa-download" style="font-size: 0.7rem; margin-left: 3px;"></i></a>
        </div>
      </div>

    </div>

    <!-- Bottom Banner CTA -->
    <div style="margin-top: 60px; background: #202124; border-radius: 16px; padding: 40px 28px; text-align: center; color: #FFFFFF;">
      <h2 style="font-size: 1.6rem; font-weight: 800; margin: 0 0 8px 0; color: #FFFFFF;">Need Your Firm's Custom Branding on Reports?</h2>
      <p style="font-size: 0.95rem; color: #9AA0A6; max-width: 560px; margin: 0 auto 24px auto;">We configure custom executive summaries, corporate logos, disclaimers, and CSV data exporters to match your exact business requirements.</p>
      <a href="/enquiry.htm" class="ps-header-cta" style="display: inline-block; padding: 12px 30px; font-size: 0.92rem; background: #1A73E8;">Book Technical Consult <i class="fa-solid fa-arrow-right" style="margin-left: 6px;"></i></a>
    </div>

  </div>
</div>

<!-- Modal Document Viewer Popup Container -->
<div id="ps-report-modal" style="display: none; position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; background: rgba(32, 33, 36, 0.85); backdrop-filter: blur(6px); -webkit-backdrop-filter: blur(6px); z-index: 9999999; align-items: center; justify-content: center; padding: 20px; box-sizing: border-box;">
  <div style="position: relative; width: 100%; max-width: 960px; height: 90vh; background: #202124; border-radius: 16px; overflow: hidden; box-shadow: 0 24px 48px rgba(0,0,0,0.4); display: flex; flex-direction: column;">
    
    <!-- Modal Header Toolbar -->
    <div style="padding: 16px 24px; background: #2D2E31; border-bottom: 1px solid #3C4043; display: flex; justify-content: space-between; align-items: center; color: #FFFFFF;">
      <div style="display: flex; align-items: center; gap: 12px;">
        <i class="fa-solid fa-file-contract" style="color: #8AB4F8; font-size: 1.2rem;"></i>
        <span id="ps-modal-report-title" style="font-weight: 700; font-size: 0.98rem; color: #FFFFFF;">Sample Report Preview</span>
      </div>
      
      <div style="display: flex; align-items: center; gap: 12px;">
        <a id="ps-modal-download-btn" href="#" target="_blank" rel="noopener noreferrer" style="background: #1A73E8; color: #FFFFFF; text-decoration: none; font-weight: 700; font-size: 0.82rem; padding: 8px 16px; border-radius: 8px; display: inline-flex; align-items: center; gap: 6px;">
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
  /* Hover effects */
  .ps-report-card:hover {
    transform: translateY(-6px) scale(1.02) !important;
    box-shadow: 0 16px 32px rgba(32, 33, 36, 0.12) !important;
    z-index: 10 !important;
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