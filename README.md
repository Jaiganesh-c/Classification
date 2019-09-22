# Classification

Data Set Information:

Important remarks before using this dataset:

1. Each row can not be used independently, because is one of the three replications of one individual. Nature of data is dependent for each subject, but independent from one to another subject. So, traditional technique from machine learning can not be applied to this dataset, because those techniques are based on the independent nature of the instances. There are 240 instances but for only 80 subjects, so they are not independent. Techniques as those presented in Naranjo et al. (2016), Naranjo et al. (2017) or other specifically designed can be used.

2. The concept of replication considered here does not match the classical concept of statistical repeated measurements. The term 'replications' refers to the collection of features extracted from voice recordings belonging to the same subject. Since, in this context, features are extracted from multiple consecutive voice recordings from the same subject, in principle, the features should be identical. The imperfections in technology and the own biological variability result in non-identical replicated features that are more similar to one another than features from different subjects.

3. All information about how the dataset was generated is presented in Naranjo et al. (2016).

Attribute Information:

1. ID: Subjects's identifier.
2. Recording: Number of the recording.
3. Status: 0=Healthy; 1=PD
4. Gender: 0=Man; 1=Woman
5. Pitch local perturbation measures: relative jitter (Jitter_rel), absolute jitter (Jitter_abs), relative average perturbation (Jitter_RAP), and pitch perturbation quotient (Jitter_PPQ).
6. Amplitude perturbation measures: local shimmer (Shim_loc), shimmer in dB (Shim_dB), 3-point amplitude perturbation quotient (Shim_APQ3), 5-point amplitude perturbation quotient (Shim_APQ5), and 11-point amplitude perturbation quotient (Shim_APQ11).
7. Harmonic-to-noise ratio measures: harmonic-to-noise ratio in the frequency band 0-500 Hz (HNR05), in 0-1500 Hz (HNR15), in 0-2500 Hz (HNR25), in 0-3500 Hz (HNR35), and in 0-3800 Hz (HNR38).
8. Mel frequency cepstral coefficient-based spectral measures of order 0 to 12 (MFCC0, MFCC1,..., MFCC12) and their derivatives (Delta0, Delta1,..., Delta12).
9. Recurrence period density entropy (RPDE).
10. Detrended fluctuation analysis (DFA).
11. Pitch period entropy (PPE).
12. Glottal-to-noise excitation ratio (GNE). 

Problem statement: Classify a patient is having parkinson disease or not.
