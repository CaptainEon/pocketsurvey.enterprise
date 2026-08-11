---
_schema: default
title: Enterprise Pricing & Feature Matrix | PocketSurvey
seo:
  page_description: >-
    Transparent enterprise licensing and feature matrix for PocketSurvey Enterprise. Includes Stock Condition, Commercial PPM, and asset system exports.
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

<section style="background-color: #FAFAFA; color: #18181B; padding: 64px 0 80px 0; border-bottom: 1px solid #E4E4E7; min-height: 80vh;">
  <div style="max-width: 1100px; padding: 0 20px; margin: 0 auto;">

    <!-- Title & Tier Overview -->
    <div style="text-align: center; margin-bottom: 40px;">
      <span class="ps-badge-platinum" style="background: rgba(37, 99, 235, 0.08); color: #2563EB; font-size: 0.8rem; padding: 6px 14px; border: 1px solid rgba(37, 99, 235, 0.2); border-radius: 20px; display: inline-block; margin-bottom: 16px;">
        ENTERPRISE LICENSING
      </span>
      <h1 style="font-size: clamp(2rem, 4vw, 2.8rem); font-weight: 800; color: #09090B; margin: 0 0 12px 0; letter-spacing: -0.02em;">
        Enterprise Capability &amp; Feature Matrix
      </h1>
      <p style="font-size: 1.05rem; color: #52525B; max-width: 680px; margin: 0 auto; line-height: 1.6;">
        All-inclusive per-user licensing. Get full access to our Housing, Commercial, and Asset System Export engines for <strong style="color: #09090B;">£175 / user / month</strong>.
      </p>
    </div>

    <!-- Interactive Category Filter Pills -->
    <div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 10px; margin-bottom: 32px;">
      <button onclick="filterTable('all')" class="ps-table-tab is-active" id="tab-all">
        All Capabilities
      </button>
      <button onclick="filterTable('housing')" class="ps-table-tab" id="tab-housing">
        <i class="fa-solid fa-house-building" style="margin-right: 6px;"></i> Housing Stock Suite
      </button>
      <button onclick="filterTable('commercial')" class="ps-table-tab" id="tab-commercial">
        <i class="fa-solid fa-screwdriver-wrench" style="margin-right: 6px;"></i> Commercial PPM Suite
      </button>
      <button onclick="filterTable('exports')" class="ps-table-tab" id="tab-exports">
        <i class="fa-solid fa-file-csv" style="margin-right: 6px;"></i> System Data Exports
      </button>
    </div>

    <!-- Interactive Enterprise Feature Table -->
    <div style="background: #FFFFFF; border: 1px solid #E4E4E7; border-radius: 16px; overflow: hidden; box-shadow: 0 10px 30px rgba(0, 0, 0, 0.04); margin-bottom: 48px;">
      
      <!-- Table Header -->
      <div style="display: grid; grid-template-columns: 2.5fr 1fr 1fr; background: #F8FAFC; padding: 16px 24px; border-bottom: 1px solid #E2E8F0; font-weight: 700; font-size: 0.88rem; color: #475569; text-transform: uppercase; letter-spacing: 0.5px;">
        <div>Enterprise Capability / Module</div>
        <div style="text-align: center;">Framework / Standard</div>
        <div style="text-align: right;">Enterprise Inclusion</div>
      </div>

      <!-- Table Body Container -->
      <div id="feature-table-body">
        
        <!-- Row 1: Housing Stock Condition -->
        <div class="ps-table-row row-housing" style="display: grid; grid-template-columns: 2.5fr 1fr 1fr; padding: 18px 24px; border-bottom: 1px solid #F1F5F9; align-items: center; transition: all 0.2s ease;">
          <div>
            <div style="font-weight: 700; color: #0F172A; font-size: 0.98rem;">Housing Stock Condition</div>
            <div style="font-size: 0.82rem; color: #64748B;">Complete social housing property audits &amp; component life-cycle schedules</div>
          </div>
          <div style="text-align: center;">
            <span style="background: #EFF6FF; color: #2563EB; font-size: 0.78rem; font-weight: 600; padding: 4px 10px; border-radius: 6px;">Decent Homes / SHQS / WHQS</span>
          </div>
          <div style="text-align: right; color: #059669; font-weight: 700; font-size: 0.9rem;">
            <i class="fa-solid fa-circle-check" style="margin-right: 4px; font-size: 1rem;"></i> Included
          </div>
        </div>

        <!-- Row 2: HHSRS Audits -->
        <div class="ps-table-row row-housing" style="display: grid; grid-template-columns: 2.5fr 1fr 1fr; padding: 18px 24px; border-bottom: 1px solid #F1F5F9; align-items: center; transition: all 0.2s ease;">
          <div>
            <div style="font-weight: 700; color: #0F172A; font-size: 0.98rem;">HHSRS Damp, Mould &amp; Safety Audits</div>
            <div style="font-size: 0.82rem; color: #64748B;">Housing Health &amp; Safety Rating System hazard scoring matrix</div>
          </div>
          <div style="text-align: center;">
            <span style="background: #EFF6FF; color: #2563EB; font-size: 0.78rem; font-weight: 600; padding: 4px 10px; border-radius: 6px;">UK Statutory Standard</span>
          </div>
          <div style="text-align: right; color: #059669; font-weight: 700; font-size: 0.9rem;">
            <i class="fa-solid fa-circle-check" style="margin-right: 4px; font-size: 1rem;"></i> Included
          </div>
        </div>

        <!-- Row 3: Commercial Planned Maintenance -->
        <div class="ps-table-row row-commercial" style="display: grid; grid-template-columns: 2.5fr 1fr 1fr; padding: 18px 24px; border-bottom: 1px solid #F1F5F9; align-items: center; transition: all 0.2s ease;">
          <div>
            <div style="font-weight: 700; color: #0F172A; font-size: 0.98rem;">Commercial Planned Preventative Maintenance (PPM)</div>
            <div style="font-size: 0.82rem; color: #64748B;">Fabric, M&amp;E elements, and 30–50 year CapEx long-term forecasting</div>
          </div>
          <div style="text-align: center;">
            <span style="background: #F3E8FF; color: #7C3AED; font-size: 0.78rem; font-weight: 600; padding: 4px 10px; border-radius: 6px;">Standard RICS / SFG20</span>
          </div>
          <div style="text-align: right; color: #059669; font-weight: 700; font-size: 0.9rem;">
            <i class="fa-solid fa-circle-check" style="margin-right: 4px; font-size: 1rem;"></i> Included
          </div>
        </div>

        <!-- Row 4: NHS 6-Facets -->
        <div class="ps-table-row row-commercial" style="display: grid; grid-template-columns: 2.5fr 1fr 1fr; padding: 18px 24px; border-bottom: 1px solid #F1F5F9; align-items: center; transition: all 0.2s ease;">
          <div>
            <div style="font-weight: 700; color: #0F172A; font-size: 0.98rem;">NHS 6-Facets Estate Auditing</div>
            <div style="font-size: 0.82rem; color: #64748B;">Statutory healthcare condition, space utilization, and safety compliance</div>
          </div>
          <div style="text-align: center;">
            <span style="background: #F3E8FF; color: #7C3AED; font-size: 0.78rem; font-weight: 600; padding: 4px 10px; border-radius: 6px;">NHS Estate Guidelines</span>
          </div>
          <div style="text-align: right; color: #059669; font-weight: 700; font-size: 0.9rem;">
            <i class="fa-solid fa-circle-check" style="margin-right: 4px; font-size: 1rem;"></i> Included
          </div>
        </div>

        <!-- Row 5: Asset System Exports -->
        <div class="ps-table-row row-exports" style="display: grid; grid-template-columns: 2.5fr 1fr 1fr; padding: 18px 24px; border-bottom: 1px solid #F1F5F9; align-items: center; transition: all 0.2s ease;">
          <div>
            <div style="font-weight: 700; color: #0F172A; font-size: 0.98rem;">Direct Asset System CSV Exporters</div>
            <div style="font-size: 0.82rem; color: #64748B;">Automated CSV exports mapped directly for NEC, Capita, Civica, Keystone, and MRI</div>
          </div>
          <div style="text-align: center;">
            <span style="background: #FEF3C7; color: #D97706; font-size: 0.78rem; font-weight: 600; padding: 4px 10px; border-radius: 6px;">Pre-Formatted Export</span>
          </div>
          <div style="text-align: right; color: #059669; font-weight: 700; font-size: 0.9rem;">
            <i class="fa-solid fa-circle-check" style="margin-right: 4px; font-size: 1rem;"></i> Included
          </div>
        </div>

        <!-- Row 6: Enterprise Platform Controls -->
        <div class="ps-table-row row-housing row-commercial row-exports" style="display: grid; grid-template-columns: 2.5fr 1fr 1fr; padding: 18px 24px; border-bottom: 1px solid #F1F5F9; align-items: center; transition: all 0.2s ease;">
          <div>
            <div style="font-weight: 700; color: #0F172A; font-size: 0.98rem;">Enterprise Database Controls &amp; Desktop Management</div>
            <div style="font-size: 0.82rem; color: #64748B;">Segmented database permissions, cloud photo galleries, and offline mobile engine</div>
          </div>
          <div style="text-align: center;">
            <span style="background: #F1F5F9; color: #475569; font-size: 0.78rem; font-weight: 600; padding: 4px 10px; border-radius: 6px;">Core Platform</span>
          </div>
          <div style="text-align: right; color: #059669; font-weight: 700; font-size: 0.9rem;">
            <i class="fa-solid fa-circle-check" style="margin-right: 4px; font-size: 1rem;"></i> Included
          </div>
        </div>

      </div>

      <!-- Table Footer CTA -->
      <div style="background: #09090B; color: #FFFFFF; padding: 24px 32px; display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 20px;">
        <div>
          <div style="font-size: 1.1rem; font-weight: 700;">Ready to streamline your inspection data workflow?</div>
          <div style="font-size: 0.85rem; color: #A1A1AA;">Includes free onboarding, ongoing user training, and dedicated technical support.</div>
        </div>
        <a href="/enquiry.htm" class="ps-header-cta" style="margin-left: 0; padding: 12px 24px; font-size: 0.92rem;">
          Book Enterprise Demo <i class="fa-solid fa-arrow-right" style="margin-left: 8px;"></i>
        </a>
      </div>

    </div>

    <!-- Bespoke Development Callout Banner -->
    <div style="background: #FFFFFF; border: 1px dashed #CBD5E1; border-radius: 16px; padding: 28px; display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 20px;">
      <div>
        <h3 style="font-size: 1.1rem; font-weight: 700; color: #09090B; margin: 0 0 6px 0;">Need Bespoke App Development or Custom Exporters?</h3>
        <p style="font-size: 0.88rem; color: #52525B; margin: 0;">We build custom mobile surveying applications and bespoke CSV/XML exporters tailored to your council's exact schema.</p>
      </div>
      <a href="/enquiry.htm" class="ps-hero-secondary-cta" style="padding: 10px 20px; font-size: 0.88rem; white-space: nowrap; border-color: #CBD5E1; color: #09090B !important;">
        Discuss Custom App <i class="fa-solid fa-comments" style="margin-left: 6px; color: #2563EB;"></i>
      </a>
    </div>

  </div>
</section>

<!-- Table Styling & Interactive Filter Script -->
<style>
  .ps-table-tab {
    padding: 8px 18px;
    border-radius: 20px;
    border: 1px solid #E4E4E7;
    background: #FFFFFF;
    color: #52525B;
    font-size: 0.88rem;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.2s ease;
  }
  .ps-table-tab:hover {
    border-color: #2563EB;
    color: #2563EB;
  }
  .ps-table-tab.is-active {
    background: #2563EB;
    border-color: #2563EB;
    color: #FFFFFF !important;
    box-shadow: 0 4px 12px rgba(37, 99, 235, 0.25);
  }
  .ps-table-row:hover {
    background-color: #F8FAFC !important;
    transform: translateX(4px);
  }
</style>

<script>
  function filterTable(category) {
    // Update Active Tab State
    document.querySelectorAll('.ps-table-tab').forEach(tab => tab.classList.remove('is-active'));
    document.getElementById('tab-' + category).classList.add('is-active');

    // Filter Table Rows
    const rows = document.querySelectorAll('.ps-table-row');
    rows.forEach(row => {
      if (category === 'all' || row.classList.contains('row-' + category)) {
        row.style.display = 'grid';
      } else {
        row.style.display = 'none';
      }
    });
  }
</script>