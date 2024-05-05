# Prompt Tuning for Multi-modal Audio Generation
### Authors:
* Christian Alexander (cmalexander@vt.org)
* Daniel Hassler (hassledw@vt.edu)
* Daniel Sabanov (sdaniel19@vt.edu)
* Stephen Owesney (stepowes@vt.edu)
  
## Objective
Our project aims to expand upon a recent SoTA audio generation model, [Make-an-Audio](https://arxiv.org/pdf/2301.12661.pdf), by creating more diverse, stylistic audios. We plan to achieve our goal by leveraging a new audio language model called [Pengi](https://arxiv.org/pdf/2305.11834.pdf) to iteratively refine the output of Make-an-Audio's generation with interpolated prompting.

## Prerequisites
### Install Make-an-Audio
```
git clone git@github.com:Text-to-Audio/Make-An-Audio.git

pip install -r requirements.txt # OR install each package one by one.
```
Then, download the weights:
```
https://drive.google.com/drive/folders/1zZTI3-nHrUIywKFqwxlFO6PjB66JA8jI
```
```
useful_ckpts/
├── bigvnat
│   ├── args.yml
│   └── best_netG.pt
└── maa1_full.ckpt
```

### Install Pengi
```
git clone git@github.com:microsoft/Pengi.git

pip install -r requirements.txt # OR install each package one by one.
```
Then, download the weights and move to `configs` folder:
```
https://zenodo.org/records/8387083
```

### Evaluation Form
Form: https://forms.gle/snULDTSjezepFQsJ6





