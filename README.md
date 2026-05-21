# Omar Ali-Yare

Biomedical Engineer (B.Eng., Toronto Metropolitan University, April 2026). I design the analog hardware that turns biological signals into clean data, and the software that turns that data into something useful — front-end electronics, embedded firmware, and signal processing for medical devices.

Founding engineer at **GlucoSolutions**, building a non-invasive continuous glucose monitor. 1st place TMU Engineering Competition 2024, 3rd place Ontario Engineering Competition 2025, $50K raised in grants.

📍 Toronto, ON &nbsp;·&nbsp; 📫 <Omarltk03@gmail.com> &nbsp;·&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/omar-ali-yare/)

---

## What I work on

**Analog front-ends** for biopotential and optical acquisition — transimpedance amplifiers, instrumentation amps, active filtering, right-leg-drive, ADC conditioning. Schematic capture and iterative PCB prototyping in Proteus, NI Multisim, and Altium. SMD and through-hole soldering, board rework.

**Embedded firmware** in C/C++ on Arduino and PIC (MPLAB X), VHDL on Quartus II. LED-drive timing, photodiode sampling, sensor pipelines, serial telemetry.

**Biomedical signal processing and ML** in MATLAB and Python (NumPy, SciPy, scikit-learn). Spectroscopy regression, ECG pathology classification, EEG motor-imagery decoding.

---

## Selected projects

### 🩸 GlucoSolutions — Non-Invasive Continuous Glucose Monitor
*Founding engineer · Jan 2024 – Present*

Wearable NIR-spectroscopy device that estimates blood glucose without a fingerstick. Derived optical and electrical design requirements from first principles (Beer-Lambert absorbance, 940 nm / 1450 nm band selection, scattering vs. absorption tradeoffs). Designed the full analog front-end (photodiode TIA → active bandpass → ADC conditioning), wrote the Arduino C/C++ firmware, and built a MATLAB/Excel regression model that converts raw NIR signal to glucose concentration. **88% detection accuracy** against controlled glucose solutions across multiple hand-soldered board revisions. Led a 4-person team and raised **$50K** in grants.

`MATLAB` `Proteus` `NI Multisim` `Altium` `Arduino` `C/C++` `Fusion 360`

> 🏆 1st place — TMU Engineering Competition (Innovative Design), 2024
> 🏆 3rd place — Ontario Engineering Competition, 2025

### 👕 ECG Pathology Compression Shirt — Capstone
*Lead hardware designer · Sep 2025 – Apr 2026*

Garment-integrated wearable ECG with on-device pathology classification. Designed the analog acquisition chain (instrumentation amp, right-leg-drive, 0.5–40 Hz bandpass, ADC conditioning) for fabric-embedded electrodes, then iteratively debugged the things textbooks don't warn you about: motion artifact, electrode-skin impedance drift, common-mode interference. Trained a Python classification model on the captured waveforms and integrated firmware output with a companion app.

`MATLAB` `Python (SciPy, scikit-learn)` `Altium` `Proteus` `Arduino` `SolidWorks`

### 🧠 EEG Motor Imagery BCI
*2025*

End-to-end EEG signal-processing and classification pipeline on the PhysioNet Motor Movement/Imagery dataset (109 subjects), decoding left- vs. right-hand imagined movement. Spatial filtering, frequency-band features, permutation entropy, LDA classifier under 5-fold stratified CV. Permutation entropy was the strongest single feature across subjects — a finding I wasn't expecting going in.

`Python` `MATLAB` `scikit-learn`

### 🛠️ DFZ Makerspace Booking System — IBZ @ TMU
*Special Projects Intern · Sep 2025 – Apr 2026*

Production booking back-end for the Design Fabrication Zone makerspace. Three linked Airtable tables behind a public form, with a 4-state booking state machine (new / hold / confirmed / rejected) driving Slack, Gmail, and Google Calendar automation. Python scripts for rolling time-slot generation and a setup/teardown pending-slot algorithm that prevents double-bookings. Engineered a Google-Calendar-to-Airtable sync that works around Google's one-way API constraint using lookup/rollup fields with timezone-aware formula logic.

`Python` `Airtable Automations` `REST APIs` `Google Calendar API`

### 🎙️ Voice Intake Assistant — NexHacks (~1,500 hackers)
*2025*

Real-time voice-assistant back-end with streaming voice input and REST API integration. Translated requirements from two nurses and a medical student into a working Figma UX in under 48 hours.

`Python` `LiveKit` `LeanMCP`

---

## Toolbox

**Languages & frameworks** — MATLAB · Python (NumPy, SciPy, scikit-learn) · C / C++ · VHDL · Simulink
**Hardware & EDA** — Altium · Proteus · NI Multisim · Quartus II · MPLAB X · Arduino IDE · LabVIEW
**Lab** — Oscilloscopes · function generators · DC bench supplies · multimeters · SMD + through-hole soldering · board rework
**Mechanical & 3D** — SolidWorks · Fusion 360 · Bambu Lab printing
**Other** — Git · Figma · LiveKit · LeanMCP

---

## Credentials

Standard First-Aid + CPR-C · WHMIS · Biosafety Awareness · Chemical Safety

---

*Open to roles in medical device hardware, embedded systems, and biomedical signal processing. Reach out — I reply to everything.*
