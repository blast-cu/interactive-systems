# Interactive Systems 

This repository contains the scripts and data for our arxiv preprint **[Studying the Effects of Collaboration in Interactive Theme Discovery Systems](https://arxiv.org/abs/2408.09030)**. If you build on these ideas, or if you use any portion of our code or data, please cite us!

```
@misc{chen2024studyingeffectscollaborationinteractive,
      title={Studying the Effects of Collaboration in Interactive Theme Discovery Systems}, 
      author={Alvin Po-Chun Chen and Dananjay Srinivas and Alexandra Barry and Maksim Seniw and Maria Leonor Pacheco},
      year={2024},
      eprint={2408.09030},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2408.09030}, 
}

```

## Installation
- Scripts must be run on python 3.12 or later
- Using a conda environment, run `pip install -r requirements.txt` to install dependencies

## Usage
The two notebooks contain the scripts necessary to calculate the results presented in the paper and also generate random samples (saved to `./dataset/generated_samples/`) for manual annotation, corresponding to the results found in Table 4 of the paper. The original data, including annotations used to produce the results for Table 4, can be found within their respective system folder in `./dataset/`. Detailed descriptions of each experimental result can also be found in the paper. 