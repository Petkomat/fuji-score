# fuji-score

Fuzzy Jaccard Index (FUJI) implementation and data

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
