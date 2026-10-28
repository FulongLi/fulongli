# Hi, I'm Fulong 👋

📍 **Cardiff, UK** | ⚡ **Power Electronics** | 🎓 **Ph.D.** | 🤖 **AI-assisted Design** | 🚀 **Founder @ AIPE Labs**

![Power Electronics](https://img.shields.io/badge/Power_Electronics-FF6F00?style=flat-square&logoColor=white)
![Converter Design](https://img.shields.io/badge/Converter_Design-E65100?style=flat-square&logoColor=white)
![Magnetics](https://img.shields.io/badge/Magnetics-4A148C?style=flat-square&logoColor=white)
![MATLAB/Simulink](https://img.shields.io/badge/MATLAB%2FSimulink-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![PLECS](https://img.shields.io/badge/PLECS-00796B?style=flat-square&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-8B0000?style=flat-square&logoColor=white)

> Energy helps humanity enter a Type I civilisation.

## Spirit Connect

```mermaid
---
config:
  look: classic
  flowchart:
    minNodeWidth: 0
---
flowchart LR
    FANTASY(("Fantasy"))
    SC(("Spirit Connect"))
    AIPE(("AIPE Labs"))
    ACADEMY(("Academy"))

    FANTASY --- SC
    SC --- AIPE
    SC --- ACADEMY

    linkStyle 0,1,2 stroke:#2EBCFE,stroke-width:2px;

    classDef brand fill:#2EBCFE,stroke:#2EBCFE,stroke-width:2px,color:#ffffff;
    classDef lab fill:#2EBCFE,stroke:#2EBCFE,stroke-width:2px,color:#ffffff;
    classDef story fill:#1C7198,stroke:#1C7198,stroke-width:2px,color:#ffffff;
    classDef academy fill:#2EBCFE,stroke:#2EBCFE,stroke-width:2px,color:#ffffff;

    class SC brand;
    class AIPE lab;
    class FANTASY story;
    class ACADEMY academy;
```

* 🌐 **[Spirit Connect](https://spiritconnect.co.uk/)** - Main brand and landing page for my connected research, design, and creative work
  * 🧠 **[AIPE Labs](https://aipel.co.uk/)** - AI-assisted power electronics, power devices, design tools, and engineering agents
  * ✍️ **[Fantasy](https://fulongli.github.io/Spirit-Connect-Fantasy/)** - Fiction, worldbuilding, and long-form creative projects
  * 🎓 **[Academy](https://github.com/FulongLi/AIPE-Academy)** - Open, AI-guided power engineering learning resources

## AIPE Ecosystem — AI for Power Engineering

**AIPE** is the engineering ecosystem I am building to connect power-electronics data, analytical models, simulation, design automation, research, and education. The current focus is a shared **Engineering State** and executable, evidence-linked workflows: specialist tools exchange explicit inputs, assumptions, results, and provenance through a coordinated design process.

**Start here:** [AIPE Labs](https://aipel.co.uk/) · [Capability index](https://github.com/FulongLi/AIPE-Registry/blob/main/generated/aipe.md) · [Engineering workflows](https://github.com/FulongLi/AIPE-Workflows) · [Browse AIPE repositories](https://github.com/FulongLi?tab=repositories&q=AIPE)

### Current Milestone: 10 kW DAB Engineering Workflow

The [10 kW dual-active-bridge benchmark](https://github.com/FulongLi/AIPE-Workflows/blob/main/examples/dab-10kw/README.md) connects **800 V → 400 V at 100 kHz** across analytical sizing, ngspice switching simulation and control analysis, device screening, waveform-informed magnetics, cooling design, Gmsh/Elmer field simulation, and FreeCAD geometry. Checkpointed task graphs retain hashed artifacts and engineering evidence; feedback runs feed magnetics and FEM parameters back into the circuit model.

The recorded run has executed software, analytical, circuit-simulation, and field-simulation checks. KiCad checks also run, with DAB board routing still in progress; the benchmark remains a prototype without measurement or hardware qualification. [Review package and verification record](https://github.com/FulongLi/AIPE-Workflows/tree/main/examples/dab-10kw/results).

### Shared Infrastructure

- **[AIPE-Core](https://github.com/FulongLi/AIPE-Core)** — Engineering State schemas, SI-unit and evidence conventions, and interoperability contracts.
- **[AIPE-Registry](https://github.com/FulongLi/AIPE-Registry)** — Validates repository capability manifests and generates a discoverable index of tools, dependencies, and integration maturity.
- **[AIPE-Workflows](https://github.com/FulongLi/AIPE-Workflows)** — Coordinates specialist tools through reproducible task graphs, checkpoints, verification gates, feedback iterations, and review packages.
- **[AIPE-Doc](https://github.com/FulongLi/AIPE-Doc)** — English and Chinese HTML document and slide templates, browser PDF export, and the presentation layer for engineering review reports.

### Engineering Data, Models & Design

- **[AIPE-Semiconductor-Database](https://github.com/FulongLi/AIPE-Semiconductor-Database)** — Versioned device data, manufacturer-model imports, evidence lineage, device screening, loss evaluation, and measurement-request interfaces.
- **[AIPE-Magnetics-Database](https://github.com/FulongLi/AIPE-Magnetics-Database)** — Magnetic data and loss models, waveform-informed inductor and transformer design, and verification evidence.
- **[AIPE-Electrical-Design](https://github.com/FulongLi/AIPE-Electrical-Design)** — Analytical converter models, single-phase-shift DAB analysis, and DC–DC sizing; successor to the former Design Agent's electrical calculations.
- **[AIPE-Thermal-Design](https://github.com/FulongLi/AIPE-Thermal-Design)** — Heat-sink models, thermal networks, electrothermal iteration, cooling-concept comparison, and Pareto screening.
- **[AIPE-Converter-Optimisation-Agent](https://github.com/FulongLi/AIPE-Converter-Optimisation-Agent)** — Multi-objective loss/volume optimisation and neural-network surrogate modelling for a buck-type inverter.
- **[AIPE-MOSFET-ANN-Modelling](https://github.com/FulongLi/AIPE-MOSFET-ANN-Modelling)** — Neural-network models for MOSFET conduction, switching losses, and thermal impedance.

### Simulation, Schematics, CAD & PCB

- **[AIPE-Simulation-Skills](https://github.com/FulongLi/AIPE-Simulation-Skills)** — Agent workflows plus executable ngspice DAB simulations, waveform analysis, and a host-side control baseline; open-source tools are the default path.
- **[AIPE-Field-Simulation](https://github.com/FulongLi/AIPE-Field-Simulation)** — Gmsh/Elmer finite-element workflows for thermal and electromagnetic analysis, with analytical benchmarks and mesh-convergence records.
- **[AIPE-Sketcher](https://github.com/FulongLi/AIPE-Sketcher)** — Circuit descriptions and Engineering State inputs to SVG schematics, with connectivity validation and provenance.
- **[AIPE-CAD-Agent](https://github.com/FulongLi/AIPE-CAD-Agent)** — Parametric FreeCAD geometry for transformers, cooling, and converter assemblies, with STEP export and interference/clearance review.
- **[AIPE-PCB-Agent](https://github.com/FulongLi/AIPE-PCB-Agent)** — Requirements to KiCad schematics, board placement/routing, native ERC/DRC checks, and exports; SiC buck and three-board DAB examples.

### Research, Learning & References

- **[AIPE-IEEE-Paper-Agent](https://github.com/FulongLi/AIPE-IEEE-Paper-Agent)** — Evidence-linked paper planning, IEEE venue-specific LaTeX workspaces, and citation/manuscript audits.
- **[AIPE-Academy](https://github.com/FulongLi/AIPE-Academy)** — AI-guided learning across foundations, power electronics, power systems, and renewable energy, with reproducible Python labs and agent interfaces.
- **[AIPE-Solid-State-Transformer](https://github.com/FulongLi/AIPE-Solid-State-Transformer)** — Solid-state transformer design and simulation references.
- **[Inductor Design Examples](https://github.com/FulongLi/AIPE-Magnetics-Agnet-Inductor-Design-Example)** — Magnetic-component drawings and reference examples.

*AIPE project snapshot: 28 October 2026. Individual repositories document their current maturity, validation evidence, and licences.*

## Other Projects

### Sites & Platforms

- **[Spirit Connect](https://spiritconnect.co.uk/)** — Main brand and project website.
- **[Personal Website](https://fulongli.github.io/)** — Academic and professional profile.
- **[spiritconnect.github.io](https://github.com/FulongLi/spiritconnect.github.io)** — Spirit Connect website source.
- **[Spirit-Connect-Technology](https://github.com/FulongLi/Spirit-Connect-Technology)** — Technology projects and prototypes.

### Aion & Intelligent Presence

- **[Aion-Presence-Plugin](https://github.com/FulongLi/Aion-Presence-Plugin)** — Visual presence and interactive presentation layer for Codex.
- **[SCF-Presence-Realtime](https://github.com/FulongLi/SCF-Presence-Realtime)** — Realtime voice-driven AI presence with visual expression.

### Power Electronics & Energy Systems

- **[AIPS-Microgrid-EMS-Agent](https://github.com/FulongLi/AIPS-Microgrid-EMS-Agent)** — Agent-oriented microgrid energy management.
- **[AIPS-EV-Charging-Planning](https://github.com/FulongLi/AIPS-EV-Charging-Planning)** — Grid-aware EV charging planning.
- **[DC-community](https://github.com/FulongLi/DC-community)** — Residential DC community research.
- **[BuckConverterOptimisation](https://github.com/FulongLi/BuckConverterOptimisation)** — Multi-objective buck converter optimisation.
- **[IsolatedCoverters](https://github.com/FulongLi/IsolatedCoverters)** / **[NonisolatedCoverters](https://github.com/FulongLi/NonisolatedCoverters)** — Converter topology references.
- **[DCMicrogridTestBench](https://github.com/FulongLi/DCMicrogridTestBench)** / **[WirelessPowerTransferTestBench](https://github.com/FulongLi/WirelessPowerTransferTestBench)** — Hardware test benches.
- **[PCB-Rogowski-Coil](https://github.com/FulongLi/PCB-Rogowski-Coil)** / **[Magnetics-PCBCurrentTransformerTransducer](https://github.com/FulongLi/Magnetics-PCBCurrentTransformerTransducer)** — Current-sensing hardware.
- **[HeatSinkOptimisation](https://github.com/FulongLi/HeatSinkOptimisation)** — Heat-sink thermal optimisation.
- **[PowerElectronicsDeviceLibrary](https://github.com/FulongLi/PowerElectronicsDeviceLibrary)** — Power semiconductor reference library.

### Creative Projects & Experiments

- **[Spirit-Connect-Fantasy](https://github.com/FulongLi/Spirit-Connect-Fantasy)** — Interactive fiction and worldbuilding website.
- **[SCF-Ancient-Civilisations](https://github.com/FulongLi/SCF-Ancient-Civilisations)** / **[SCF-Another-World](https://github.com/FulongLi/SCF-Another-World)** / **[SCF-Another-World-Art](https://github.com/FulongLi/SCF-Another-World-Art)** — Fiction, worldbuilding, and concept art.
- **[Temporal-Slices](https://github.com/FulongLi/Temporal-Slices)** — Experimental time-slice visualisation.
- **[Earthquake-Predictions](https://github.com/FulongLi/Earthquake-Predictions)** — Earthquake prediction experiments.

### Community Resources & Forks

- **[awesome-open-source-power-electronics](https://github.com/FulongLi/awesome-open-source-power-electronics)** — Curated open-source power electronics resources.
- **[PowerVision](https://github.com/FulongLi/PowerVision)** / **[transistordatabase](https://github.com/FulongLi/transistordatabase)** / **[magnetchallenge](https://github.com/FulongLi/magnetchallenge)** — Forked research and tooling resources.

## Useful Tools for PE Engineers

A curated collection of open-source tools for power electronics research and design.

<details>
<summary>View engineering tools and references</summary>

### Power Electronics

* 🖊️ **[Inkscape Electric Symbols](https://github.com/upb-lea/Inkscape_electric_Symbols)** - Electrical drawing symbols for Inkscape
* 📋 **[awesome-open-source-power-electronics](https://github.com/upb-lea/awesome-open-source-power-electronics)** - Curated list of open-source PE tools
* 🧲 **[FEM Magnetics Toolbox (FEMMT)](https://github.com/upb-lea/FEM_Magnetics_Toolbox)** - FEM simulation for magnetic components
* 🗄️ **[Material Database](https://github.com/upb-lea/materialdatabase)** - Ferrite core material datasheets and measurements
* 🔌 **[PE Capacitor Selection Toolbox](https://github.com/upb-lea/capacitor_selection_toolbox)** - Foil capacitor selection and comparison
* 🌡️ **[Heat Sink Computation Toolbox](https://github.com/upb-lea/HCT_heat_sink_computation_toolbox)** - Fan-cooled heat-sink sizing and optimisation
* 🧪 **[MagNet Hub](https://github.com/upb-lea/mag-net-hub)** - Certified models from the MagNet Challenge

### CAD, Simulation & Plotting

* 🐍 **[pyGeckoCircuits2](https://github.com/upb-lea/pygeckocircuits2)** - Python wrapper for GeckoCIRCUITS
* 📐 **[KiClearance](https://github.com/upb-lea/KiClearance)** - KiCad clearance rules generator
* 🗂️ **[LEA KiCad Library](https://github.com/upb-lea/LEA_KiCad_Library)** - Reviewed symbols and footprints with Mouser part numbers
* 📊 **[pySignalScope](https://github.com/upb-lea/pySignalScope)** - Simulation and measurement plotting

### Reinforcement Learning, Motor & Grid

* 🎓 **[RL Course Materials](https://github.com/upb-lea/reinforcement_learning_course_materials)** - Lectures, tutorials and solutions for RL
* 🏎️ **[Gym Electric Motor (GEM)](https://github.com/upb-lea/gym-electric-motor)** - OpenAI Gym environment for electric motors
* ⚙️ **[OpenModelica Microgrid Gym](https://github.com/upb-lea/openmodelica-microgrid-gym)** - Microgrid Gym environment
* 🔌 **[ElectricGrid.jl](https://github.com/upb-lea/ElectricGrid.jl)** - Time-domain grid modeling with converter control
* 🎛️ **[gem-control](https://github.com/upb-lea/gem-control)** - Linear / field-oriented controllers for GEM
* 🤖 **[meta_RL_PMSM](https://github.com/upb-lea/meta_RL_PMSM)** - Meta RL for PMSM current control across power classes

</details>

## Connect

[GitHub](https://github.com/FulongLi) · [Personal Site](https://fulongli.github.io/) · [Spirit Connect](https://spiritconnect.co.uk/) · [AIPE Labs](https://aipel.co.uk/) · [Aion Presence](https://github.com/FulongLi/Aion-Presence-Plugin) · [Fantasy](https://fulongli.github.io/Spirit-Connect-Fantasy/) · [Academy](https://github.com/FulongLi/AIPE-Academy)
