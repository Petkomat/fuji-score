# fuji-score

Fuzzy Jaccard Index (FUJI) implementation and data

## Dependencies

The code implements many similarity scores. Some of them need `numpy` or `scipy`. For showing the progress, `tqdm` is be used.


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