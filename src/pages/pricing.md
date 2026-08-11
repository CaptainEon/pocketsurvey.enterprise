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
layout: layouts/component-page.html
permalink: /pricing/
eleventyExcludeFromCollections: false
content_blocks:
  # 1. Page Hero Banner
  - _type: components/hero
    background_color: '#FAFAFA'
    heading:
      heading_text: Transparent Enterprise Licensing Built for Scale
      heading_gradient_color: '#2563EB'
    subheading:
      markdown_content: >-
        Complete mobile surveying workflows with direct automated data export into your core asset management system. Simple per-user pricing with free training and dedicated support included.
      color: '#52525B'
    image:
      image_path: /assets/images/undraw-online-test.svg
      alt_text: Enterprise Pricing & Licensing

  # 2. Main Enterprise Pricing Card (£175 Tier)
  - _type: components/left-right
    id_anchor: enterprise-plan
    background_color: '#ffffff'
    heading:
      heading_text: All-Inclusive License — £175 per user / month
      color: '#0F172A'
    text:
      markdown_content: >-
        Designed for housing associations, local councils, surveying practices, and commercial FM teams requiring rigorous compliance standards and enterprise database controls. Free onboarding and ongoing support included as standard.


        ### Housing Stock Condition Suite
        * **Decent Homes Standard:** Complete mobile auditing for social housing stock compliance.
        * **SHQS & WHQS:** Dedicated inspection modules for Scottish and Welsh Housing Quality Standards.
        * **HHSRS Audits:** Track damp, mould, and tenant safety hazards seamlessly on mobile devices.


        ### Commercial Planned Maintenance Suite
        * **RICS & SFG20 Schedules:** Standardised building surveys and maintenance models.
        * **NHS 6-Facets Audits:** Statutory healthcare estate and risk assessments.
        * **30–50 Year CapEx Forecasting:** Automated component replacement and expenditure profiles.
      color: '#334155'
    image:
      image_path: /assets/images/undraw-startup.svg
      alt_text: Enterprise Software Offerings
    flipped: false
    button:
      _type: components/buttons/primary
      button_text: Book Enterprise Demo
      button_icon: fa-solid fa-arrow-right
      button_link: /enquiry.htm
      background_color: '#2563EB'
      hover_brightness: 0.85
      text_color: '#ffffff'

  # 3. Direct System Integrations (NEC, Capita, Civica, Keystone, MRI)
  - _type: components/left-right
    id_anchor: system-integrations
    background_color: '#F8FAFC'
    heading:
      heading_text: Direct Asset System CSV Exports
      color: '#0F172A'
    text:
      markdown_content: >-
        PocketSurvey acts as a practical, high-speed mobile data capture engine that generates pre-formatted CSV exports ready for direct import into leading housing and asset management software.


        * **NEC Software Solutions:** Direct CSV field mapping for Housing Stock modules.
        * **Capita Housing:** Structured CSV tables ready for stock condition import.
        * **Civica Horizon & Housing:** Seamless portfolio data formatting without manual re-keying.
        * **Keystone Asset Management:** Full compatibility with long-term capital planning tools.
        * **MRI Software / Real Asset Management:** Automated field mapping for commercial and housing assets.
      color: '#334155'
    image:
      image_path: /assets/images/undraw-hello.svg
      alt_text: Enterprise System Integrations
    flipped: true
    button:
      _type: components/buttons/primary
      button_text: Request Sample Export
      button_icon: fa-solid fa-file-csv
      button_link: /enquiry.htm
      background_color: '#2563EB'
      hover_brightness: 0.85
      text_color: '#ffffff'

  # 4. Bespoke App Studio
  - _type: components/left-right
    id_anchor: bespoke-apps
    background_color: '#ffffff'
    heading:
      heading_text: Custom Application Development & Exporters
      color: '#0F172A'
    text:
      markdown_content: >-
        Need a custom inspection form, bespoke scoring matrix, or proprietary database exporter? Our UK development team builds tailored mobile apps engineered to your exact council or housing association guidelines.


        * **Custom Inspection Logic:** Tailored fields, scoring matrices, and conditional inspection branching.
        * **Bespoke Data Exporters:** Custom-coded CSV, XML, or JSON exports matching your exact database schema.
        * **Branded Deliverables:** Custom PDF report templates styled precisely to your corporate guidelines.
      color: '#334155'
    image:
      image_path: /assets/images/undraw-startup.svg
      alt_text: Bespoke Mobile App Development
    flipped: false
    button:
      _type: components/buttons/primary
      button_text: Discuss Custom App
      button_icon: fa-solid fa-comments
      button_link: /enquiry.htm
      background_color: '#2563EB'
      hover_brightness: 0.85
      text_color: '#ffffff'
---