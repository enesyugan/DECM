# DECM Dataset

This repository contains data related to the Paper: **DECM: Evaluating Bilingual ASR Performance on a Code-switching/mixing Benchmark**

## About the Dataset

The DECM dataset consists of Code-Switching/Code-Mixing (CSW/CM) data collected from YouTube videos. The initial transcription, segmentation, and manual correction were performed using the website [ASROT-Website](https://transcript-corrector.dataforlearningmachines.com/).

The dataset is split into three parts:
- low-CSW
- mid-CSW
- high-CSW

## Data Statistics

| Split    | # utts | Duration  | En-ratio | SPF  | CMI   |
|----------|--------|-----------|----------|------|-------|
| low-CSW  | 401    | 50.68 min | <2 %     | 0.02 | 0.013 |
| mid-CSW  | 553    | 75.59 min | 2-9 %    | 0.07 | 0.040 |
| high-CSW | 602    | 78.85 min | >9 %     | 0.16 | 0.113 |


## Data Download

To download the dataset, you can use the provided download scripts located in the `download-mng` directory. Please note that the licensing for this data is handled by Google, which is the host of the YouTube website.

For access to the transcripts, please make a request to **enes.ugan@kit.edu**

## Citation

If you use this dataset in your research, please cite the following paper:

[Author(s). "Title of the Paper." Conference/Journal Name, Year.](https://link-to-paper)
