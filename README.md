# Liberty Energy (liberty-oilfield-services)

Profile for **Liberty Energy Inc** (NYSE: LBRT), formerly Liberty Oilfield Services,
in the API Evangelist network. Fortune 1000.

Liberty is a Denver, Colorado onshore oilfield services company and one of the
largest hydraulic fracturing providers in North America. It is now actively
pivoting from a pure completions pure-play into a hybrid completions plus
distributed-power company aimed at supplying behind-the-meter natural gas
generation to hyperscale data centers and AI infrastructure via its subsidiary
**Liberty Power Innovations (LPI)**.

## Snapshot

| Field | Value |
|---|---|
| Legal name | Liberty Energy Inc |
| Former name | Liberty Oilfield Services |
| Ticker | NYSE: LBRT |
| Headquarters | 950 17th Street, Suite 2400, Denver, CO 80202 |
| Founded | 2011 |
| IPO | January 2018 |
| Founder | Chris Wright (left 2025 to become 17th US Secretary of Energy) |
| CEO | Ron Gusek (President & CEO) |
| CFO | Michael Stock |
| 2025 revenue | $4.01B |
| 2025 net income | $147.87M |
| Fortune rank | F1000 |

## Business segments

1. **Completion Services** - hydraulic fracturing, wireline, sand and logistics
   (PropX, Freedom Proppant). Second-largest frac provider in North America after
   the December 2020 OneStim acquisition from Schlumberger.
2. **Liberty Power Innovations (LPI)** - launched April 2023. Distributed
   natural-gas power generation, CNG fueling, field gas processing, modular
   generation for baseload/backup/peak, sold as **Power as a Service**.
3. **Technology & Manufacturing** - digiTechnologies (electric + hybrid fleets),
   Liberty Advanced Equipment Technology (LAET), production / engineering /
   maintenance / emissions services.

## Liberty Power: the data center & AI pivot

LPI started as vertical integration of fueling for Liberty's own frac fleets.
It is now being marketed as dispatchable on-site power for hyperscale data
centers and AI compute build-outs.

| Date | Counterparty | Scope |
|---|---|---|
| 2025-03 | IMG Energy Solutions | Acquisition extending LPI's distributed power footprint |
| 2025-07 | Oklo Inc | Next-gen integrated power solution (advanced nuclear + nat gas) |
| 2026-01 | Vantage Data Centers | Strategic partnership to develop and operate **1 GW** of power for next-generation data centers |
| 2026-05 | Bergen Engines | Over **500 MW** of on-site generation capacity for large-scale data center developments |

Related strategic investments:

- **Fervo Energy** (Jul 2022) - next-generation enhanced geothermal.
- **Natron Energy** (Sep 2022) - sodium-ion battery manufacturing.

## Proprietary platforms (not public APIs)

| Platform | Purpose |
|---|---|
| FracTrends | Viewer over a 60,000+ well database for frac optimization |
| Sentinel | Sand/proppant logistics forecasting platform |
| digiTechnologies | Modular electric/hybrid frac fleet control with "advanced AI" |
| digiFrac | Fully electric frac pump fleet (field tested 2021) |
| digiPrime | Hybrid natural-gas frac fleet |
| digiFleets | Fleet family delivering "50% lower emissions vs. conventional Tier IV diesel" |

These are operational platforms exposed to customers through portals and
post-job reports - not programmatic, no SDKs, no OpenAPI.

## Founder note: Chris Wright

Chris Wright founded Liberty in 2011 and led it through the 2018 IPO, the
OneStim acquisition, and the launch of Liberty Power Innovations. In 2025 he
was confirmed as the **17th United States Secretary of Energy** in the Trump
administration and exited the company. **Ron Gusek** is now President and CEO.

## Public developer surface

| Surface | Status |
|---|---|
| Public APIs | 0 |
| OpenAPI specs | 0 |
| SDKs | 0 |
| Developer portal | None |
| GitHub org | None discoverable (github.com/libertyenergy returns 404) |
| Status page | None public |
| RSS / changelog | None public |

Liberty Energy operates entirely as a physical-services + power-infrastructure
company; it does not publish a developer surface. This repository documents
the organization, its segments, the Liberty Power pivot, and its proprietary
operational software so the API Evangelist network has a complete corporate
record even though no API artifacts exist to generate.

## Locations

**HQ:** Denver, CO. **Regional offices:** Houston, Dallas/Plano, Oklahoma
City, Calgary. **Basin offices:** Midland (Permian), DJ Basin (CO),
Powder River (WY), Williston (Bakken), Farmington (NM), Vernal (UT),
South Texas (Eagle Ford), Shreveport (Haynesville), Grande Prairie (AB),
Red Deer (AB), Whitefish (MT).

## Files in this repo

- `apis.yml` - APIs.yml profile (org-only; `apis: []`).
- `README.md` - this file.

No `openapi/`, `asyncapi/`, `capabilities/`, `rules/`, `examples/`,
`json-schema/`, `json-structure/`, `json-ld/`, `vocabulary/`, `plans/`,
`rate-limits/`, or `finops/` folders are generated, in line with the
run-pipeline rule against creating empty/placeholder artifacts for
providers with no public API surface.
