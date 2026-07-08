---
title: "Link-to-System LEO"
excerpt: "Simulation of network connections between LEO satellites and terrestrial UE."
collection: projects
order: 4
---

This project focused on the design of a system-level simulation framework for evaluating link performance in LEO satellite networks, developed in the MATLAB 5G Toolbox™ environment and compliant with 3GPP technical specifications (TR 38.821 and TR 36.763).

The work was structured across multiple layers:

- **Geometric and channel modeling**: implementation of orbital dynamics (slant range, angular velocity) and propagation modeling (Free Space Path Loss, atmospheric loss, ionospheric scintillation, polarization loss) for four operational scenarios, differentiated by satellite antenna aperture and terminal class (eMBB and mMTC IoT).
- **Link-to-System (L2S) abstraction**: development of a link adaptation algorithm for the dynamic selection of the modulation and coding scheme (MCS) based on instantaneous SINR, in accordance with 3GPP TS 38.214 tables.
- **Physical-layer emulation of the 5G NR chain**: slot-by-slot simulation of PUSCH/PDSCH, TDL-D channel modeling, LDPC decoding, and HARQ management for realistic uplink/downlink throughput estimation.
- **Results analysis**: characterization of average throughput as a function of elevation angle and transit time, along with statistical analysis via cumulative distribution functions (CDFs), comparing the four radio scenarios.

For further information or access to the documentation, please contact me via [email](mailto:davideverditto).