# CHIC Shared Algorithms
> A curated list of shared algorithms for digital global health, maintained by CHIC's digital enablement squad.

## Data quality algorithms

| Algorithm | Maintainer | Description | License |
| :-------- | :--------: | :--------- | ------: |
| [Outlier detection](https://github.com/dimagi/outlier-detect) | Dimagi | Surprise scores at the frontline worker-question prompt level based on peer response. Built on work from [Benjamin Birnbaum's](https://bbirnbaum.com/) thesis work. | Apache 2.0 |
| [Time series outlier detection](https://github.com/medic/chic-ts-outlierdetect) | Medic | Time series anomaly detection as predicted by time series forecasting models for weekly/monthly data  | Apache 2.0 |

## Inclusion Requirements

_Work in progress_

Algorithms need to meet some specific criteria to be considered, including:

* **Free and open source** without any reliance on commcercial products. Note that instructions for how to use commercial products with the algorithm is fine, but no commcercial products should be required to use the algorithms.
* **Platform agnostic** with no reliance on a particular digital platform for collecting the data by frontline workers. Data schemas used on input data should be fully documented. Note that developing connectors to make it easy to pull data from a particular system is encouraged and should be released alongside the shared algorithm as long as the core algorithm functions independently.

