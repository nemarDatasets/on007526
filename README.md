# LEMON-PD-EEG: Resting-State & Walking EEG in Parkinson's Disease Dataset

## Overview

This dataset contains EEG recordings from Parkinson's disease (PD) patients and healthy controls (HC), collected under two behavioral conditions: resting state (sitting) and walking. The dataset was acquired at the Laboratory of Early Markers of Neurodegeneration (LEMON), Tel Aviv Sourasky Medical Center.

---

## Participants

- **Parkinson’s disease (PD):** 116 participants
- **Healthy controls (HC):** 28 participants

### Inclusion criteria (PD):
- Age 40–90  
- Hoehn & Yahr stage ≤ 2  
- MoCA ≥ 21  
- Able to walk independently  

### Exclusion criteria:
- History of stroke or major neurological disorder  
- Brain surgery  
- Significant head injury  
- Inability to walk independently  

All participants provided informed consent. The study was approved by the local ethics committee and conducted in accordance with the Declaration of Helsinki.

---

## Experimental Design

Each participant underwent EEG recording under two conditions:

1. **Resting State** (144 Recordings)
   - Sitting
   - Eyes open
   - Duration: ~4 minutes  

2. **Walking** (133 Recordings)
   - Walking on a treadmill  
   - Duration: ~4 minutes  

Additional clinical data were collected, including:
- **MoCA** (Montreal Cognitive Assessment) - a measure of cognitive function.  
- **MDS-UPDRS**  - Movement Disorder Society Unified Parkinson's Disease Rating Scale - the gold standard clinical rating scale for Parkinson's Disease.
- **CTT** - Color Trails Test - a measure of executive function and processing speed.

---

## EEG Acquisition

- **System:** 64-channel EEG  
- **Montage:** International 10–20 system  

---

## Data Organization

This dataset follows the **Brain Imaging Data Structure (BIDS)** specification.

Typical structure:

```
sub-001/
    eeg/
        sub-001_task-rest_eeg.*
        sub-001_task-walk_eeg.*

participants.tsv
participants.json
dataset_description.json
```

**Inbal Maidan, PhD**  
Tel Aviv Sourasky Medical Center  
Email: inbalm@tlvmc.gov.il
