---
icon: atom
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Projects

### Online Quantitative Mass Spectrometry

Operando mass spectrometry can be used to continuously monitor and quantify the volatile products produced by a chemical or electrochemical reaction making it both a powerful diagnostic and scientific tool. **QU**antitative **A**naly**S**is of vol**A**tiles via **R**eal-time **M**ass **S**pectrometry **(QUASAR-MS),** is an open-source, sensitive, repeatable, and low-cost online mass spectrometry system where both the instrument's software and hardware can be reconfigured to an experiment's specific needs. We strongly believe that an open source community can lower the entry and cost barriers to using _operando_ quantitative gas analysis systems while extending the technique to a wide range of industrial-grade electrolytes to help bridge the all too common valley-of-death in energy research.

<div align="left"><figure><img src=".gitbook/assets/Asset 38@300x.png" alt="" width="188"><figcaption></figcaption></figure></div>

<figure><img src=".gitbook/assets/Asset 32@300x.png" alt=""><figcaption><p>System diagram of <strong>QUASAR's</strong> open source quantitative mass spectrometry system.</p></figcaption></figure>

**QUASAR's** hardware is designed to be easily maintain-able by researchers with parts being selected for both their availability and replaceability without the need for precise alignment. The system is designed to be resistant to industrial-grade electrolytes such as potassium hydroxide and sulfuric acid at high concentrations (>5M), though reconfiguration of specific parts may be required depending on the user's choice of electrolyte. The documentation on this website contains a (1) theory of operation, (2) a list of parts and assembly instructions, (3) calibration procedures and data, (4) required software, and (5) tips and tricks to modify the system to your experimental needs. We also maintain an updated list of experiments that have used the platform or variants of the platform as a starting point for your own work.

#### Applications of QUASAR

Below are example experiments that have been performed with Quadrupole and its adaptations.

* Quantification of the efficiency of hydrogen production from both alkaline-water electrolysis (AWE) and chemical-based reactors; measurement of Faraday and Energy Efficiency (kWh/kg) under quasi-industrial conditions (30wt% KOH @ 25°C).
* Measurement of gas crossover and efficiency loss mechanisms in water electrolysis including comparative studies on membrane, separator, and seperator-less technologies.
* High-througput screening of parameters for pulsed electrolysis with applications in water-splitting, direct waste water to hydrogen production, CO2 reduction, and critical minerals recovery.
* Characterization of aqueous metal-air batteries (AMABs) with gas-diffusion cathodes.

### Electrochemical Test Cells

The design of electrochemical test cells has significant effects on the quality of experimental data; a well-documented starting cell can significantly reduce debugging time especially in the early stages of research. In addition to this, the translatability of electrochemical cells between different _operando_ and _in-situ_ characterization methods is non-trivial and often requires significant engineering effort or additional characterization to be able to replicate conditions across multiple techniques.&#x20;

On this website, we provide documentation for two key types of test cells. The first type, are standard H-Cells that are designed to couple directly with **QUASAR** while simultaneously being compatible with optical characterization equipment such as high-speed cameras, Raman Spectrometers, and IR Spectrometers. The second type are half-cells that similarly couple with **QUASAR** but are designed for _operando_ XAS characterization at the beamline, _operando_ Second Harmonic Generation (SHG) spectroscopy, or similar advanced probing techniques. All cells are designed for compatibility with industrial-grade electrolytes (30wt% KOH @ 25°C), include the option to add a reference electrode, and can be operated both as flow-cells or stand-alone.&#x20;

In addition to cell design, manufacturing, and assembly instructions, we've included detailed characterization data for each of these cells. This data includes CV and EIS curves, polarization curves, faraday efficiency measurements, overpotential plots, efficiency curves, ex-situ XPS data, _operando_ XAS data, mass spectrometer pressures and flow rates from **QUASAR**, and preparation and experimental procedures.

{% columns %}
{% column %}
<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

### Resources

Additional resources are provided on this website for characterization techniques including _operando_ Mass Spectrometry, ex-situ X-Ray Photoelectron Spectroscopy (XPS) and Grazing-Incidence X-Ray Diffraction (GI-XRD), _operando_ X-Ray Absorption Spectroscopy (XAS), Electrochemical Impedance Spectroscopy (EIS), and other references we've found useful in our work. Please visit the resources page and email us at [hardware@mit.edu](mailto:hardware@mit.edu) with suggested additions.

### Contributor & Educational Projects

Documentation of additional hardware projects by EHB contributors and our research collaborators including Raman-compatible electrochemical cells, SHG spectrometers, and more are contained within the contributor projects subsection of this documentation set. There is additionally a section specifically for educational projects and kits designed to bring energy science into the classroom.

Please cite these projects using the specific instructions and DOIs contained on their subpages. We'd like to thank all our contributors and collaborators for making energy science and education more accessible.&#x20;
