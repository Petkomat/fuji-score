# FUJI: Fuzzy Jaccard Index: A robust comparison of ordered lists

This repository contains the code (and many feature rankings computed on over twenty real-life benchmark data sets) from the paper [Fuzzy Jaccard Index: A robust comparison of ordered lists](https://arxiv.org/abs/2008.02216).

This code is distributed under the [Creative Commons Attribution license (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), so the authors would greatly apprecieate if you acknowledge its use by citing the paper above (the corresponding bibtex is shown below).

```
@misc{fuji,
    title={Fuzzy Jaccard Index: A robust comparison of ordered lists},
    author={Matej Petkovi\{c} and Bla\v{z} \v{S}krlj and Dragi Kocev and Nikola Simidjievski},
    year={2020},
    eprint={2008.02216},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}
```

## Dependencies

The code implements many similarity scores. Some of them need [`numpy`](https://numpy.org/install/) or [`scipy`](https://www.scipy.org/install.html). For showing the progress, [`tqdm`](https://pypi.org/project/tqdm/) can be used.


## .fimp files

The structure of the files is the following:

<meta data (if available)>
<table>

<table> consists of four columns:

- index of the feature in the dataset
- name of the feature
- rank of the feature (>= 1)
- feature relevance score

The values are tab-separated.
