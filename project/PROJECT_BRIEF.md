# Project Brief

## Engagement Details
| Field | Detail |
|---|---|
| Project ID | MTL-XF-016 |
| Project Title | Community Safety, Crime Demand & Resource Allocation Intelligence |
| Client | Confidential Community Safety Partnership |
| Sector | Public Safety / Local Government / Policing |
| Duration | 8 weeks |
| Recommended Team Size | 6–8 |
| Primary Sponsor | Director of Community Safety |
| Senior Stakeholders | Community Safety Lead, Police Partnership Lead, Violence Reduction Lead, Local Authority Performance Lead, Safeguarding/Prevention Lead, Data Governance Lead, Insight Lead |
| Primary Dataset | Home Office Police Recorded Crime Open Data — Police Force Area tables, year ending March 2013 onwards |

## 1. Client Situation
The partnership has limited neighbourhood and prevention resources, but current reporting does not distinguish persistent demand, emerging offence patterns, police-force-area variation and recording effects well enough to support targeted intervention.

## 2. Business Decision
> **Which crime-demand patterns and areas should receive the earliest multi-agency investigation or prevention attention, and what evidence should be monitored before resources are reallocated?**

## 3. Agreed Objectives
1. Create a governed long-run crime-demand dataset with explicit offence and geography definitions.
2. Separate persistent changes from one-period spikes and make recording/methodology caveats visible.
3. Identify offence/area combinations that warrant multi-agency investigation using transparent materiality rules.
4. Avoid stigmatising communities or presenting recorded-crime counts as total victimisation.
5. Provide a decision-support view for prevention and partnership planning.

## 4. Key Business Questions
1. Which offence categories show persistent growth or decline?
2. Which force areas show material divergence from longer-term patterns?
3. Where do volume and growth rate tell different stories?
4. Which offence/area combinations remain elevated across multiple periods?
5. Which methodology/recording changes could explain apparent trend breaks?
6. What evidence should trigger prevention investigation versus routine monitoring?

## 5. Cross-Functional Roles
| Role | Minimum expected output |
|---|---|
| Business Analyst | Define partnership decision, stakeholder needs, prevention use cases and acceptance criteria. |
| Data Governance Analyst | Govern offence taxonomy, geography, time-period definitions, lineage and DQ rules. |
| Data Engineer | Prepare reproducible extraction and longitudinal analytical model from Home Office tables. |
| Community Safety/Data Analyst | Own trend, persistence, offence-mix and area comparison analysis. |
| BI Developer | Build partnership-level executive and diagnostic views. |
| GIS/Spatial Analyst | Provide cautious area mapping where source geography supports it. |
| Risk/Assurance Analyst | Challenge denominators, labels, thresholds and unintended consequences. |

## 6. Minimum Delivery Standard
Traceable requirements; governed definitions/lineage; preserved raw data; reproducible transformation; data-quality/reconciliation evidence; domain-specific analysis; transparent decision logic; governed BI; UAT; handover; visible collaboration.

## 7. Constraints
- Police-recorded crime is affected by reporting, recording practices and police activity.
- Recorded crime is not equivalent to total crime or neighbourhood danger.
- Area comparisons need appropriate denominators/context and must avoid stigmatising labels.
- Changes in offence definitions or recording practice can create artificial trend breaks.
- The project supports planning, not operational policing or individual risk assessment.

## 8. Agreed Success Criteria
- All offence categories used in trend analysis are mapped to documented source definitions.
- At least one methodology/recording continuity review is completed before interpreting long-term trend breaks.
- Priority flags require persistence across more than one reporting period unless a documented exception is approved.
- No area is labelled dangerous/high risk solely from raw recorded-crime volume.
- At least five dashboard figures reconcile to the source table for selected offence/area periods.
- Volume and percentage-change views are both provided to prevent small-base distortion.

## 9. Out of Scope
Core delivery excludes confidential personal data, paid production infrastructure, automated operational decisions and unsupported causal inference.

## 10. Reproducibility Definition
A reviewer should be able to clone the team repository, obtain the approved source data, run the documented workflow and reproduce curated outputs and validation evidence without undocumented manual changes.
