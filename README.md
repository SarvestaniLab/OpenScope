This dataset was collected by the Allen Institute as part of [OpenScope](https://www.allenneuraldynamics.org/projects/openscope) to test the unified mouse V2 hypothesis presented in [(Rowley & Sedigh-Sarvestani, 2024)](https://www.biorxiv.org/content/10.1101/2024.10.10.617533v3). By releasing the dataset, we hope to allow others to independently test this hypothesis and other hypotheses surrounding mouse visual cortex organization.


The dataset includes It includes electrophysiological recordings (Ephys) using four Neuropixels probes within V1 and two-photon measurements (Ophys) from 12 V1 locations, together with stimuli for receptive-field mapping and characterization of orientation (Ori), spatial-frequency (SF), and temporal-frequency (TF) tuning.

## Stimuli

The stimuli for the electrophysiological recordings includes gabor patches (fixed TF and SF with varying Ori: 0, 45,90), full-field drifting gratings (TF: 1.0, 2.0, 4.0, 8.0, 15.0; SF: 0.02, 0.04, 0.08, 0.16, 0.32; Ori: 0, 45, 90, 135), and full-field flashes.   

The stimuli for the two-photon measurements includes gabor patches (fixed TF and SF with varying Ori: 0, 45,90) and full-field drifting gratings (TF: 1.0, 2.0, 4.0, 8.0, 15.0; SF: 0.02, 0.04, 0.08, 0.16, 0.32; Ori: 0, 45, 90, 135).   

An example truncated ephys session is shown below.

<p align="center">
  <video src="https://github.com/user-attachments/assets/1c861f92-a653-4379-990b-01a02dc8050d" width="30%"></video>
</p>


## Recordings

#### Ephys
The following data is contained in the electrophysiological recordings.

|   Mouse ID | Type                |   Number of sessions | Stimuli                                                                                                                                      |   Number of probes |   Number of units across probes |
|-----------:|:--------------------|---------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------|-------------------:|------------------:|
|     810531 | Mus musculus, wt/wt |                    1 | drifting_gratings_field_block_presentations, flash_field_block_presentations, receptive_field_block_presentations, spontaneous_presentations |                  4 |              2251 |
|     810532 | Mus musculus, wt/wt |                    1 | drifting_gratings_field_block_presentations, flash_field_block_presentations, receptive_field_block_presentations, spontaneous_presentations |                  4 |              2202 |
|     813810 | Mus musculus, wt/wt |                    1 | drifting_gratings_field_block_presentations, flash_field_block_presentations, receptive_field_block_presentations, spontaneous_presentations |                  4 |              2996 |
|     815152 | Mus musculus, wt/wt |                    1 | drifting_gratings_field_block_presentations, flash_field_block_presentations, receptive_field_block_presentations, spontaneous_presentations |                  4 |              2353 |
|     816305 | Mus musculus, wt/wt |                    1 | drifting_gratings_field_block_presentations, flash_field_block_presentations, receptive_field_block_presentations, spontaneous_presentations |                  4 |              2732 |
|     816308 | Mus musculus, wt/wt |                    1 | drifting_gratings_field_block_presentations, flash_field_block_presentations, receptive_field_block_presentations, spontaneous_presentations |                  4 |              2512 |
|     817334 | Mus musculus, wt/wt |                    1 | drifting_gratings_field_block_presentations, flash_field_block_presentations, receptive_field_block_presentations, spontaneous_presentations |                  4 |              2925 |
|     817335 | Mus musculus, wt/wt |                    1 | drifting_gratings_field_block_presentations, flash_field_block_presentations, receptive_field_block_presentations, spontaneous_presentations |                  4 |              2403 |
