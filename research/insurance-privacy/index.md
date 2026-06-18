---
layout: page
title: Health Insurance Data Privacy Research
subtitle: Working paper. Not for public distribution.
published: true
---

This page is shared with potential collaborators only.
Please do not share the URL publicly.

## Status

Early stage working paper. Georgia primary case complete.
Massachusetts and Florida comparison pending.

## What we have so far

- Document analysis of 10 privacy policies across 5 insurers
- Readability scoring across all documents
- Opt-out step count coding across 17 pathways
- Three interactive visualizations

### Scoring Flowchart
<iframe
  src="consent-flow.html"
  width="100%"
  height="500"
  style="border: 1px solid #2a2a2a; border-radius: 6px;">
</iframe>


### Policy Data Scope and Destination
<iframe src="/research/insurance-privacy/data_scope_destinations.html" 
        width="100%" height="700" 
        frameborder="0"
        style="border: 1px solid #e0e0e0; border-radius: 6px;">
</iframe>

## Findings summary

## Opt-Out Step Count Results: Georgia Primary Case

Coded June 17, 2026 using claude-sonnet-4-6 with structured codebook.
17 pathways identified across 10 documents from 5 insurers.

| Insurer | Document | Pathway | Steps | Flags | Asymmetry |
|---|---|---|---|---|---|
| Aetna | Web Privacy Policy | Email contact for privacy inquiries | 2 | Insurer may decline | No |
| Anthem BCBS | HIPAA Notice | Opt-out of PHI sharing with health information exchanges | 2 | Prior disclosures cannot be undone | No |
| Anthem BCBS | HIPAA Notice | Opt-out of unspecified PI sharing activities | 2 | Opt-out not available for this data type | No |
| Anthem BCBS | HIPAA Notice | Cancel written authorization for PHI use | 1 | Prior disclosures cannot be undone | Yes |
| Anthem BCBS | HIPAA Notice (Spanish) | Opt-out of PHI disclosure to health info exchanges | 2 | Insurer may decline | No |
| Anthem BCBS | HIPAA Notice (Spanish) | Opt-out of PI use for certain activities | 2 | Insurer may decline | No |
| Anthem BCBS | HIPAA Notice (Spanish) | Revoke written authorization for PHI use | 1 | Prior disclosures cannot be undone | Yes |
| Cigna | Data Sharing Notice | Provider Access Data Sharing Opt-Out | 2 | Default opt-in; prior disclosures cannot be undone | Yes |
| Cigna | Data Sharing Notice | Third-Party App Data Authorization | 0 | No opt-out available; prior disclosures cannot be undone; insurer may decline | No |
| Cigna | Global Health Benefits Notice | Marketing use of PHI | 0 | No opt-out available; default opt-in | Yes |
| Cigna | HIPAA Notice | Opt-out of disclosure to individuals involved in care | 2 | Default opt-in | Yes |
| Cigna | GLB Notice | No opt-out pathway described | 0 | No opt-out available : federal law cited | No |
| Humana | HIPAA Notice | Opt-out of health-related benefit contacts | 1 | Default opt-in; mechanism not described | No |
| UnitedHealthcare | Web Privacy Policy | Location Data Opt-Out (Mobile Device) | 1 | Prior disclosures cannot be undone; loss of functionality | No |
| UnitedHealthcare | HIPAA Notice | Revoke written permission for special uses | 3 | Prior disclosures cannot be undone; insurer may decline | Yes |
| UnitedHealthcare | HIPAA Notice | Request limit on use or sharing of health information | 3 | Insurer may decline | No |
| UnitedHealthcare | HIPAA Notice | Request confidential communications change | 3 | None | No |

**0 steps** = no opt-out mechanism described.
**Asymmetry** = opt-out requires more steps than opt-in, a documented dark pattern (Nouwens et al., 2020).  
All pathways coded from document text only. Steps not described in documents were not inferred.

## Visualizations

<iframe src="readability_chart_grouped.html" 
        width="100%" height="600" 
        frameborder="0">
</iframe>
<br>
## Analysis Source Code

### Readability Scoring
<iframe src="insurance_privacy_readability_scoring.html" 
        width="100%" height="600" 
        frameborder="0">
</iframe>

### Opt-Out Step Coding
<iframe src="opt_out_step_coding.html" 
        width="100%" height="600" 
        frameborder="0">
</iframe>


## Support this research

If you want to support expansion to Massachusetts and Florida,
or additional insurer coverage, please consider sponsoring.

<iframe src="https://github.com/sponsors/victoriamccray/card" title="Sponsor victoriamccray" height="225" width="600" style="border: 0;"></iframe>

## Access & Sharing

This is a controlled working draft intended for:
- research collaborators
- potential funders and sponsors
- invited reviewers

This page is intentionally not indexed and not linked from the main site navigation.

If you were forwarded this link, please do not redistribute without permission.
