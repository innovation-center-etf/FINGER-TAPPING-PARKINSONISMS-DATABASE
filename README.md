# FINGER-TAPPING-PARKINSONISMS-DATABASE
Gyroscope recordings obtained from patients with Parkinson's disease and atypical parkinsonisms, as well as healthy controls. 
Data was recorded using 3D gyroscope positioned over the fingernails of the thumb and index finger, while performing finger tapping task according to the UPDRS instructions. Several trials were recorded per subject.
The data was recorded from the right (more affected) hand. 

Each recording/trial is given as a separate .mat file, containing the following fields: 
'diagnosis': either 'CTRL' (healthy control), 'PD' (Parkinson's Disease), 'MSA' (Multiple System Atrophy) or 'PSP' (Progressive Supranuclear Palsy), 
'gyroThumbX': x axis of thumb gyroscope, 'gyroThumbY': y axis of thumb gyroscope, 'gyroThumbZ': z axis of thumb gyroscope, 'gyroIndexX': x axis of index gyroscope, 'gyroIndexY': y axis of index gyroscope, 'gyroIndexZ': z axis of index gyroscope, 
'personID': person code, 
'trialID': trial code,
'fs': sampling rate in Hz (although always 200Hz).






