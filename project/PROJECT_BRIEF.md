# Project Brief

## 1. Business Problem

The Community Safety Partnership has limited prevention, neighbourhood and analytical resources, but current reporting is largely descriptive. It can show how many crimes were recorded, but it does not consistently distinguish persistent demand from short-term spikes, large-volume areas from fast-growing small bases, or genuine trend changes from shifts in recording practice.

This creates a resource-allocation problem. Without a governed longitudinal view, the partnership risks focusing on the biggest numbers rather than the most important changes, or stigmatising areas because they have high recorded volume without understanding the wider context.

The business problem is therefore to create a repeatable evidence base that helps the partnership identify which offence-area combinations deserve deeper multi-agency investigation and which changes are not strong enough to justify intervention.

## What the Team Needs to Do

The team is expected to build a community-safety demand and prioritisation solution.

The work should include:
- defining the partnership decision process and prevention use cases;
- standardising offence categories, reporting periods and geographic fields;
- building a reproducible longitudinal analytical model;
- documenting recording/methodology changes that could affect trends;
- analysing long-term offence trends and persistence;
- comparing raw volume with percentage/growth measures to avoid small-base distortion;
- identifying offence-area combinations that remain elevated across multiple periods;
- developing transparent investigation-priority rules;
- introducing valid denominators only where a compatible source is documented;
- building executive and diagnostic BI;
- completing reconciliation, assurance, UAT and handover.

## Practical Use Case

The finished product should support a Community Safety Partnership meeting. Leaders should be able to see, for example, that one offence category has increased across several periods in a particular area, compare that change with the overall force trend, and decide whether a multi-agency prevention review is warranted.

The product should help prioritise investigation and monitoring. It must not label an area “dangerous” or an individual/group “high risk” based only on recorded-crime data.

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
