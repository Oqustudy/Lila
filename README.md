# Lila

A unified benchmark for math reasoning.

The `original` directory contains the data used in the Lila paper. 
We include it for reproducibility.
The `lila` directory contains the data for the official Lila benchmark, 
which has undergone quality improvements since the paper.

You will need [git-lfs](https://git-lfs.github.com/) to clone these, 
or you can download them manually (e.g., `lila.zip > download`).

Contact matthewf@allenai.org with questions.

```
├── README.md
├── data.zip
│   ├── all
│   │   └── *.json
│   └── multi
│       ├── iid
│       │   ├── dev.json
│       │   ├── test.json
│       │   └── train.json
│       └── ood
│           ├── dev.json
│           ├── test.json
│           └── train.json
└── original.zip
    ├── all
    │   └── *.json
    ├── multi
    │   └── ...
    ├── single
    │   └── ...
    ├── cross
    │   └── ...
    └── robust
        ├── original.json
        └── perturbed.json
```

Cite this dataset and the source datasets (see `sources.bib`). 

```bib
@INPROCEEDINGS{Hosseini14learningto,
  author = {
    Swaroop Mishra 
      and Matthew Finlayson 
      and Pan Lu 
      and Leonard Tang 
      and Sean Welleck 
      and Chitta Baral 
      and Tanmay Rajpurohit 
      and Oyvind Tafjord 
      and Ashish Sabharwal 
      and Peter Clark 
      and Ashwin Kalyan},
  title = {Lila: A Unified Benchmark for Mathematical Reasoning},
  booktitle = {Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  year = {2022}
}
```
