# Data Guidance

## Approved Core Dataset

Use the Home Office **Police Recorded Crime and Outcomes Open Data Tables**.

Official source:
https://www.gov.uk/government/statistical-data-sets/police-recorded-crime-and-outcomes-open-data-tables

Approved core file:
**Police Force Area tables — year ending March 2013 onwards**.

## Why This Source Is Used

This file provides a long historical series suitable for:
- trend analysis;
- persistence analysis;
- offence-mix analysis;
- area comparison;
- monitoring changes over time.

It is much more manageable for this project than downloading the full Police.uk archive.

## What to Put in `data/raw/`

Store the original ODS file unchanged:

```text
data/raw/
└── home-office-police-recorded-crime-pfa-2013-onwards.ods
```

Do not replace the raw ODS with an exported CSV.

Processed tables can be written to `data/processed/`.

## Recommended Time Scope

Do not analyse the entire historical period unless the team has a clear reason.

Recommended core period:
- most recent **5 years** of comparable data.

Optional:
- extend to 10+ years for long-run context if offence definitions and methodology remain sufficiently comparable.

## Recommended Geographic Scope

The project should be manageable.

Choose one of:
- England & Wales overview with a limited set of priority force areas;
- one region and its police force areas;
- a selected group of comparable forces.

Document the selection rationale.

## Recommended Analytical Grain

Use a clearly documented:
**police force area × offence category × reporting period** grain.

Do not mix force-level and lower-geography data without an explicit model.

## Continuity & Methodology Rules

Before trend analysis:
- review offence-category changes;
- review recording/methodology notes;
- record discontinuities;
- flag periods that should not be compared directly.

## Denominators

Raw recorded-crime counts are acceptable for the core project.

If population-based rates are added:
- use a compatible official population source;
- document the population year/geography;
- do not mix denominator periods.

## Optional Extension

Teams may add Police.uk street-level data for a tightly scoped geographic extension, but this is optional and should not replace the Home Office frozen core dataset.
