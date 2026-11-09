# ds004616 QC

Supplementary quality-control material for OpenNeuro dataset ds004616.

Dataset:
https://openneuro.org/datasets/ds004616

This repository contains the outputs generated during processing of the anatomical T2w images for inclusion in the PAM50-normalized-metrics project.

## Contents

- `contrast_agnostic_segmentations/`
  - Contrast-agnostic spinal cord segmentations generated with `sct_deepseg spinalcord`.

- `qc_contrast_agnostic/`
  - SCT quality-control reports for the spinal cord segmentations.

- `automatic_disc_labels/`
  - Automatic intervertebral disc labels generated with `sct_deepseg spine`.

- `qc_spine/`
  - Quality-control reports generated during automatic spine/disc labeling.

A total of 50 T2w scans from 26 participants were processed.

The corresponding PAM50-normalized morphometric measurements are included in:
https://github.com/spinalcordtoolbox/PAM50-normalized-metrics
