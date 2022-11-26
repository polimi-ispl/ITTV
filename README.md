# ITTV - A Dataset of Italian Television for Automatic Genre Classification

ITTV is a publicly available dataset of Italian TV programs presented in

> Paolo Sani, Alessandro Ilic Mezza, and Augusto Sarti, "Automatic TV Genre Classification Using Visually-Aware Deep Audio Features," _unpublished_, 2022.

ITTV consists of 2,625 manually annotated YouTube videos, totalling over 675 hours. Each clip is assigned one of seven classes similarly to the 
RAI dataset described in [(Montagnuolo and Messina, 2007)](https://ieeexplore.ieee.org/document/4312865), i.e.,
* `Cartoons`
* `Commercials`
* `Football`
* `Music`
* `News`
* `Talk Shows`
* `Weather Forecast`

This repository (will) contain genre annotations and metadata in [csv format](https://github.com/polimi-ispl/ITTV/meta.csv). Please note that audio data is not provided.

We provide the annotations for a balanced **training** (`train`) and **validation** (`val`) split, 
as well as for a disjoint **test set** (`test`) containing 525 installments from 
TV programs not included in the development set.

![](https://github.com/polimi-ispl/ITTV/blob/main/images/duration_table.png)

![](https://github.com/polimi-ispl/ITTV/blob/main/images/duration_boxplot.png)

## Known Potential Issues

Some YouTube videos and channels (especially from the `Football` class and, to a lesser extent, `Cartoons`) may not be available in every country due to regional restrictions imposed by the content creator. All videos are known to be accessible from Italy (last accessed Nov. 26th, 2022.)
