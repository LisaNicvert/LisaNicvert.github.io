---
title: "standardizeSnapshot"
collection: tools
permalink: /tools/standardizeSnapshot
excerpt: 'R package to clean camera trap data.'
toolurl: 'https://snapshotsafari.github.io/standard-merge/'
sourcecode: 'https://github.com/SnapshotSafari/standard-merge'
---

{standardizeSnapshot} is a R package to standardize camera trap data. It was
created as part of the [Snapshot Safari](https://snapshotsafari.wordpress.com/) project during my PhD (2023-2024).

This package allows to (1) standardize column names and format and (2) 
clean data stored in columns. These operations are possible with the two main
functions:

- `standardize_snapshot_df` to standardize one file
- `standardize_snapshot_list` to standardize multiple file


<img src="/images/standardizeSnapshot-workflow.png" alt="{standardizeSnapshot} workflow" width="100%" class = "align-center">

Due to the large amount of data processed within the project, and to the fact that
different tools were historically used for annotation, there was a need for an
automated tool to process data.