# ESRC NIA: Proto-Institutional Governance of Advanced Air Mobility

[![GitHub Pages](https://img.shields.io/badge/docs-live-brightgreen)](https://polstavros.github.io/esrc-nia-proto-gov/)
[![ESRC](https://img.shields.io/badge/ESRC-New%20Investigator%20Award-blue)](https://www.ukri.org/councils/esrc/)

## Overview

This repository contains the complete ESRC New Investigator Award proposal for a research project examining **how governance emerges in proto-AAM ecosystems** before formal institutions stabilize. The project develops a process-relational theory of governance formation through empirical analysis of BVLOS drone operations in the UK.

**🌐 Live Site:** [https://polstavros.github.io/esrc-nia-proto-gov/](https://polstavros.github.io/esrc-nia-proto-gov/)

## Project Summary

**Title:** Governing Autonomous Air Mobility: Understanding and Enabling Governance Formation in Proto-Ecosystems

**Duration:** 40 months (June 2026 - October 2029)

**Award Type:** ESRC New Investigator Award

**Research Question:** How is governance accomplished in early AAM/BVLOS operations, where actors rely on dynamic actor-artefact-algorithm-rule configurations to coordinate safely and legitimately?

### Key Objectives

1. **O1 - Evidence:** Generate high-quality empirical evidence on governance formation in live BVLOS settings
2. **O2 - Conceptualisation:** Develop a process theory identifying mechanisms of coordination, justification and accountability
3. **O3 - Translation:** Co-design and validate three governance mechanisms with operators and intermediaries
4. **O4 - Uptake:** Support adoption through targeted capability development and policy engagement

## Repository Structure

```
esrc-nia-proto-gov/
├── _config.yml                  # Jekyll configuration
├── _data/
│   ├── nia_proposal.yml        # Sectioned proposal data (YAML)
│   └── nia_truth_table.yml     # Assessment criteria mapping
├── _layouts/
│   └── default.html            # Site layout template
├── index.md                     # Main proposal page
├── truth-table.md              # Truth table page
└── README.md                    # This file
```

## Site Features

### 📄 Full Proposal Page
- **Dynamic Content:** Rendered from structured YAML data
- **Comprehensive Sections:** Vision, Aim, Objectives, Context, Knowledge Gap, Conceptual Framework, Methodology, Work Packages, Outputs, Outcomes, Impact, Risks, Team, and Partners
- **Professional Styling:** Clean, academic design optimized for readability

### 📊 Truth Table Page
- **Quality Assurance:** Maps every proposal section to ESRC NIA assessment criteria
- **Criteria Coverage:** Originality (O), Research Design (R), Feasibility (F), Impact (I), Development (D), Environment (ENV)
- **Risk Rating:** Green/Amber/Red status indicators for each element
- **35+ Mappings:** Comprehensive coverage of all proposal components

## Technical Implementation

### Built With
- **Jekyll:** Static site generator
- **GitHub Pages:** Hosting and deployment
- **Liquid:** Templating engine for dynamic content
- **YAML:** Structured data format
- **Markdown:** Content authoring

### Data Architecture

The proposal is stored in **sectioned YAML format** for maximum flexibility:

```yaml
project:
  title: "Governing Autonomous Air Mobility"
  duration: "40 months"
  
vision: |
  Autonomous Air Mobility (AAM) is a national priority...
  
objectives:
  - code: "O1"
    title: "Evidence"
    description: "Generate high-quality empirical evidence..."
```

This structure enables:
- ✅ Easy updates without touching HTML
- ✅ Version control of content
- ✅ Reuse across multiple formats (web, PDF, presentations)
- ✅ Automated rendering with Jekyll/Liquid

## Work Packages

| WP | Title | Period | Lead | Deliverables |
|----|-------|--------|------|-------------|
| **WP1** | Discovery | M1-12 | PI | Evidence report, baseline dataset, episode typology |
| **WP2** | Mechanism Modelling | M12-24 | RIA | Mechanism catalogue, conceptual synthesis |
| **WP3** | Co-Design & Validation | M18-30 | PcL | Three validated governance mechanisms |
| **WP4** | Translation | M24-36 | PI | Policy briefs, training materials, publications |

## Key Outputs

- **O₁:** Drone Trilemma article + Governance Episode Vignettes
- **O₂:** Governance Toolkit & Methods Guide
- **O₃:** Executive Report + Drone Futures exhibition assets
- **O₄:** White Paper + Journal Paper 2 + UKDS dataset + Methods Note

## Impact Pathways

### Conceptual Impact
New process-relational theory of governance formation in proto-ecosystems

### Capacity-Building Impact
Adoption of three governance mechanisms strengthening organisational capability

### Instrumental Impact
Evidence contributions to CAP 722C and Airspace Modernisation Strategy through time-of-need engagement

## Partners

- **BMT / OD-RIC:** Controlled Living Laboratory access
- **ARPAS-UK:** Sector intermediary and capability-building platform
- **Cambridge Digital Innovation:** Policy translation and ecosystem coordination
- **SkyBound Rescuer:** Healthcare/emergency response use case

## Local Development

To run the site locally:

```bash
# Clone the repository
git clone https://github.com/PolStavros/esrc-nia-proto-gov.git
cd esrc-nia-proto-gov

# Install Jekyll (if not already installed)
gem install jekyll bundler

# Install dependencies
bundle install

# Serve the site
bundle exec jekyll serve

# View at http://localhost:4000/esrc-nia-proto-gov/
```

## Updates and Maintenance

### Updating Proposal Content

1. Edit `_data/nia_proposal.yml`
2. Commit and push changes
3. GitHub Pages automatically rebuilds (typically 1-2 minutes)

### Updating Truth Table

1. Edit `_data/nia_truth_table.yml`
2. Add/modify entries following the existing structure
3. Commit and push

### Styling Updates

1. Edit `_layouts/default.html`
2. Modify CSS within `<style>` tags
3. Commit and push

## Quality Assurance

✅ **ESRC Alignment:** All sections mapped to NIA assessment criteria  
✅ **Sectioned Structure:** Easy navigation and reference  
✅ **Professional Design:** Academic styling with clear typography  
✅ **Accessibility:** Clean markup, semantic HTML  
✅ **Version Control:** Full Git history of all changes  
✅ **Documentation:** Comprehensive README and inline comments  

## Citation

If referencing this work:

```
[Author Name] (2025). Governing Autonomous Air Mobility: Understanding and 
Enabling Governance Formation in Proto-Ecosystems. ESRC New Investigator 
Award Proposal. https://polstavros.github.io/esrc-nia-proto-gov/
```

## License

This proposal and documentation are provided for review and collaboration purposes. All intellectual property rights reserved.

## Contact

For inquiries about this research project, please contact via GitHub issues or through the repository owner.

---

**Last Updated:** November 2025  
**Status:** Proposal Development  
**Funding Scheme:** ESRC New Investigator Award
