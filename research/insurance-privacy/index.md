---
layout: page
title: Health Insurance Data Privacy Research
subtitle: Working paper. Not for public distribution.
published: true
---

## Overview

This working paper analyzes data collection, consent mechanics, and opt-out design in member-facing privacy policies from five major private insurers operating in Georgia: Anthem Blue Cross Blue Shield, UnitedHealthcare, Aetna, Cigna, and Humana.

The study focuses on how privacy rights are operationalized in practice through document-defined procedures, with attention to populations that may experience elevated exposure to insurer data systems due to structural vulnerability in health and social service contexts.

**Population of focus.** Adults with chronic conditions, including those with intersecting histories of system involvement such as incarceration, housing instability, and substance use disorder. These groups are overrepresented among Medicaid and marketplace enrollees in Georgia and may face disproportionate exposure to data-driven profiling, coverage determination systems, and consent architectures designed for high-trust, high-literacy users.

**Methods.** A systematic document analysis was conducted across ten member-facing privacy policies from the five insurers. Analysis was structured across three dimensions: consent mechanics, data scope, and readability.

Readability was assessed using Flesch-Kincaid Grade Level, Flesch Reading Ease, and SMOG index. Opt-out friction was operationalized as the number of discrete actions required for a member to exercise a stated privacy right, using a step-count framework adapted from Nouwens et al. (2020) and extended to include non-digital pathways.

AI-assisted coding was conducted using a structured codebook grounded in EDPB Guidelines 03/2022 on deceptive design patterns and the FTC (2022) report *Bringing Dark Patterns to Light*. All coding was constrained to document-described procedures; no behavioral inference was applied.

The data collection and sharing table below summarizes the data categories collected by each insurer and the entities with which that data may be shared, based on member-facing privacy documents reviewed in June 2026.

**Current findings.** In addition to HIPAA-covered health information, insurers collect a broad range of non-clinical data, including commercially available and third-party sourced information, device and behavioral data, and in some cases, demographic characteristics such as race, ethnicity, sexual orientation, and religious affiliation. Among the insurers reviewed, Humana is the only insurer that explicitly identifies the Medical Information Bureau (MIB), an industry-wide data-sharing consortium, as a source of member information.

The disclosures described in these documents extend well beyond healthcare operations. All five insurers permit disclosure of member data to law enforcement without requiring member consent, and three explicitly identify correctional institutions as potential recipients. All five also share data with life sciences and research organizations. Commercial recipients include advertising and analytics providers, credit bureaus, and corporate affiliates such as CVS Health (Aetna) and Evernorth (Cigna). Two insurers additionally reserve the right to transfer member data to acquiring entities as part of mergers, acquisitions, or other corporate transactions without obtaining member consent.

A cell marked "—" indicates that the practice is not described in the available documents; it should not be interpreted as evidence that the practice does not occur.

All ten documents exceed the AMA-recommended 6th-grade readability threshold for patient-facing health materials, with scores ranging from grade 6.7 to 18.4.

Across 17 coded opt-out pathways, five contained no documented opt-out mechanism. Six pathways exhibited consent asymmetry, where withdrawal of data use required more procedural steps than enrollment or authorization. Three pathways required multi-step written submissions in which insurers retain explicit discretion to deny requests.

**Next phase.** The next phase involves community-partnered validation of document-based findings against lived member experience. This phase will require IRB approval and is currently in partner identification. Collaboration is being pursued with university partners with IRB infrastructure and established community relationships in the Atlanta region.

This page is shared with potential collaborators only.
Please do not share the URL publicly.

## Status

Early stage working paper. Georgia primary case complete.
Massachusetts and Florida comparison pending.

## Current State

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
