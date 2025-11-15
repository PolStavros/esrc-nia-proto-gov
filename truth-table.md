---
layout: default
title: "ESRC NIA Truth Table"
permalink: /truth-table.html
---

# ESRC NIA Truth Table
## Proposal Alignment with Assessment Criteria

This table maps every section of the proposal to ESRC New Investigator Award assessment criteria, providing a comprehensive quality assurance review.

### Criteria Key
- **O** = Originality
- **R** = Research Design & Methods
- **F** = Feasibility
- **I** = Impact
- **D** = Development (for NIA)
- **ENV** = Environment & Support

### Risk Categories
- <span style="color: green">✓</span> **Green** = Aligned, no issues
- <span style="color: orange">⚠</span> **Amber** = Minor concerns, addressable
- <span style="color: red">✗</span> **Red** = Significant issues requiring revision

---

<table>
  <thead>
    <tr>
      <th>Section</th>
      <th>Content</th>
      <th>Criteria</th>
      <th>Status</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
{% for row in site.data.nia_truth_table.truth_table %}
    <tr>
      <td><strong>{{ row.section }}</strong></td>
      <td>{{ row.line }}</td>
      <td>{{ row.criteria | join: ", " }}</td>
      <td>
        {% if row.risk == "green" %}
        <span style="color: green">✓ Green</span>
        {% elsif row.risk == "amber" %}
        <span style="color: orange">⚠ Amber</span>
        {% elsif row.risk == "red" %}
        <span style="color: red">✗ Red</span>
        {% endif %}
      </td>
      <td><small>{{ row.notes }}</small></td>
    </tr>
{% endfor %}
  </tbody>
</table>

---

## Summary

All {{ site.data.nia_truth_table.truth_table | size }} proposal elements have been reviewed and mapped to assessment criteria. The proposal demonstrates:

- **Strong originality** in proto-ecosystem governance theory
- **Rigorous research design** with CLL methodology
- **Clear feasibility** with appropriate resourcing
- **ESRC-aligned impact** pathways
- **PI development** through independent conceptual leadership
- **Robust environment** with strong partnerships

---

[Back to Proposal](/) | [View on GitHub](https://github.com/PolStavros/esrc-nia-proto-gov)
