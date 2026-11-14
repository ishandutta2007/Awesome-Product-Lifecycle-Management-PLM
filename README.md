# Awesome-Product-Lifecycle-Management-PLM

# Awesome Product Lifecycle Management (PLM)

> A curated list of top Product Lifecycle Management (PLM) platforms — both SaaS/Hosted commercial enterprise suites and open-source alternatives for managing product data, bills of materials, engineering changes, and quality across the lifecycle.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Siemens Teamcenter](#siemens-teamcenter)
  - [PTC Windchill](#ptc-windchill)
  - [Dassault ENOVIA](#dassault-enovia)
  - [Autodesk Fusion 360 Manage](#autodesk-fusion-360-manage)
  - [Arena PLM](#arena-plm)
  - [Centric Software](#centric-software)
  - [Oracle Agile PLM](#oracle-agile-plm)
- [Open-Source Software](#-open-source-software)
  - [beCPG](#becpg)
  - [Aras Innovator (Community Edition)](#aras-innovator-community-edition)
  - [DocDokuPLM](#docdokuplm)
  - [Cascadia PLM](#cascadia-plm)
  - [GitPLM](#gitplm)
  - [PLMore](#plmore)
  - [OpenPLM](#openplm)
  - [InvenTree](#inventree)
  - [Odoo PLM](#odoo-plm)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Product Lifecycle Management platforms. These are not open-source but are included as reference points for feature comparison.

| Platform | Target Focus | Company Size (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier / Trial Limit |
|---|---|---|---|---|
| **Oracle Agile PLM (Fusion Cloud PLM)** | Legacy & cloud PLM for discrete manufacturing & supply chains | ~$57.4B Revenue (FY2025) / ~$460B+ Market Cap | $6,545/Application User (one-time perpetual license + $1,439.90/yr annual support for Agile Product Collaboration module) | No free trial for Agile PLM application; 30-day trial ($300 cloud credits) for general Oracle Cloud Infrastructure |
| **Siemens Teamcenter (Teamcenter X)** | Enterprise PLM for discrete manufacturing & global engineering | ~€75.9B (~$82B) Siemens Group Revenue / ~€140B+ Market Cap | $165/user/month (Teamcenter X Essentials, billed annually at $1,980/user/yr) | 30-day free trial with pre-configured cloud industry environments (BOM, CAD, change management) |
| **Autodesk Fusion Manage** | Cloud PLM for mid-market product development & BOM workflows | ~$6.1B Revenue (FY2025) / ~$55B–$60B Market Cap | $100/user/month (billed annually at $1,200/user/yr; Flex tokens available at 4–8 tokens/day; Contributor seats at ~$250/yr) | No self-service free trial; 30-day proof-of-concept / evaluation tenant upon request via sales |
| **Dassault ENOVIA (3DEXPERIENCE)** | Enterprise PLM deeply integrated with CATIA & SOLIDWORKS | ~€6.0B (~$6.7B) Revenue (FY2024) / ~$38B–$42B Market Cap | $115/user/month ($345/user/quarter for 3DSwymer/platform collaboration roles; ~$2,900+/user/yr for core governance/PLM) | No open self-service free trial; vendor-assisted sales proof-of-concept (PoC) & 3-month structured Drive-to-Trial programs |
| **PTC Windchill (Windchill+)** | Enterprise PLM with CAD & multi-CAD engineering depth | ~$2.74B Revenue (FY2025) / ~$21B Market Cap | ~$250/user/month (~$3,000/user/year for standard author seats) | No core PLM free trial; 15-day guided trial for Windchill Navigate & 30-day trial for Windchill Risk & Reliability |
| **Arena PLM (PTC)** | Cloud PLM & QMS for high-tech electronics & medical devices | Subsidiary of PTC ($2.74B rev / ~$21B cap); acquired for $715M | ~$100/user/month (Launch tier starting at ~$1,200/user/year; typical entry contract ~$10,000/yr minimum spend) | 10-day free trial (self-guided evaluation for BOM, Change, and Document Management; no credit card required) |
| **Centric Software (Centric PLM)** | Purpose-built PLM for fashion, retail, footwear, luxury & CPG | ~$120M–$235M Revenue (Subsidiary majority-owned by Dassault Systèmes) | ~$150/user/month (subscription tier based on user roles and enterprise modules; typical deployments quote annual contracts) | No free trial; interactive custom product demos and guided enterprise walkthroughs available upon request |
| **Propel Software (Propel PLM)** | Salesforce-native PLM, QMS, and PIM for commercial & engineering alignment | ~$25M–$50M Revenue / $48M+ VC Funding (Backed by Salesforce Ventures) | $73/user/month (billed annually; full PLM & QMS suites start upwards of $250/user/month or $3,000/user/yr) | No free trial; live personalized demonstrations and proof-of-concept sandbox environments upon request |

---

## 🟩 Open-Source Software

Self-hosted, community-driven Product Lifecycle Management tools. The open-source ecosystem spans **industry-specific CPG PLM**, **open-core enterprise platforms**, **modern digital thread applications**, **Git-native PLM**, and **lightweight part/BOM managers**.

### beCPG
**Stack:** Java 21 / Spring / Alfresco / Solr / PostgreSQL | **License:** LGPL v3 (Community Edition)
beCPG is an all-in-one open-source PLM built specifically for **food, beverage, and cosmetics** manufacturers, used by more than 120 manufacturers daily [citation:10]. Its key differentiator is **deterministic calculation engines** for nutrition, labelling, regulatory compliance, and costs—AI assists by searching, reading, and drafting, but a person accepts or rejects each proposal [citation:10]. The Community Edition covers product data, formulation, labelling, regulatory compliance, packaging, specifications, quality, projects, and supplier collaboration. It supports **multi-site, multi-brand, and multi-country deployments** with very large portfolios, and can be hosted on your own servers or any cloud with Docker or Kubernetes [citation:10]. Enterprise Edition is available via subscription for additional support and features.
**Best for:** Food and cosmetics manufacturers wanting a turnkey open-source PLM with regulatory compliance built in, accepting that it is not designed for mechanical or electronic engineering driven by CAD [citation:10].

### Aras Innovator (Community Edition)
**Stack:** .NET / SQL Server | **License:** Open core (free community edition)
Aras Innovator is an open-core enterprise PLM platform with no license fees for the core product, monetizing through optional support subscriptions (Aras Unlimited) [citation:4]. It provides BOM management, change management, program management, quality planning (FMEA, Control Plan, CAPA), and CAD integrations for all major CAD systems [citation:4]. The platform achieved a **four-star CMII certification** rating for configuration management, and is described as delivering "high end PLM systems" capabilities "at a fraction of the price and risk" [citation:4]. Community solutions expand the ecosystem, and it is frequently evaluated alongside Windchill and Teamcenter [citation:2][citation:11].
**Best for:** Mid-size to large manufacturers wanting enterprise-grade PLM capabilities without per-user license fees, accepting the implementation and configuration effort of an open-core platform.

### DocDokuPLM
**Stack:** Java / (Check repository) | **License:** AGPL v3
DocDokuPLM is a high-end open-source PLM solution with a **cloud-native architecture** designed for Kubernetes, edge, or cloud deployment [citation:3][citation:7]. Key features include document management (version control, workflows, templates, links), product structure with search and filters, **product configuration** (effectivities, alternatives, substitutes), **Bill of Materials**, process management with workflow and task management, change management for tracking modifications, and **WebGL-based data visualization** for exploring product structures in the browser [citation:3][citation:7]. The flexible architecture lets teams configure product object types, attributes, and relationships without deep developer overhead [citation:11].
**Best for:** Manufacturers wanting a modular, cloud-native open-source PLM with strong document and product structure management, particularly those needing flexible data models for engineering change control [citation:11].

### Cascadia PLM
**Stack:** TypeScript / Next.js / PostgreSQL | **License:** Open Source (GitHub)
Cascadia is a modern **Digital Thread application** designed to replace traditional low-code PLM platforms, listed as the top open-source PLM in a 2026 comparison [citation:2][citation:5]. Key item types include Parts, Documents, Change Orders (ECOs), Requirements, Tasks, Test Plans/Cases, Work Instructions, Issues, Software configuration items, Physical Parts (digital twin records), and Work Orders for manufacturing execution [citation:5]. It includes **RBAC user and role management**, lifecycle and workflow configuration, background job monitoring, and a health check endpoint [citation:5]. The service layer centralizes business logic, with support for checkout to ECO branches and version resolution at specific commit contexts [citation:5].
**Best for:** Hardware engineering teams wanting a modern, self-hosted digital thread application with multi-level BOM, enforced lifecycles, and ECO coordination, accepting the TypeScript/Next.js stack requirements.

### GitPLM
**Stack:** Git-based | **License:** Open Source
GitPLM is an open-source PLM that keeps **manufacturing data and designs in Git**, available for Linux, Windows, and macOS [citation:2]. It is positioned for teams that want version-controlled product data without a separate database or web platform, leveraging Git's native branching, history, and diff capabilities for engineering artifacts.
**Best for:** Technical engineering teams already using Git workflows who want PLM data versioned alongside code and designs, accepting a CLI/Git-native rather than web-UI approach.

### PLMore
**Stack:** Web-based | **License:** Open Source
PLMore describes itself as open-source PLM software and an alternative to Windchill and Teamcenter, with a web interface [citation:2]. It is listed among open-source PLM options in a 2026 comparison, though detailed feature documentation is limited compared to established projects.
**Best for:** Teams exploring a web-based open-source PLM alternative to enterprise suites, with careful evaluation of maturity and feature coverage before adoption.

### OpenPLM
**Stack:** Python / Django | **License:** GPLv3
OpenPLM provides core PLM functionality: part definition, BOM, document management, and versioning, with support for hierarchical structures, change history, and external document attachments [citation:11]. It is suitable for discrete manufacturing where traceability matters, and is positioned for small to mid-sized manufacturers transitioning from file folders and spreadsheets [citation:11].
**Best for:** Small to mid-sized discrete manufacturers wanting a straightforward open-source PLM for parts, BOMs, and revision control.

### InvenTree
**Stack:** Python / Django | **License:** MIT
InvenTree is primarily an inventory and BoM management system, but its strong API and part hierarchy make it a good **lightweight PLM companion** for small teams needing structure without full enterprise overhead [citation:11]. It handles parts, assemblies, and simple BoMs with a REST API for integration.
**Best for:** Startups and small shops wanting lightweight part and BOM management with API integration, accepting that it is not a full PLM suite.

### Odoo PLM
**Stack:** Python / PostgreSQL | **License:** LGPLv3 (Community)
Odoo's PLM app (Community edition) tracks revisions, changes, and engineering documents directly against inventory, BOMs, and work orders [citation:11]. It does not have all high-end PLM features, but the tight ERP link makes it practical for machine shops already using Odoo for ERP or inventory management [citation:11].
**Best for:** Odoo ERP users wanting PLM integrated with their existing inventory and manufacturing workflows, accepting a lighter feature set than dedicated PLM platforms.

---

## 📊 Comparison at a Glance

| Software | License | Stack | BOM/Change | CAD Integration | Industry Focus | Self-Hosted | Best For |
|----------|---------|-------|------------|-----------------|----------------|-------------|----------|
| **Siemens Teamcenter** | Proprietary | Cloud/On-prem | ✅ Deep | ✅ Broad | Discrete manufacturing | (On-prem) | Enterprise global PLM |
| **PTC Windchill** | Proprietary | Cloud/On-prem | ✅ | ✅ Creo | Discrete manufacturing | (On-prem) | CAD-integrated enterprise |
| **beCPG** | LGPL v3 | Java/Spring | ✅ | ❌ | Food & cosmetics | ✅ | CPG regulatory PLM |
| **Aras Innovator** | Open core | .NET/SQL | ✅ CMII 4-star | ✅ All major CAD | Discrete manufacturing | ✅ | Enterprise PLM no license fee |
| **DocDokuPLM** | AGPL v3 | Java/Cloud-native | ✅ | (Viewer) | General discrete | ✅ | Modular cloud-native PLM |
| **Cascadia** | Open Source | TypeScript/Postgres | ✅ ECOs | (Check) | Hardware engineering | ✅ | Modern digital thread |
| **GitPLM** | Open Source | Git | (Git-based) | (Check) | General | ✅ (Git) | Git-native product data |
| **OpenPLM** | GPLv3 | Python/Django | ✅ | (Check) | Small discrete | ✅ | Lightweight parts + BOM |
| **InvenTree** | MIT | Python/Django | (Simple BoM) | ❌ | Inventory adjunct | ✅ | Parts + BOM API |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Product Lifecycle Management (PLM) tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between **industry-specific PLM** (beCPG for food/cosmetics with deterministic regulatory engines [citation:10]), **open-core enterprise platforms** (Aras Innovator with CMII-certified change management and no license fees [citation:4]), **modern digital thread applications** (Cascadia with ECO branches and physical part traceability [citation:5]), and **lightweight part/BOM managers** (InvenTree, OpenPLM [citation:11]). **beCPG** and **Aras Innovator** represent the two strongest open-source foundations for production use in their respective domains, while **Cascadia** is a notable modern entrant for hardware teams wanting a self-hosted digital thread.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
