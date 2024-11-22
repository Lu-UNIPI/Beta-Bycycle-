# Beta Bust Speech Bycycle Analysis
## Neural Engineering Master Degree Thesis Project 
## Title: "Investigation of intracranial electrophysiological dynamics  of the cortico-basal ganglia circuit in Parkinsonian patients performing intraoperative speech production tasks" 
Author: Lucia Poma  
Supervisors: R.M.Richardson, MD, A.Mazzoni  
Co-supervisors: A.Bush, A.Vergani  
Tutor: M.Vissani  
Computational Neuroengineering Lab, Sant'Anna School of Advanced Studies - Brain Modulation Lab, MGH, Harvard Medical School  

This repository can be used to compare different burst detection algorithms (among which, the approach proposed by Voyteck et al.) and assess beta burst features evolution in relation to speech performances.

## Thesis abstract
> This thesis investigates the detection of oscillatory bursts in local field potentials through a time-domain algorithm and examines their modulation during a speech production task in Parkinsonian patients. Beta frequency transient activity, called bursts, is a well-established biomarker for Parkinson’s disease, correlating with symptoms and dopamine dynamics. Speech impairments are common in this disorder; however, the role of STN-cortico connections in speech production are not yet fully understood. I analyzed intracranial cortico-subthalamic simultaneous data from patients undergoing deep brain stimulation (DBS) implantation surgery, compared the performances of three burst detection approaches, and investigated burst features evolution before, during and after speech. Employing a cycle-by-cycle burst analysis allowed for a more reliable output and obtaining more informative features, notably burst frequency and time symmetries. My study contributes to a comprehensive beta activity characterization, encompassing speech-related modulations, with the intent to advance towards a more effective and personalized therapy for Parkinson’s disease and a refinement in scientific knowledge about a complex, uniquely human behaviour that is speech.

Keywords: Parkinson’s, speech, subthalamic nucleus, beta bursts, cycle-by-cycle

## Task and main windows/measures/trial subdivisions?

## Dependencies
The code depends on these repositories:
* fieldtrip: toolbox to analyze electrophysiological data
* bml: fieldtrip wrapper developed by the BrainModulation Lab.
You need to manually download and include (only the main folder!) them in your MATLAB dependencies. After that just run these commands in MATLAB to manage dependencies:
```
bml_defaults
ft_defaults
```
Before running the project, ensure you have the following installed:
- MATLAB 2022a 
- FieldTrip toolbox
- BML toolbox
- python 3.8 or higher
- FOOOF 1.0 wrap for MATLAB
- Bycycle 1.0 wrap for MATLAB

## Structure of the project:
 -  1_data_overview   
 -  2_preprocessing                   
 -  3_timefrquency_analysis            
 -  4_bursting_detection
 -  5_beta_bursts_speech 
 -  6_beta_speech_metrics  
All the functions are in the folder "functions"

Author: Lucia Poma

