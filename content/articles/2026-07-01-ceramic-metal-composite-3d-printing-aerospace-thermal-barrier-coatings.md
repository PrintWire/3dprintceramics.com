---
title: "Ceramic Metal Composite 3D Printing for Aerospace Thermal Barrier Coatings and Multi-Material Structures"
date: 2026-07-01T06:06:21-06:00
draft: false
description: "An overview of ceramic-metal 3D printing routes relevant to aerospace thermal barrier coatings, environmental barrier coatings on ceramic matrix composites, and ultra-high temperature ceramics."
keywords: ["ceramic metal composite 3D printing aerospace thermal barrier coatings", "functionally graded materials additive manufacturing", "ceramic matrix composite metal substrate bonding"]
---

# Ceramic Metal Composite 3D Printing for Aerospace Thermal Barrier Coatings and Multi-Material Structures

Ceramic metal composite 3D printing for aerospace thermal barrier coatings is a demanding corner of additive manufacturing. Unlike single-material parts, ceramic-metal structures have to reconcile very different thermal and mechanical properties across a bond interface that is heated and cooled again and again in service. This article covers how conventional coating systems handle that interface, which additive routes have been reported for combining ceramics and metals, and where ceramic composites are already used in engines.

---

## Why the Ceramic-Metal Interface is the Critical Variable

Ceramics and metals expand by different amounts when heated. Near room temperature, nickel expands at about 13 parts per million per kelvin, while silicon carbide expands at about 2.77. Ceramics often have to be joined to, or work alongside, other materials, so their expansion has to be matched to the application; uneven expansion in a brittle material causes thermal stress that can lead to fracture.

A conventional thermal barrier coating manages this with a layered system. A metallic bond coat, typically a NiCrAlY or NiCoCrAlY alloy (nickel and platinum aluminide bond coats also exist), sits between the metal substrate and a ceramic topcoat that is typically yttria-stabilized zirconia (YSZ). The thermal expansion coefficients of the layers should match well. In service, a thermally grown oxide (TGO) layer forms, and its growth is the most important cause of spallation failure: with a thick enough TGO, the coating can spall. YSZ also has a temperature ceiling, since above 1200 °C it suffers unfavorable phase transformations. Topcoats are applied by air plasma spray or electron beam physical vapor deposition.

A functionally graded material takes a different approach: composition and structure vary gradually through the volume, normally by connecting a ceramic layer to a metallic layer, so that the transition from metal to ceramic is spread out instead of sharp.

---

## Additive Approaches to Ceramic-Metal Integration

### Directed Energy Deposition with Compositional Grading

Directed energy deposition (DED) uses a focused energy source (usually a laser, electron beam or electric arc) to melt and deposit powder or wire feedstock. It is a separate process family from powder bed fusion, and it has mainly been used for metallic parts. Composition can be adjusted during the build by feeding powders from multiple coaxial feeders with independently controllable feed rates, and a review of multi-material additive manufacturing describes this arrangement as suitable for producing functionally graded composites.

### Binder Jetting and Infiltration for Net-Shape Ceramic Bodies

Binder jetting bonds powder with a liquid binder, and the loose powder supports overhanging features during the build. Binder-jetted parts are inherently porous, so they are usually sintered and can be infiltrated with a second material. Ceramic-metal composites can be made this way: a ceramic body is printed, cured and sintered, then immersed in molten metal to fill the porosity.

Silicon carbide is a well-documented example. Researchers at Oak Ridge National Laboratory printed SiC powder by binder jetting, added carbon through phenolic resin infiltration and pyrolysis, and finished with reactive silicon melt infiltration. After two infiltration and pyrolysis cycles, porosity was below 2%, Young's modulus was close to 300 GPa, and flexural strength was 517.6 ± 24.8 MPa. The authors report that this is below values reported for hot-pressed SiC (about 650 MPa) but above those reported for siliconized silicon carbide (about 385 MPa), and they describe the material as dense, gas impermeable and comparable to conventionally processed siliconized SiC. They point to heat exchangers as a target application.

### Vat Photopolymerization for Complex Oxide Ceramics

In lithography-based ceramic manufacturing, a UV-curable resin or slurry containing ceramic particles is polymerized layer by layer, and the printed part is then debinded and sintered to obtain a dense ceramic. One research facility running a Lithoz CeraFab S25 lists a printing resolution of 25 µm in the x/y plane and 10 to 100 µm in z.

---

## Environmental Barrier Coatings in CMC Systems

