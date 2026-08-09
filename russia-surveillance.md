<div align="center">

<img width="100%" src="assets/banner-russia-surveillance.svg" alt="RUSSIAN SURVEILLANCE APPARATUS"/>

</div>

| Metric | Value |
|---|---|
| SORM exporters identified | 8+ (Recorded Future, 2023) |
| Protei footprint | 35 countries |
| US/State Dept sanctioned firms | Positive Technologies, Citadel |
| Interception mandate | SORM, compulsory since 1995 |
| Primary customer | FSB (direct, warrantless access) |

### The SORM Backbone

Russia's surveillance industry is built around **SORM** (Sistema Operativno-Rozysknykh Meropriyatiy - "System for Operative Investigative Activities"), the legal and technical framework that forces every telecom operator and ISP to install FSB-controlled interception equipment at their own expense. SORM-1 covers phone calls, SORM-2 internet traffic, and SORM-3 long-term storage and deep packet inspection. The FSB accesses the data directly from a remote terminal - no warrant is shown to the operator. A cottage industry of vendors builds and exports the boxes, and since 2022 they have leaned hard into "friendly" markets in Latin America, Africa, and Central Asia to route around sanctions.

## SORM Vendors & Exporters

### Protei (NTC Protei)
`sorm` `dpi` `lawful-intercept` `exporter`

- **Location:** St. Petersburg, Russia
- **Founded:** 1997
- **Product:** SORM interception, deep packet inspection, lawful-intercept and telecom monitoring systems; 150+ engineers.
- **Notable:** Recorded Future documented Protei exports to ~35 countries including Mexico, Cuba, Colombia, Italy, and the UAE - a primary channel for spreading Russian interception architecture abroad.

### Citadel (with MFI Soft)
`sorm` `sanctioned` `fsb`

- **Location:** Moscow, Russia
- **Owner:** Anton Cherepennikov (oligarch tied to Putin-linked circles)
- **Product:** Consortium consolidating most of Russia's SORM manufacturers, including SORM-maker **MFI Soft**; reportedly controls the majority of the domestic interception-equipment market.
- **Notable:** Sanctioned by the U.S. Department of State in 2023 over ties to the FSB and the reach of its interception monopoly.

### Norsi-Trans
`sorm` `interception` `storage`

- **Location:** Moscow, Russia
- **Founded:** 1996
- **Product:** SORM interception and data-retention systems (the "Yakhont" line) for telecom operators.
- **Notable:** One of the eight SORM exporters flagged by Recorded Future as marketing at trade expos across Africa, Latin America, and the Middle East.

### Positive Technologies
`offensive` `sanctioned` `fsb-gru`

- **Location:** Moscow, Russia
- **Product:** Vulnerability research, exploit development, and network security tooling.
- **Notable:** Sanctioned by the U.S. Treasury in **April 2021** for providing tools to the FSB and using its security conferences as FSB/GRU recruiting events. The company said sanctions had little effect on its business.

### NTC Vulkan (NPO Vulkan)
`cyber-weapons` `mod` `sandworm`

- **Location:** Moscow, Russia
- **Product:** Contract engineering for Russian military and intelligence cyber programs.
- **Notable:** The **Vulkan Files** leak (March 2023) exposed contracts to build offensive tooling (Scan-V, Amezit, Crystal-2V) for the Russian MoD and units linked to Sandworm - blueprints for disinformation, traffic manipulation, and attacks on critical infrastructure.
