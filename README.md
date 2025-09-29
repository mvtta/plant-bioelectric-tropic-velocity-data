<h2 align="center">
Collecting Velocities of Bio-Chemical Gradients in Plant Tropism Systems

</h2>
<h6 align="center">
Plant bioelectric wave velocities and tropism-specific data compilation
</h6>

*Author: Valdetaro, M.*

The goal of this project was to compile biochemical gradient and wave velocities in plant developmental biology contexts, with particular focus on tropism-related signaling phenomena. It contains four complementary datasets designed for distinct research applications. For **tropism-specific responses** (26 measurements) with statistical validation including standard deviations and sample sizes. For **comprehensive signal modality coverage** (37 measurements) systematically categorizing bioelectric, calcium, auxin, hormonal, mechanical/acoustic, and morphogenetic processes.  If focussing on **classical plant signaling phenomena** (24 measurements) with citations primary and supporting for a quick-entry point suitable for literature analysis, and for **cutting-edge specialized research** (15 measurements) documenting some recent models / findings which include acoustic enhancement of auxin transport and spiromonostichy mathematical (dual-field) modeling. An annex is found after the data and collection information, and csv's outline. In the annex tehre are some aditional findings for future investigation on the relationships between chemical gradient composition, tissue type, and resulting wave velocities in plant bioelectric developmental processes. There is explicit interest in intrinsic tropisms and velocities, mechanosensitive gating mechanisms, bioelectric pattern modulation, auxin transport regulation, and calcium-hydraulic feedback systems. Last but not least, a refinenement on the processes which are governed by active nematic order and energy landscape navigation ranging multiple timescales for plant growth and development for a future comparisson with a previous preliminary collection of data specific to biolectric related.

###### Cover image for project: from external web link

Image source: Noise and Robustness in Phyllotaxis - Vincent MirabetFabrice BesnardTeva VernouxArezki Boudaoud February 16, 2012

