---
layout: default
title: "ESRC NIA Proposal"
---

# {{ site.data.nia_proposal.project.title }}
## {{ site.data.nia_proposal.project.subtitle }}

**{{ site.data.nia_proposal.project.award_type }}**  
**Duration:** {{ site.data.nia_proposal.project.duration }}  
**Start Date:** {{ site.data.nia_proposal.project.start_date }}

---

## Vision

{{ site.data.nia_proposal.vision }}

---

## Aim

{{ site.data.nia_proposal.aim }}

---

## Objectives

{% for obj in site.data.nia_proposal.objectives %}
### {{ obj.code }}: {{ obj.title }}
{{ obj.description }}
{% endfor %}

---

## Context

{{ site.data.nia_proposal.context }}

---

## Knowledge Gap

{{ site.data.nia_proposal.knowledge_gap }}

---

## Conceptual Framework

{% for construct in site.data.nia_proposal.conceptual_framework.constructs %}
### {{ construct.name }}
{{ construct.description }}
{% endfor %}

---

## Methodology

**Design:** {{ site.data.nia_proposal.methodology.design }}  
**Setting:** {{ site.data.nia_proposal.methodology.setting }}

### Research Phases

{% for phase in site.data.nia_proposal.methodology.phases %}
#### {{ phase.name }}
{{ phase.activities }}
{% endfor %}

---

## Work Packages

{% for wp in site.data.nia_proposal.work_packages %}
### {{ wp.code }}: {{ wp.title }} ({{ wp.period }})

**Lead:** {{ wp.lead }}  
**Objectives:** {{ wp.objectives }}

**Activities:** {{ wp.activities }}

**Deliverables:** {{ wp.deliverables }}
{% endfor %}

---

## Outputs

{% for output in site.data.nia_proposal.outputs %}
- **{{ output.code }}:** {{ output.title }}
{% endfor %}

---

## Outcomes

### Short-Term Outcomes
{% for outcome in site.data.nia_proposal.outcomes.short_term %}
- {{ outcome }}
{% endfor %}

### Mid-Term Outcomes
{% for outcome in site.data.nia_proposal.outcomes.mid_term %}
- {{ outcome }}
{% endfor %}

### Late Outcomes
{% for outcome in site.data.nia_proposal.outcomes.late %}
- {{ outcome }}
{% endfor %}

### Legacy
{% for legacy in site.data.nia_proposal.outcomes.legacy %}
- {{ legacy }}
{% endfor %}

---

## Impact

**Conceptual Impact:**  
{{ site.data.nia_proposal.impact.conceptual }}

**Capacity-Building Impact:**  
{{ site.data.nia_proposal.impact.capacity_building }}

**Instrumental Impact:**  
{{ site.data.nia_proposal.impact.instrumental }}

---

## Risks and Mitigations

{% for risk in site.data.nia_proposal.risks %}
- **{{ risk.name }}:** {{ risk.mitigation }}
{% endfor %}

---

## Team

{% for member in site.data.nia_proposal.team %}
- **{{ member.role }}** ({{ member.fte }} FTE): {{ member.responsibilities }}
{% endfor %}

---

## Partners

{% for partner in site.data.nia_proposal.partners %}
- {{ partner }}
{% endfor %}

---

## Navigation

- [View Truth Table](/truth-table.html)
- [View on GitHub](https://github.com/PolStavros/esrc-nia-proto-gov)
