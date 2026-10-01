# Hi, I'm Wei-Hong Ruan

Biomedical researcher working at the intersection of
**functional neuroimaging, EEG, focused ultrasound neuromodulation,
and real-time closed-loop neuroscience**.

My research focuses on combining neural signal analysis, neuroimaging, and adaptive stimulation to investigate and modulate brain activity. I am particularly interested in integrating EEG-based brain-state detection with functional MRI and focused ultrasound neuromodulation to study dynamic changes in neural activity and brain networks.

My work involves real-time EEG processing, wavelet-based signal analysis, individualized event detection, and event-triggered stimulation within closed-loop experimental frameworks. In parallel, I use resting-state fMRI, ROI-based analysis, and functional connectivity methods to investigate how neuromodulation affects large-scale brain networks.

More broadly, I am interested in developing multimodal and state-dependent neurotechnology approaches that combine electrophysiology, neuroimaging, and non-invasive stimulation for more precise and adaptive modulation of brain function.

## Research Interests

- Functional neuroimaging and resting-state fMRI
- EEG and neural signal processing
- Real-time brain-state detection
- Closed-loop neuromodulation
- Focused ultrasound neuromodulation
- Multimodal neuroscience
- Brain network and functional connectivity analysis

## Technical Skills

### Neuroimaging
- 7T small-animal MRI
- Resting-state fMRI preprocessing
- Image registration
- ROI-based analysis
- Functional connectivity analysis
- DCE-MRI
- Quantitative R1 mapping

### Neural Signal Analysis
- EEG acquisition and preprocessing
- Wavelet analysis
- Time-frequency analysis
- Individualized dynamic thresholding
- Real-time seizure-related activity detection

### Closed-Loop Neurotechnology
- EEG-guided closed-loop stimulation
- Event-triggered experimental control
- Focused ultrasound neuromodulation

### Programming
- MATLAB
- Python
- Scientific data analysis
- Data visualization
- Medical image analysis

## Featured Projects

### EPI0 DICOM-to-NIfTI Pipeline

A modular MATLAB pipeline for preparing rodent EPI data before downstream fMRI preprocessing.

The workflow performs dataset-specific DICOM cleanup, removes predefined initial fMRI time points, converts the remaining EPI data to NIfTI format, adjusts spatial metadata, prepares the output as `EPI0.nii`, and organizes the data for subsequent preprocessing.

**Workflow**

DICOM cleanup → Initial time-point removal → NIfTI conversion → EPI0 preparation → Downstream rodent fMRI preprocessing

**Tools:** MATLAB R2025b, DICOM/NIfTI processing, rodent fMRI

[View repository](https://github.com/WeiHongRuan/EPI0-DICOM-to-NIfTI-Pipeline)

---

### Ultrasound Signal Generator Control

A Python-based instrument-control program for configuring and operating a **GW Instek AFG-3022 arbitrary function generator** for burst-mode ultrasound experiments.

The program communicates with the signal generator through **PyVISA** and allows the VISA resource address and major ultrasound waveform parameters to be modified directly from a centralized user-settings section at the beginning of the script.

Adjustable parameters include:

- VISA instrument address
- carrier frequency
- output amplitude
- burst duration
- pulse repetition frequency (PRF)
- total output duration
- output-channel control

The program automatically calculates the pulse repetition period and number of cycles per burst, validates the configured waveform parameters, controls the signal-generator output, and attempts to safely disable the output before closing the VISA connection.

**Workflow**

Keysight Connection Expert → VISA address identification → Python / PyVISA → GW Instek AFG-3022 → Burst-mode waveform configuration → Ultrasound stimulation output

**Tools:** Python, PyVISA, Keysight Connection Expert, GW Instek AFG-3022

[View repository](https://github.com/WeiHongRuan/Ultrasound-Signal-Generator-Control)

## Research Experience

My master's research at National Taiwan University focused on the
development and evaluation of an EEG-guided closed-loop focused
ultrasound system for a rodent epilepsy model.

The system integrated EEG acquisition, wavelet-based real-time signal
processing, individualized detection thresholds, event detection,
and event-triggered ultrasound stimulation.

I also performed 7T resting-state fMRI acquisition and analysis to
evaluate brain-network changes associated with neuromodulation.

## Publications & Conference Contributions

### Peer-Reviewed Publication

- P.-C. Chu, W.-H. Ruan, C.-S. Huang, Y.-J. Juan, J.-H. Chen, H.-Y. Yu, R. S. Fisher, and H.-L. Liu,  
  **"Focused ultrasound suppresses pentylenetetrazol-induced epileptiform activity in rats and alters connectivity measured by functional MRI."**  
  *Scientific Reports*, 2025.  
  DOI: 10.1038/s41598-025-15305-0

### Selected Conference Contributions

- **W.-H. Ruan**, P.-C. Chu, Y.-C. Wang, J.-H. Chen, and H.-L. Liu,  
  **"Evaluating the efficacy of scalp-EEG feedback focused ultrasound stimulation for epilepsy treatment."**  
  IEEE International Ultrasonics Symposium, 2025 — Oral Presentation.

- P.-C. Chu*, **W.-H. Ruan***, H.-L. Liu, and J.-H. Chen,  
  **"Exploring epileptic connectivity: A comparative study of kainic acid and pentylenetetrazol using rs-fMRI and focused ultrasound."**  
  ISMRM Annual Meeting, 2025 — Oral Presentation.  
  *Co-first author.*

- **W.-H. Ruan**, P.-C. Chu, Y.-J. Juan, J.-H. Chen, and H.-L. Liu,  
  **"Modulation of acute seizures in pentylenetetrazol models: Effective suppression by high- and low-dose focused ultrasound."**  
  International Symposium on Therapeutic Ultrasound, 2024 — Poster Presentation.

## Research Training

Laboratory Academic Visit & fMRI Training  
**The University of Queensland, Australia**

Training included experimental animal preparation, fMRI acquisition,
and preprocessing workflows involving FSL, AFNI, and ANTs.

---

More research code and analysis pipelines will be added progressively.