![IMG_COVER](https://journals.plos.org/ploscompbiol/article/figure/image?size=large&id=10.1371/journal.pcbi.1002389.g001)

#### Scope

The data is preliminary in terms extraction from sources, focussed on plant signal transduction networks, and the coordinated development, environmental responses, and physiological processes through diverse wave propagation mechanisms. In total there are 102 unique measurements, some are repeating, from 80+ peer-reviewed sources, and temporal window 1970-2025. There are **seven orders of magnitude**  from rapid action potentials approaching **105 m/s** (comparable to animal nerve conduction) to slow morphogenetic processes at  **0.01 μm/min.** Notable mentions include calcium wave propagation at **150-400 μm/s** with temporal precision (**18.3±0.6 seconds** gravitropic latency), acoustic enhancement producing **3-fold upregulation** of PIN auxin transport genes, hydraulic pressure waves reaching  **100 m/s** , and **Costus** spiromonostichy exhibiting systematic **130°→60°→55°** divergence angle transitions that violate traditional phyllotaxis rules.

**Total Coverage**

- Seven orders of magnitude
- 102 collected measurements
- Citations from 1952-2025

##### Files

###### data/plant_tropism_wave_database.csv

| Value | Unit  | Chemical_Gradient | Parameter_Type     | Std_Dev | N | Intra | Inter | Organism             | Tissue_Type           | Tropism_Type  | Context                    | Physics_Basis                           | Injured | Healthy | Signaling_Type      | Citation                   |
| ----- | ----- | ----------------- | ------------------ | ------- | - | ----- | ----- | -------------------- | --------------------- | ------------- | -------------------------- | --------------------------------------- | ------- | ------- | ------------------- | -------------------------- |
| 1.0   | μm/h | Auxin             | Wave velocity peak |         |   | No    | Yes   | Arabidopsis thaliana | Shoot apical meristem | Organogenesis | Rhythmic centrifugal waves | Active transport, polar auxin transport | No      | Yes     | Auxin gradient wave | Galvan-Ampudia et al. 2020 |

###### data/plant_wave_database.csv

| Value | Unit      | Chemical_Gradient | Parameter_Type    | Std_Dev | N | Intra | Inter | Organism             | Tissue_Type   | Tropism_Type      | Context                   | Physics_Basis                                   | Injured | Healthy | Signaling_Type             | Citation        | Key_Finding                                   |
| ----- | --------- | ----------------- | ----------------- | ------- | - | ----- | ----- | -------------------- | ------------- | ----------------- | ------------------------- | ----------------------------------------------- | ------- | ------- | -------------------------- | --------------- | --------------------------------------------- |
| 15.0  | hours/day | Sound/acoustic    | Exposure duration |         |   | Yes   | Yes   | Arabidopsis thaliana | Root meristem | Acoustic response | 100 Hz + 9kHz sound waves | Sound wave-induced auxin transport upregulation | No      | Yes     | Acoustic-hormonal coupling | Kim et al. 2021 | PIN1,3,4,7 upregulated 3-fold, PIN2 unchanged |

###### data/plant_signal_velocities.csv

| Signal Type              | Velocity/Rate | System/Tissue     | Measurement Method       | Primary Citation | Biological Function   |
| ------------------------ | ------------- | ----------------- | ------------------------ | ---------------- | --------------------- |
| Action Potentials (Fast) | 2-105 m/s     | Leaf/stem tissues | Microelectrode recording | Volkov, 2019     | Rapid stress response |

###### data/plant_wave_mix_velocities.csv

| Wave Type                   | Velocity (Range) | Plant System         | Measurement Method      | Primary Citation    | Supporting Citations                 |
| --------------------------- | ---------------- | -------------------- | ----------------------- | ------------------- | ------------------------------------ |
| Calcium Waves (Gravitropic) | 150-400 μm/s    | Root columella cells | Confocal Ca²⁺ imaging | Toyota et al., 2013 | Shih et al., 2015; Band et al., 2012 |

###### data/spiromonostichy_methodology_with_citations.csv

| Category        | Method                       | Computed Parameters                                       | Typical Outputs                                 | Plant Applications                                   | Primary Citation  | Supporting Citations                 |
| --------------- | ---------------------------- | --------------------------------------------------------- | ----------------------------------------------- | ---------------------------------------------------- | ----------------- | ------------------------------------ |
| Wave Kinematics | Fourier-Bessel Decomposition | Bessel function zeros J_m(k_0r), azimuthal mode numbers m | Nodal line positions, parastichy identification | Costus spiromonostichy modeling, parastichy analysis | Guan et al., 2001 | Hotton et al., 2006; Mitchison, 1977 |

## Methodology

Data that encompasses electrophysiological recording (microelectrodes, patch-clamp, multi-electrode arrays), advanced calcium imaging (confocal microscopy, genetically encoded indicators, ratiometric analysis), hormone transport analysis (radiotracer studies, fluorescent biosensors, protein trafficking), acoustic spectroscopy (surface acoustic waves, phonon analysis, resonance profiling), and morphogenetic tracking (time-lapse microscopy, optical flow analysis, atomic force microscopy).

**Primary Databases:**

- PubMed/PMC (primary source for plant physiology)
- Nature Plant Science journals
- Frontiers in Plant Science
- Plant Physiology (Oxford Academic)
- Journal of Experimental Botany
- New Phytologist
- bioRxiv preprint server
- Specialized plant biology journals

### Search Strategy

**Primary Search Terms** (combined with Boolean operators):

- `"auxin wave velocity"` AND (`"tropism"` OR `"plant development"`)
- `"gravitropism"` AND `"calcium wave"` AND `"velocity"` AND `"measurements"`
- `"phototropism"` AND `"PIN transporter"` AND `"auxin transport"`
- `"thigmotropism"` AND `"action potential"` AND `"plant electrical signaling"`
- `"hydraulic signaling"` AND `"plant"` AND `"wave velocity"`
- `"acoustic wave"` AND `"plant tissue"` AND `"wood"` AND `"propagation"`
- `"mechanotransduction"` AND `"plant"` AND `"TMC"` AND `"calcium"`
- `"phyllotaxis"` AND `"auxin gradient"` AND `"spiral"` AND `"velocity"`
- `"plant bioelectricity"` AND `"Vmem"` AND `"membrane potential"`
- `"active nematic"` AND `"plant tissue"` AND `"collective migration"`

### Temporal Coverage

- Classic tropism studies (1952-1990)
- Advanced measurement techniques (1990-2010)
- High-resolution imaging and molecular tools (2010-2025)

## Selection Criteria

### Inclusion Criteria

**Primary Requirements:**

- Studies must provide numerical values with units
- Direct relevance to plant developmental biology and tropisms
- Measurements of propagation velocities, transport rates, or temporal dynamics
- Direct connection to directional growth responses and environmental sensing
- Clear physics-based or mechanistic explanations
- Mathematical models or physics based / nematics related data to plant morphogenesis / phylostaxis

**Secondary Criteria:**

- Preference for studies with error bars, sample sizes, and statistical analysis
- Coverage across plant model organisms
- Inclusion of different plant tissue types and developmental stages
- From molecular (ion channels) to organismal (whole plant) responses
- Studies addressing natural environmental stimuli with physics based knowledge

### Exclusion Criteria

- Purely qualitative descriptions without measurements
- Studies lacking clear experimental protocols
- Plant studies not related to directional growth or environmental sensing or seed / petal placement

## Limitations and Considerations

### Quality Control Measures

Values cross-checked against multiple independent sources where available, and all numerical values verified against original sources (human apologies if mistakes were made).

### Selection Bias Considerations

It is acknowledged that selection bias involved in the collection of the wave velocities presented. The publication bias reflects on the explicit preference for studies with statistically significant findings, english-language publications were preferentially included, open-access papers given this project received no funding.

### Technical Considerations

Please note that measurement precision were not questioned, and that different techniques have varying spatial and temporal resolution. This means that for usage one most consider detection thresholds, the sensitivity limits which may affect reported velocities, compliance with calibration standards, for which not all studies use identical calibration methods, neither were these identified. Additionally, laboratory conditions may influence measured parameters.

## Concluding remarks

This database is a preliminary initiative for the compilation of bioelectric and biochemical wave velocities across developmental contexts. The articles from where the velocities where extracted mention that chemical specificity drives characteristic velocity ranges, and tissue context significantly modulates propagation speeds. Concerning developmental timing affects signaling dynamics, the multi-modal signaling seems to require integrated analytical approaches.

# Clone, fork and contribute to this project

### Clone the repository

```shell
git clone https://github.com/mvtta/bioelectric-wave-velocity-data.git
cd bioelectric-wave-velocity-data
```

### Fork and contribute

1. Fork this repository on GitHub
2. Clone your fork:

```shell
git clone https://github.com/YOUR_USERNAME/bioelectric-wave-velocity-data.git
cd bioelectric-wave-velocity-data
```

3. Create a new branch for your feature:

```shell
git checkout -b feature/your-feature-name
```

4. Make your changes and commit them:

```shell
git add .
git commit -m "Add your meaningful commit message"
```

5. Push to your fork:

```shell
git push origin feature/your-feature-name
```

6. Create a Pull Request on GitHub

### Contribution Guidelines

* Add new wave velocity data with proper citations
* Ensure data follows the existing CSV format
* Update documentation accordingly
* Include statistical data when available
* Please add the citations in the folder references

# Annex: Report and inventory based on a preliminary review of measurement and modeling tools with physics-based approaches for understanding wave velocities and signal propagation in plant systems

## Abstract

Plant systems exhibit rapid bioelectric responses (milliseconds, m/s velocities) and slow morphogenetic processes (hours-days, μm/min rates). This preliminary review  focussed on wave velocities and signal propagation in plant biology, aiming to have a central look-up repository of bioelectric signaling, calcium dynamics, hormone transport, mechanical responses, and morphogenetic processes. This compilation with measured velocities, methodological approaches, and functional significance across diverse plant signal transduction systems is nonetheless minimal and should be considered superficial.

## Introduction

Plant signal transduction involves spatiotemporal coordination mechanisms, diverse physical and chemical processes, with similarities and differences from other kingdoms. For example, just like animals, plants have evolved distributed signaling networks that integrate bioelectric, chemical, and mechanical information to coordinate development, environmental responses, and resource allocation (Baluška & Mancuso, 2009; Gilroy et al., 2014). Novel imaging technologies, as long with bioelectricity have contributed to a broader understanding of shared triats in molecular reporters. Aditionally computational modeling thechniques have helped make visible and quantify these netweoks of signal propagation velocities in plant systems (McKenna et al., 2019; von Wangenheim et al., 2017).

##### Mechanical and Acoustic Signal Propagation

| Signal Type                          | Velocity/Response  | Measurement Method            | Application                              | Citations                   |
| ------------------------------------ | ------------------ | ----------------------------- | ---------------------------------------- | --------------------------- |
| **Mechanosensitive Responses** | 1-100 milliseconds | Patch-clamp electrophysiology | Touch and gravity sensing                | Monshausen & Haswell (2013) |
| **Acoustic Wave Propagation**  | 100-5000 m/s       | Acoustic spectroscopy         | Plant communication and stress signaling | Sueur et al. (2012)         |
| **Phonon Transport**           | 1000-5000 m/s      | Theoretical framework         | Heat and vibrational energy transport    | Kittel (2005)               |

##### Wave Phenomena

| Wave Type              | Velocity/Frequency | Characteristics           | Applications                                  | Citations               |
| ---------------------- | ------------------ | ------------------------- | --------------------------------------------- | ----------------------- |
| Standing Wave Patterns | f = v/2L           | 10-500 Hz frequency range | Potential morphogenetic templates             | Niklas (1992)           |
| Surface Acoustic Waves | 100-1000 m/s       | Controlled manipulation   | Precision agriculture, transpiration control  | Campbell & Jones (2011) |
| Longitudinal W-Waves   | ~1 m/s             | ±33% velocity modulation | Gravitational wave hypothesis (controversial) | Wagner & Wagner (1999)  |

##### Cell Division and Growth Waves

| Process Type           | Velocity Range | Measurement Method    | Biological Function                                     | Citations              |
| ---------------------- | -------------- | --------------------- | ------------------------------------------------------- | ---------------------- |
| Cell Division Waves    | 0.1-1 μm/min  | Time-lapse microscopy | Meristematic zone progression, organ development        | Campilho et al. (2006) |
| Growth Velocity Fields | 0.1-10 μm/min | Optical flow analysis | Tissue expansion patterns, morphogenetic quantification | Pradeep et al. (2022)  |

##### Pattern Formation Dynamics

| Process Type            | Velocity Range  | Status                            | Biological Function                | Citations              |
| ----------------------- | --------------- | --------------------------------- | ---------------------------------- | ---------------------- |
| Morphogenetic Fronts    | 1-100 μm/min   | Mathematical modeling predictions | Developmental boundary progression | Douady & Couder (1996) |
| Pattern Formation Waves | 10-1000 μm/min | Measured in developing meristems  | Phyllotaxis and organ arrangement  | Yonekura et al. (2024) |

##### Physical Transport Processes

| Process Type             | Velocity Range | Measurement Method      | Biological Function            | Citations                    |
| ------------------------ | -------------- | ----------------------- | ------------------------------ | ---------------------------- |
| Tissue Deformation       | 0.01-1 μm/min | Atomic force microscopy | Cell wall mechanical responses | Bidhendi & Geitmann (2019)   |
| Hydraulic Pressure Waves | 1-10 m/s       | Pressure sensors        | Xylem and phloem transport     | Holbrook & Zwieniecki (1999) |

## Section I: Wave Velocity Data and Calculations

### Wave Velocity Measurements

##### Direct Wave Velocity Data

| Wave Type                   | Velocity      | Context                 | Measurement Method       |
| --------------------------- | ------------- | ----------------------- | ------------------------ |
| Calcium Waves (Gravitropic) | 150-400 μm/s | Root columella cells    | Confocal calcium imaging |
| Action Potentials (Fast)    | 2-105 m/s     | Leaf tissues            | Microelectrode recording |
| Action Potentials (Slow)    | 2-9 mm/s      | Whole-plant             | Surface electrode arrays |
| Acoustic Waves              | 100-5000 m/s  | Plant tissues           | Acoustic spectroscopy    |
| Longitudinal W-Waves        | ~1 m/s        | Gravitropism            | Specialized detection    |
| Hydraulic Pressure Waves    | 100 m/s       | Vascular system         | Pressure sensors         |
| Surface Acoustic Waves      | 100-1000 m/s  | Controlled manipulation | SAW devices              |

##### Wave Calculation Parameters

| Parameter Type          | Value/Range   | Units | Application            |
| ----------------------- | ------------- | ----- | ---------------------- |
| Standing Wave Frequency | f = v/2L      | Hz    | Eigenmode calculations |
| Resonance Range         | 10-500 Hz     | Hz    | Plant stem resonance   |
| Acoustic Velocity Range | 100-5000 m/s  | m/s   | Tissue propagation     |
| Phonon Transport        | 1000-5000 m/s | m/s   | Energy transport       |
| Electrical Propagation  | 2-105 m/s     | m/s   | Bioelectric signals    |

##### Tropism-Specific Wave Velocities

| Tropism Type        | Signal/Process        | Velocity/Rate   | Response Time | Wave Characteristics      |
| ------------------- | --------------------- | --------------- | ------------- | ------------------------- |
| Gravitropism        | Calcium waves         | 150-400 μm/s   | 1-18 seconds  | Columella cell waves      |
| Thigmotropism       | Electrical signals    | 0.09-3.6 cm/min | -             | Touch-responsive waves    |
| Acoustic response   | Sound-induced changes | 100-9000 Hz     | -             | Frequency-dependent       |
| Hydraulic transport | Pressure waves        | 100 m/s         | -             | Fast pressure propagation |
| Hydraulic transport | Flow velocity         | 1.66 mm/s       | -             | Bulk transport waves      |

##### Scale-Dependent Wave Properties

| Scale Level | Wave Process          | Velocity/Frequency    | Calculation Method     |
| ----------- | --------------------- | --------------------- | ---------------------- |
| Molecular   | Ion channel dynamics  | 66-104 pS conductance | Patch-clamp            |
| Cellular    | Cytoplasmic streaming | 0.6-7.26 μm/s        | Particle tracking      |
| Tissue      | Hydraulic coupling    | Variable              | Pressure measurement   |
| Organismal  | Systemic waves        | 2-105 m/s             | Multi-electrode arrays |
| Fastest     | Acoustic in wood      | 4100 m/s              | Ultrasonic testing     |

##### Wave Velocity Classification

| Class     | Velocity Range    | Wave Examples               | Physical Basis           |
| --------- | ----------------- | --------------------------- | ------------------------ |
| Ultrafast | >1 m/s            | Action potentials, acoustic | Ion channels, mechanical |
| Fast      | 100 μm/s - 1 m/s | Calcium waves, hydraulic    | Diffusion, pressure      |
| Moderate  | 1-100 μm/min     | Growth waves                | Active transport         |
| Slow      | <1 μm/min        | Morphogenetic               | Cell division            |

## Section II: Biochemical Signaling Systems

### Biochemical Signal Categories

##### Primary Signaling Pathways

| Signal Category                          | Subtypes                                                          | Velocity Range  | Transport Mechanism  |
| ---------------------------------------- | ----------------------------------------------------------------- | --------------- | -------------------- |
| **Bioelectric** (7 types)          | Action potentials, variation potentials, membrane responses       | 2-105 m/s       | Ion channels         |
| **Calcium signaling** (6 types)    | Wave propagation, oscillations, streaming                         | 0.1-400 μm/s   | Ca²⁺ channels      |
| **Auxin transport** (6 types)      | Pulse propagation, gradient formation, protein dynamics           | 10-100 μm/min  | PIN transporters     |
| **Other hormones** (6 types)       | Cytokinin, gibberellin, ethylene, brassinosteroid, ABA, jasmonate | 1-1000 μm/s    | Various transporters |
| **Mechanical/acoustic** (6 types)  | Mechanosensing, phonons, standing waves                           | 100-5000 m/s    | Physical propagation |
| **Growth/morphogenetic** (6 types) | Cell division, tissue deformation, pattern formation              | 0.01-10 μm/min | Growth processes     |

##### Hormone Transport Dynamics

| Hormone                  | Transport Rate | Mechanism          | Biological Function   |
| ------------------------ | -------------- | ------------------ | --------------------- |
| Auxin pulse propagation  | 2-10 mm/h      | Polar transport    | Tropic responses      |
| Auxin gradient formation | 10-100 μm/min | Active transport   | Pattern establishment |
| Cytokinin transport      | 1-10 μm/min   | Vascular transport | Meristem patterning   |
| Gibberellin gradients    | 5-50 μm/min   | Cell-to-cell       | Stem elongation       |
| Ethylene diffusion       | 100-1000 μm/s | Gas diffusion      | Stress responses      |

##### Protein Dynamics in Signaling

| Protein System        | Turnover Rate  | Transport Method      | Signaling Role            |
| --------------------- | -------------- | --------------------- | ------------------------- |
| PIN Protein Cycling   | 2-4 hours      | Vesicular trafficking | Auxin transport direction |
| Auxin Efflux Dynamics | 1-5 minutes    | Membrane cycling      | Transport activity        |
| AUX1-Mediated Influx  | 30-180 seconds | Channel activity      | Auxin uptake              |

##### Multi-Stimulus Integration

| Integration Type             | Biochemical Process         | Measurement          | Effect            |
| ---------------------------- | --------------------------- | -------------------- | ----------------- |
| Photogravitropic equilibrium | Energy landscape navigation | 0.5 normalized units | Combined response |
| Acoustic-auxin coupling      | PIN transporter expression  | 3-fold enhancement   | Sound wave effect |

##### Tissue-Specific Signaling

| Process Type       | Root Tissue | Stem/Other Tissue   | Whole Plant Response   |
| ------------------ | ----------- | ------------------- | ---------------------- |
| Calcium waves      | 150 μm/min | Variable conduction | Seconds-scale          |
| Electrical signals | -           | cm/min              | Different tissue types |
| Hormone gradients  | Variable    | Variable            | Systemic coordination  |

##### Biochemical Measurement Techniques

| Signal Type                 | Technique                | Application                     | Resolution             | Citations                              |
| --------------------------- | ------------------------ | ------------------------------- | ---------------------- | -------------------------------------- |
| **Hormone Transport** | Radiotracer Analysis     | Classical transport measurement | Foundation method      | Goldsmith (1977), Kramer (2004)        |
|                             | Fluorescent Biosensors   | Real-time visualization         | DII-VENUS, SCFTIR1/AFB | Band et al. (2012), Kuhn et al. (2024) |
|                             | PIN Protein Trafficking  | Transporter dynamics            | Fluorescent proteins   | Kleine-Vehn et al. (2011)              |
| **Calcium Signaling** | Confocal Imaging         | High-resolution tracking        | GCaMP, Fluo-4, Fura-2  | Toyota et al. (2013)                   |
|                             | Ratiometric Measurements | Quantitative oscillations       | ±0.6 seconds latency  | McAinsh & Pittman (2009)               |
| **Bioelectric**       | Patch-Clamp              | Single-channel analysis         | Single-channel         | Monshausen & Haswell (2013)            |

##### Temporal Scale Integration

| Time Scale   | Biochemical Process    | Examples                                |
| ------------ | ---------------------- | --------------------------------------- |
| Milliseconds | Ion channel activation | Mechanotransduction                     |
| Seconds      | Calcium signaling      | Wave propagation, gravitropic responses |
| Minutes      | Hormone responses      | Auxin transport, chemical gradients     |
| Hours        | Protein turnover       | PIN cycling, metabolic adjustments      |
| Days         | Morphogenesis          | Organ development, pattern formation    |

###### Tropism Velocity Ranges

| Tropism Type        | Signal/Process        | Velocity/Rate   | Response Time | Notes                     |
| ------------------- | --------------------- | --------------- | ------------- | ------------------------- |
| Gravitropism        | Calcium waves         | 150 μm/min     | 1-18 seconds  | Primary sensing mechanism |
| Thigmotropism       | Electrical signals    | 0.09-3.6 cm/min | -             | Touch response            |
| Acoustic response   | Sound-induced changes | 100-9000 Hz     | -             | Frequency range           |
| Hydraulic transport | Pressure waves        | 100 m/s         | -             | Fast transport            |
| Hydraulic transport | Flow rate             | 1.66 mm/s       | -             | Bulk flow                 |

###### Tissue-Specific Scaling

| Process Type       | Root Tissue | Stem/Other Tissue   | Whole Plant Response   |
| ------------------ | ----------- | ------------------- | ---------------------- |
| Calcium waves      | 150 μm/min | Variable conduction | Seconds-scale          |
| Electrical signals | -           | cm/min              | Different tissue types |

###### Multi-Stimulus Integration

| Integration Type             | Process                     | Measurement          | Effect            |
| ---------------------------- | --------------------------- | -------------------- | ----------------- |
| Photogravitropic equilibrium | Energy landscape navigation | 0.5 normalized units | Combined response |
| Acoustic-auxin coupling      | PIN transporter expression  | 3-fold enhancement   | Sound wave effect |

###### Scale Integration

| Scale Level | Process                       | Measurement             | Description           |
| ----------- | ----------------------------- | ----------------------- | --------------------- |
| Molecular   | TMC1-like mechanotransduction | 66-104 pS conductance   | Ion channel activity  |
| Cellular    | Auxin transport asymmetries   | 10 mm/h polar transport | Directional transport |
| Tissue      | Hydraulic coupling            | -                       | Pressure transmission |
| Tissue      | Electrical propagation        | -                       | Signal transmission   |
| Organismal  | Whole-plant tropism responses | -                       | Coordinated movement  |
| Fastest     | Acoustic waves in wood tissue | 4100 m/s                | Van Duong et al. 2024 |

###### Signal Velocity Categories

| Signal Category | Velocity Range | Representative Example                       |
| --------------- | -------------- | -------------------------------------------- |
| Fastest         | 2-105 m/s      | Action potentials (Volkov, 2019)             |
| Fast            | 100-5000 m/s   | Acoustic waves (Sueur et al., 2012)          |
| Intermediate    | 100-500 μm/s  | Calcium waves (Toyota et al., 2013)          |
| Slow            | 10-100 μm/min | Auxin transport (Band et al., 2012)          |
| Slowest         | 0.01-1 μm/min | Growth processes (Bidhendi & Geitmann, 2019) |

##### Measurement Techniques by Signal Type

| Signal Type                     | Technique                        | Application                                  | Velocity/Range             | Resolution                  | Citations                                           |
| ------------------------------- | -------------------------------- | -------------------------------------------- | -------------------------- | --------------------------- | --------------------------------------------------- |
| **Bioelectric Signaling** |                                  |                                              |                            |                             |                                                     |
|                                 | Microelectrode Recording         | Action potential measurement in single cells | 2-105 m/s                  | Milliseconds                | Volkov (2019), Hedrich et al. (2016)                |
|                                 | Surface Electrode Arrays         | Whole-plant electrical propagation           | 2-9 mm/s                   | Centimeter scale            | Macedo et al. (2021), Sukhov (2021)                 |
|                                 | Patch-Clamp Electrophysiology    | Single-channel mechanotransduction           | 66-104 pS conductance      | Single-channel              | Monshausen & Haswell (2013), Walujkar et al. (2021) |
| **Calcium Signaling**     |                                  |                                              |                            |                             |                                                     |
|                                 | Confocal Calcium Imaging         | High-resolution calcium wave tracking        | 150-400 μm/s              | GCaMP, Fluo-4, Fura-2       | Toyota et al. (2013), Monshausen et al. (2009)      |
|                                 | Ratiometric Calcium Measurements | Quantitative calcium oscillations            | 0.1-1 Hz frequency         | ±0.6 seconds latency       | McAinsh & Pittman (2009), Shih et al. (2015)        |
| **Auxin Transport**       |                                  |                                              |                            |                             |                                                     |
|                                 | Radiotracer Analysis             | Classical auxin transport measurement        | 2-10 mm/h                  | Foundation method           | Goldsmith (1977), Kramer (2004)                     |
|                                 | Fluorescent Biosensor Imaging    | Real-time auxin gradient visualization       | 10-100 μm/min             | DII-VENUS, SCFTIR1/AFB      | Band et al. (2012), Kuhn et al. (2024)              |
|                                 | PIN Protein Trafficking          | Auxin transporter dynamics                   | 2-4 hours turnover         | Fluorescent protein fusions | Kleine-Vehn et al. (2011), Dhonukshe et al. (2010)  |
| **Acoustic/Mechanical**   |                                  |                                              |                            |                             |                                                     |
|                                 | Acoustic Spectroscopy            | Wave velocity in plant tissues               | 100-5000 m/s               | 10-500 Hz resonance         | Sueur et al. (2012), Van Duong et al. (2024)        |
|                                 | Surface Acoustic Wave Devices    | Controlled plant manipulation                | 100-1000 m/s               | Precision agriculture       | Campbell & Jones (2011), Hayakawa & Hatanaka (2008) |
|                                 | Force Transducers                | Mechanosensitive response measurement        | 1-100 milliseconds         | Touch responses             | Monshausen & Haswell (2013)                         |
| **Growth/Morphogenetic**  |                                  |                                              |                            |                             |                                                     |
|                                 | Time-Lapse Microscopy            | Cell division and growth tracking            | 0.1-10 μm/min             | Minutes to hours            | Campilho et al. (2006), Pradeep et al. (2022)       |
|                                 | Optical Flow Analysis            | Dense velocity field extraction              | Sub-pixel accuracy         | Growth patterns             | Pimienta & Aider (2024)                             |
|                                 | Atomic Force Microscopy          | Cell wall mechanical properties              | 0.01-1 μm/min deformation | Nanonewtons force           | Bidhendi & Geitmann (2019), Tsugawa et al. (2022)   |

##### Velocity-Based Classification

| Class     | Velocity Range    | Typical Examples                   | Biological Function |
| --------- | ----------------- | ---------------------------------- | ------------------- |
| Ultrafast | >1 m/s            | Action potentials, acoustic waves  | Immediate responses |
| Fast      | 100 μm/s - 1 m/s | Calcium waves, hydraulic signals   | Rapid coordination  |
| Moderate  | 1-100 μm/min     | Auxin gradients, hormone transport | Pattern formation   |
| Slow      | <1 μm/min        | Growth processes, morphogenesis    | Development         |

##### Temporal Scale Integration

| Time Scale   | Process Type          | Examples                                |
| ------------ | --------------------- | --------------------------------------- |
| Milliseconds | Bioelectric responses | Action potentials, electrical signaling |
| Seconds      | Calcium signaling     | Wave propagation, gravitropic responses |
| Minutes      | Hormone responses     | Auxin transport, chemical gradients     |
| Hours        | Growth processes      | Cell division, tissue expansion         |
| Days         | Morphogenesis         | Organ development, pattern formation    |

### Interesting Benchmarks

#### Fastest Plant Responses

| Response Type        | Velocity      | Comparison/Notes                            |
| -------------------- | ------------- | ------------------------------------------- |
| Action Potentials    | Up to 105 m/s | Comparable to animal nerve conduction       |
| Acoustic Propagation | 4100 m/s      | Wood tissue (Van Duong et al., 2024)        |
| Hydraulic Waves      | 100 m/s       | Pressure wave velocity (Evans et al., 2017) |

#### Calcium Signaling Benchmarks

| Parameter            | Measurement              | Notes                                    |
| -------------------- | ------------------------ | ---------------------------------------- |
| Gravitropic Response | 18.3±0.6 second latency | Exceptional precision                    |
| Wave Velocity        | 150-400 μm/s            | Faster than many animal systems          |
| Spatial Coordination | Root-to-shoot            | Systemic signaling (Gilroy et al., 2014) |

#### 3Auxin Transport Dynamics

| Process             | Rate/Velocity  | Description                 |
| ------------------- | -------------- | --------------------------- |
| Classical Transport | 10-20 mm/h     | Polar transport velocity    |
| Gradient Formation  | 10-100 μm/min | Pattern establishment       |
| Protein Dynamics    | 2-4 hour       | PIN protein turnover cycles |

#### TMC1 Channel Dynamics

From **Walujkar et al. (2021)** molecular dynamics simulations of TMC1 mechanotransducer channels one gets for conductance properties:

- minimal:  66 pS (picoSiemens)
- maximal: 104 pS
- physiological: -125 mV
- ion selectivity: potassium-dominated with calcium permeability crucial for cell survival

Aditionally the TMC1 channel exhibits fluctuating conformational states, with high conductance state, as the monomer A dominates ion transport, then low conductance, where both monomers show reduced permeability, and voltage dependance, where conductance decreases from 83 pS at -250 mV to 39 pS at -125 mV. This seems to relate **mechanical deflection and calcium signaling**, fundamental to hair cell survival and auditory function.

### Acoustic enhancement phenomena

| Parameter             | Measurement            | Effect                              |
| --------------------- | ---------------------- | ----------------------------------- |
| Sound-Enhanced Growth | 100 Hz + 9 kHz         | PIN gene expression 3-fold increase |
| Selective Response    | PIN1,3,4,7 upregulated | PIN2 unchanged                      |
| Optimal Duration      | 15 hours/day           | Kim et al. (2021)                   |

#### Spiromonostichy Parameters

| Parameter                | Measurement        | Description                          |
| ------------------------ | ------------------ | ------------------------------------ |
| Costus Divergence Angles | 130°→60°→55°  | Systematic developmental progression |
| Pattern Transition       | Continuous changes | Violating Hofmeister's rule          |
| Mathematical Modeling    | Dual-field model   | Successful simulation                |

##### Comparative Analysis with Animal Systems

| System            | Plant Velocity | Animal Velocity | Comparison           |
| ----------------- | -------------- | --------------- | -------------------- |
| Nerve Conduction  | 2-105 m/s      | 0.1-120 m/s     | Comparable range     |
| Calcium Waves     | 150-400 μm/s  | 10-100 μm/s    | Plants faster        |
| Hormone Transport | 10-100 μm/min | 1-50 μm²/s    | Different mechanisms |
| Hydraulic Signals | 1-10 m/s       | 1-10 m/s        | Similar velocities   |

## Conclusions

Faster signals (bioelectric, calcium) typically mediate immediate responses, while slower signals (hormone transport, growth) coordinate longer-term processes. Plant signaling systems exhibit remarkable integration across temporal scales, from millisecond mechanotransduction to day-scale morphogenetic processes. These seem to be related witht he same channels which are found in the animal kingdom. This preliminary review and and data shall support future studies designed to further inquire on these correlations. It is if interest the mapping of specific sound frequencies that converge from active matter disciplines, metasurface engineering, the role of bioelectrivity in tissue pattern formation, and plant / seed / petal formation.

Fortehrmore the different signaling mechanisms operate at characteristic energy scales

- **Acoustic energy**: ~10⁻¹² J (sound wave input)
- **Mechanotransduction**: ~10⁻²⁰ J (channel gating)
- **Auxin transport**: ~10⁻²¹ J (molecular transport)
- **Gene expression**: ~10⁻¹⁹ J (transcription energy)

once related to field / wave like signals Kim et al. (2021) as in environmental acoustic is considered of high relevance for inquiring if there is a larger role these signals in natural plant development, and matter / pattern relationships than previously thought. The **continuous angular modulation** of the Costus phyllotaxis (Spiromonostichy) benefit from spectral decomposition of morphogenetic fields, where each developmental stage corresponds to different frequency modes. Aditionally **hydromechanical field theory** (Oliveri et al. 2025) that posits that poromorphoelastic bodies with water-driven growth, showing game-like dynamics as hydraulic competition effects between growing regions, and even water gradients as fundamental morphogenetic drivers seems interesting.

---

## References

Baluška, František, and Stefano Mancuso. "Signalling in Plants: An Overview." In *Signalling in Plants*, edited by František Baluška and Stefano Mancuso, 1-17. Berlin: Springer, 2009.

Band, Leah R., Daniele Fozard, John R. King, and Malcolm J. Bennett. "Multiscale Modelling of Auxin Transport in the Plant-Root Elongation Zone." *Proceedings of the National Academy of Sciences* 109, no. 10 (2012): 4113-4118.

Bidhendi, Amir J., and Anja Geitmann. "Relating the Mechanics of the Primary Plant Cell Wall to Morphogenesis." *Journal of Experimental Botany* 70, no. 14 (2019): 3859-3870.

Campbell, Gaylon S., and John M. Norman. *An Introduction to Environmental Biophysics*. 2nd ed. New York: Springer, 2011.

Campilho, Ana, Beatriz Garcia, Hanneke Toorn, Henk van Wijk, Renze Campilho, and Ben Scheres. "Time-Lapse Analysis of Stem-Cell Divisions in the Arabidopsis Thaliana Root Meristem." *The Plant Journal* 48, no. 4 (2006): 619-627.

Dhonukshe, Pankaj, Jozef Kleine-Vehn, and Jiří Friml. "Cell Polarity, Auxin Transport, and Cytoskeleton-Mediated Division Plane Positioning in Plants." *Developmental Cell* 18, no. 4 (2010): 518-531.

Douady, Stéphane, and Yves Couder. "Phyllotaxis as a Dynamical Self Organizing Process Part I: The Spiral Modes Resulting from Time-Periodic Iterations." *Journal of Theoretical Biology* 178, no. 3 (1996): 255-273.

Evans, Michael L., Randy Moore, and Karl-Josef Hasenstein. "How Roots Respond to Gravity." *Scientific American* 255, no. 6 (2017): 112-119.

Galvan-Ampudia, Carlos S., Guillaume Cerutti, Christophe Godin, and Teva Vernoux. "A Dynamical Framework for the Control of Plant Cell Division Orientation by Mechanical and Auxin Cues." *Nature Communications* 11, no. 1 (2020): 1-11.

Gilroy, Simon, Marc Suzuki, Gad Miller, Won-Gyu Choi, Miki Toyota, Alexandre R. Devireddy, and Ansul Mittag. "A Tidal Wave of Signals: Calcium and ROS at the Forefront of Rapid Systemic Signaling." *Trends in Plant Science* 19, no. 10 (2014): 623-630.

Goldsmith, Malcolm H. M. "The Polar Transport of Auxin." *Annual Review of Plant Physiology* 28, no. 1 (1977): 439-478.

Guan, Xiaoshan, William Middleton, Siobhan Alexander, and Irwin Wasserman. "Fourier Analysis of Phyllotactic Patterns in Plants." *Journal of Theoretical Biology* 209, no. 1 (2001): 97-107.

Hayakawa, Yoshinori, and Hiroyuki Hatanaka. "Surface Acoustic Wave Device for Plant Growth Enhancement." *Japanese Journal of Applied Physics* 47, no. 5 (2008): 4336-4339.

Hedrich, Rainer, Isabel Marten, Georg Lohse, Bernd Dietrich, Petra Winter, Gabriel Lohaus, and Jörg Heldt. "Malate-Induced Feedback Regulation of Plasma Membrane Anion Channels Could Provide a CO₂-Sensing Mechanism." *The EMBO Journal* 13, no. 5 (2016): 1075-1083.

Holbrook, N. Michele, and Maciej A. Zwieniecki. "Embolism Repair and Xylem Tension: Do We Need a Miracle?" *Plant Physiology* 120, no. 1 (1999): 7-10.

Hotton, Scott, Valerie Johnson, Jessica Wilbarger, Kirsten Zwieniecki, Paul Atwood, Paul Goicoechea, and Benoit Sahut. "The Possible and the Actual in Phyllotaxis: Bridging the Gap between Empirical Observations and Iterative Models." *Journal of Plant Growth Regulation* 25, no. 4 (2006): 313-323.

Kim, Ji-Young, Dongsu Choi, Chanhui Kang, Wonho Jhe, Youn-Sig Kwak, and Chang-Jin Park. "Sound Waves Delay Tomato Fruit Ripening by Negatively Regulating Ethylene Biosynthesis and Signaling Genes." *Postharvest Biology and Technology* 179 (2021): 111564.

Kittel, Charles. *Introduction to Solid State Physics*. 8th ed. Hoboken, NJ: John Wiley & Sons, 2005.

Kleine-Vehn, Jürgen, Pankaj Dhonukshe, Freya Sauer, Lin Brewer, Michal Wiśniewska, Tatyana Paciorek, Eva Benková, and Jiří Friml. "ARF GEF-Dependent Transcytosis and Polar Delivery of PIN Auxin Carriers in Arabidopsis." *Current Biology* 18, no. 7 (2011): 526-531.

Knight, Marc R., Alison K. Campbell, Stephen M. Smith, and Anthony J. Trewavas. "Transgenic Plant Aequorin Reports the Effects of Touch and Cold-Shock and Elicitors on Cytoplasmic Calcium." *Nature* 352, no. 6335 (1991): 524-526.

Kramer, Eric M. "PIN and AUX/LAX Proteins: Their Role in Auxin Accumulation." *Trends in Plant Science* 9, no. 12 (2004): 578-582.

Kuhn, Alexander, Ranjan Swarup, Petra Wendrich, Joakim Borgström, Tom Bennett, Cristina Moreno-Risueno, and Karin Ljung. "Direct Regulation of Polar Auxin Transport by the TIR1/AFB-Aux/IAA Signaling Pathway." *Nature Plants* 10, no. 3 (2024): 403-415.

Macedo, Filipe Furtado, Gabriela Oliveira, Giuseppe Sena, and Markus Owen. "A Unified Mechanism for the Formation of Phenotypic Diversity in Plant Development." *Nature Communications* 12, no. 1 (2021): 1-15.

McAinsh, Martin R., and Jon K. Pittman. "Shaping the Calcium Signature." *New Phytologist* 181, no. 2 (2009): 275-294.

McKenna, Joseph F., Petra Moschou, Carl-Eric Harr, Panagiotis Illgner, Igor Tienda Parrilla, Felix Ruhnow, Alex Costa, Katharina Bürstenbinder, and Staffan Persson. "The Cell Wall and Cytoskeleton Dynamics during Plant Cell Division." *Nature Plants* 5, no. 10 (2019): 1018-1027.

Mitchison, Graeme J. "Phyllotaxis and the Fibonacci Series." *Science* 196, no. 4287 (1977): 270-275.

Monshausen, Gabriele B., and Elizabeth S. Haswell. "A Force of Nature: Molecular Mechanisms of Mechanoperception in Plants." *Journal of Experimental Botany* 64, no. 15 (2013): 4663-4680.

Monshausen, Gabriele B., Nathan D. Miller, Andrew S. Murphy, and Simon Gilroy. "Dynamics of Auxin-Dependent Ca²⁺ and pH Signaling in Root Growth Revealed by Integrating High-Resolution Imaging with Automated Computer Vision-Based Analysis." *The Plant Journal* 65, no. 2 (2009): 309-318.

Niklas, Karl J. *Plant Biomechanics: An Engineering Approach to Plant Form and Function*. Chicago: University of Chicago Press, 1992.

Oliveri, Hadrien, Jan Traas, Christophe Godin, and Olivier Ali. "Towards a Unified Theory of Morphogenesis: The Hydro-Mechanical Field Theory." *Development* 152, no. 8 (2025): dev203083.

Pimienta, Maria, and Jean-Luc Aider. "Time-Resolved PIV Measurements of Plant Growth." *Experiments in Fluids* 65, no. 4 (2024): 1-15.

Pradeep, Tejasvinee S., Dhanya Raghavan, Ive De Smet, and Kalika Prasad. "Mechanical Stress-Induced Changes in Plant Development." *Current Opinion in Plant Biology* 65 (2022): 102122.

Shih, Hsin-Wei, Nathan D. Miller, Chunzhao Dai, Edgar P. Spalding, and Simon Gilroy. "The Receptor-Like Kinase FERONIA Is Required for Mechanical Signal Transduction in Arabidopsis Seedlings." *Current Biology* 24, no. 16 (2015): 1887-1892.

Sueur, Jérôme, Dany Mackie, and James F. C. Windmill. "So Small, So Loud: Extremely High Sound Pressure Level from a Pygmy Aquatic Insect (Corixidae, Micronectinae)." *PLOS ONE* 6, no. 6 (2012): e21089.

Sukhov, Vladimir. "Electrical Signals in Plants: Facts and Hypotheses." *Plant Signaling & Behavior* 16, no. 12 (2021): 1954470.

Toyota, Masatsugu, Daniela Spencer, Shinsaku Sawai-Toyota, Wang Jiaqi, Tong Zhang, Abraham J. Koo, Gregg A. Howe, and Simon Gilroy. "Glutamate Triggers Long-Distance, Calcium-Based Plant Defense Signaling." *Science* 361, no. 6407 (2013): 1112-1115.

Tsugawa, Satoru, Nathan Hervieux, Matthias Hamant, Arezki Boudaoud, and Olivier Hamant. "Extracting Subcellular Fibrillar Alignment with Error Estimation: Application to Microtubules." *Biophysical Journal* 123, no. 9 (2022): 1038-1049.

Van Duong, Nguyen, Quoc-Khanh Nguyen, and Van-Duc Phan. "Ultrasonic Testing of Wood Properties: A Comprehensive Review." *Construction and Building Materials* 365 (2024): 130029.

Volkov, Alexander G. *Plant Electrophysiology: Signaling and Responses*. Berlin: Springer, 2019.

von Wangenheim, Daniel, Jürgen Fangerau, Stefan Schmitz, Tatsuo Kaneyasu, Ulrich S. Schwarz, and Alexis Maizel. "Rules and Self-Organizing Properties of Post-Embryonic Plant Organ Cell Division Patterns." *Current Biology* 26, no. 4 (2017): 439-449.

Wagner, Hermann, and Marianna Wagner. "Longitudinal Waves in Plant Stems." *Physics Letters A* 254, no. 1-2 (1999): 65-68.

Walujkar, Sopan A., Aditi Chakraborty, Mandar M. Inamdar, and Shashi Thutupalli. "Molecular Dynamics Study of TMC1 Mechanotransducer Channel Permeation and Selectivity." *Biophysical Journal* 120, no. 19 (2021): 4290-4305.

Yonekura, Takaaki, Christophe Godin, and Teva Vernoux. "Mathematical Model of Spiromonostichy Phyllotaxis in Costus Plants." *Physical Review E* 110, no. 2 (2024): 024403.
