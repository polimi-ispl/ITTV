# ITTV - A Dataset of Italian Television for Automatic Genre Classification

ITTV is a publicly available dataset of Italian TV programs.

ITTV was introduced in 

> Alessandro Ilic Mezza, Paolo Sani, and Augusto Sarti, "Automatic TV Genre Classification Based on Visually-Conditioned Deep Audio Features," 2023 31st European Signal Processing Conference (EUSIPCO), 2023.

__Update:__ The dataset is now available on [Zenodo](https://zenodo.org/record/8027327) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8027327.svg)](https://doi.org/10.5281/zenodo.8027327)


ITTV consists of 2,625 manually annotated YouTube videos, totaling over 673 hours. Each clip is assigned one of seven classes similarly to the 
RAI dataset described in [(Montagnuolo and Messina, 2009)](https://link.springer.com/article/10.1007/s11042-008-0222-3), i.e.,

* `Cartoons`
* `Commercials`
* `Football`
* `Music`
* `News`
* `Talk Shows`
* `Weather Forecast`

This repository contains genre annotations and metadata in [csv format](https://github.com/polimi-ispl/ITTV/blob/main/ittv.csv). Please note that audio data is not provided.

We provide the annotations for a balanced **training** (`train`) and **validation** (`val`) split, 
as well as for a disjoint **test set** (`test`) containing 525 installments from 
TV programs not included in the development set.

![](https://github.com/polimi-ispl/ITTV/blob/main/images/duration_table.png)

![](https://github.com/polimi-ispl/ITTV/blob/main/images/duration_boxplot.png)

## Known Potential Issues

As YouTube is continuously updating, some videos may not be available in the future. Although we intend to keep ITTV updated as best as possible, please note that the durations reported in the table above may differ from those of the content available at any given time.

Some YouTube videos (especially from the `Football` class and, to a lesser extent, `Cartoons`) may only be available in some countries due to regional restrictions imposed by the content creator. All videos are known to be accessible from Italy (last accessed on Nov. 25th, 2022.)
