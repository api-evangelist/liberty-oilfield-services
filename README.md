# Liberty Energy (liberty-oilfield-services)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
