# Citation counts data

The data comes from [Web of Science](https://clarivate.com/webofsciencegroup/solutions/web-of-science/) (WoS).

The data were collected as follows:
- Records of published papers were downloaded from the WoS database using the `scrapeWoS.ipynb` script.
- Citation counts were then collected using the [Web of Science Links Article Match Retrieval Service tool](https://github.com/Clarivate-SAR/wos-amr).
- The publication records and citation records were combined into a single dataset, `wos-citation-data.csv`.

