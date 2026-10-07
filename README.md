# Beyond Point-Level AUPRC

This repository accompanies **Beyond Point-Level AUPRC: A Resolution-Aware Multi-Level Evaluation Framework for Automatic Sleep Arousal Detection**.

The study evaluates automatic arousal detection at the point, event, boundary, and subject levels using SHHS1 and RNS, including bidirectional cross-dataset external validation.

## Code availability

The full code and usage instructions will be released after the paper is accepted.

## SHHS1 dataset splits

The initial release provides the recording ID lists for the SHHS1 training, validation, and test sets used in the study. The split was performed at the subject level with a fixed random seed of 42.

| Split | Recordings |
| --- | ---: |
| Training | 3,460 |
| Validation | 866 |
| Test | 1,443 |
| Total | 5,769 |

These lists identify the included recordings; they do not contain PSG signals or annotations. SHHS1 data must be obtained separately through the National Sleep Research Resource (NSRR).
