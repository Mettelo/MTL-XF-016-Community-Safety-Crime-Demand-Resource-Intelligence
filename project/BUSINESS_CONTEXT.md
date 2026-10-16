# Business Context

## Business Problem

The Community Safety Partnership has limited prevention, neighbourhood and analytical resources, but current reporting is largely descriptive. It can show how many crimes were recorded, but it does not consistently distinguish persistent demand from short-term spikes, large-volume areas from fast-growing small bases, or genuine trend changes from shifts in recording practice.

This creates a resource-allocation problem. Without a governed longitudinal view, the partnership risks focusing on the biggest numbers rather than the most important changes, or stigmatising areas because they have high recorded volume without understanding the wider context.

The business problem is therefore to create a repeatable evidence base that helps the partnership identify which offence-area combinations deserve deeper multi-agency investigation and which changes are not strong enough to justify intervention.

## Required Delivery Response

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

## How the Client Will Use the Output

The finished product should support a Community Safety Partnership meeting. Leaders should be able to see, for example, that one offence category has increased across several periods in a particular area, compare that change with the overall force trend, and decide whether a multi-agency prevention review is warranted.

The product should help prioritise investigation and monitoring. It must not label an area “dangerous” or an individual/group “high risk” based only on recorded-crime data.

## Client
**Confidential Community Safety Partnership**

## Problem
The partnership has limited neighbourhood and prevention resources, but current reporting does not distinguish persistent demand, emerging offence patterns, police-force-area variation and recording effects well enough to support targeted intervention.

## Decision Owner
**Director of Community Safety**

## Stakeholders
Community Safety Lead, Police Partnership Lead, Violence Reduction Lead, Local Authority Performance Lead, Safeguarding/Prevention Lead, Data Governance Lead, Insight Lead

## Decision
**Which crime-demand patterns and areas should receive the earliest multi-agency investigation or prevention attention, and what evidence should be monitored before resources are reallocated?**

## Role Responsibilities
| Role | Required contribution |
|---|---|
| Business Analyst | Define partnership decision, stakeholder needs, prevention use cases and acceptance criteria. |
| Data Governance Analyst | Govern offence taxonomy, geography, time-period definitions, lineage and DQ rules. |
| Data Engineer | Prepare reproducible extraction and longitudinal analytical model from Home Office tables. |
| Community Safety/Data Analyst | Own trend, persistence, offence-mix and area comparison analysis. |
| BI Developer | Build partnership-level executive and diagnostic views. |
| GIS/Spatial Analyst | Provide cautious area mapping where source geography supports it. |
| Risk/Assurance Analyst | Challenge denominators, labels, thresholds and unintended consequences. |

## Evidence Chain
**Requirement → governed definition → transformation → quality control → metric/analysis → decision insight → recommendation → UAT**