Silicon carbide fiber-reinforced SiC matrix composites (SiC/SiC CMCs) are already in service in turbine hot sections. The CFM LEAP engine, made by CFM International (a 50/50 joint venture of Safran and GE), has one CMC component, a high-pressure turbine shroud, which lets that zone operate at up to 2400 °F. The GE9X has five CMC parts in the hot section: inner and outer combustor liners, Stage 1 high-pressure turbine shrouds and nozzles, and Stage 2 high-pressure turbine nozzles. The fan blades of these engines are not among the CMC parts. SiC/SiC has roughly one-third the density of nickel-based superalloys.

SiC-based materials are vulnerable to water vapor, which is a by-product of combustion. SiC forms a silica scale at high temperature, and that scale reacts with water vapor to form gaseous Si(OH)₄. The resulting material loss is called recession. Environmental barrier coatings (EBCs) were developed to prevent it. Current EBCs use a silicon bond coat between the CMC substrate and a topcoat of rare-earth silicate, such as ytterbium disilicate (Yb₂Si₂O₇).

The failure mechanism resembles that of thermal barrier coatings. Water vapor and oxygen still permeate the EBC topcoat and oxidize the silicon bond coat, forming a thermally grown oxide of SiO₂. Once that scale reaches a critical thickness, the topcoat delaminates and spalls.

---

## Applications: Aerospace and Nuclear Energy

**Re-entry thermal protection systems.** Ultra-high temperature ceramics (UHTCs) based on hafnium diboride (HfB₂, melting point 3,380 °C) and zirconium diboride (ZrB₂, 3,245 °C) are being developed for the leading edges of vehicles in atmospheric re-entry, where sharp edges reduce drag but challenge current thermal protection materials. A set of hafnium diboride fins has been produced by robocasting, an extrusion-based 3D printing technique.

**Nuclear applications.** SiC fiber-reinforced SiC matrix composites are considered a primary candidate for accident tolerant fuel cladding in light water reactors. Joining the cladding to its end plug is recognized as one of the technological hurdles, because the joint must be gas-tight and is exposed to hot water and neutron irradiation in normal operation.

---

Ceramic-metal structures succeed or fail at the interface. Conventional coating systems manage it with bond coats and accept that a thermally grown oxide will eventually limit life. Additive routes offer other options, including graded compositions by directed energy deposition and infiltrated ceramic bodies by binder jetting, and published results for binder-jetted, silicon-infiltrated SiC show properties comparable to conventionally processed material.

## Sources

- [Wikipedia: Thermal barrier coating](https://en.wikipedia.org/wiki/Thermal_barrier_coating)
- [Wikipedia: Thermal expansion](https://en.wikipedia.org/wiki/Thermal_expansion)
- [Wikipedia: Functionally graded material](https://en.wikipedia.org/wiki/Functionally_graded_material)
- [Toursangsaraki, A Review of Multi-material and Composite Parts Production by Modified Additive Manufacturing Methods (arXiv preprint)](https://arxiv.org/pdf/1808.01861)
- [Wikipedia: Powder bed and inkjet head 3D printing (binder jetting)](https://en.wikipedia.org/wiki/Powder_bed_and_inkjet_head_3D_printing)
- [Cramer et al., Properties of SiC-Si made via binder jet 3D printing of SiC powder, carbon addition, and silicon melt infiltration (ORNL, via OSTI)](https://www.osti.gov/servlets/purl/1813244)
- [Karlsruhe Institute of Technology KNMF: Lithography-based Ceramic Manufacturing](https://www.knmf.kit.edu/LCM.php)
- [American Ceramic Society Bulletin: Ceramic matrix composites taking flight at GE Aviation](https://bulletin.ceramics.org/article/ceramic-matrix-composites-taking-flight-at-ge-aviation/)
- [Oak Ridge National Laboratory: Ceramic matrix composites take flight in LEAP jet engine](https://www.ornl.gov/news/ceramic-matrix-composites-take-flight-leap-jet-engine)
- [NASA Glenn, GT2025-152711: Oxidation of an environmental barrier coated ceramic matrix composite in a combustion environment](https://ntrs.nasa.gov/api/citations/20250002624/downloads/GT2025-152711-Final.pdf)
- [Wikipedia: Ultra-high temperature ceramic](https://en.wikipedia.org/wiki/Ultra-high_temperature_ceramic)
- [Katoh et al., ORNL/TM-2016/274: Report on viability of hydrothermal corrosion resistant SiC/SiC joint development](https://info.ornl.gov/sites/publications/files/Pub68199.pdf)

Fact-checked 2026-11-21
