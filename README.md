# ITTV - A Dataset of Italian Television for Automatic Genre Classification

ITTV is a publicly available dataset of Italian TV programs presented in

> Paolo Sani, Alessandro Ilic Mezza, and Augusto Sarti, "Automatic TV Genre Classification Using Visually-Aware Deep Audio Features," _unpublished_, 2022.

ITTV consists of 2,625 manually annotated YouTube videos, totaling over 675 hours. Each clip is assigned one of seven classes similarly to the 
RAI dataset described in [(Montagnuolo and Messina, 2007)](https://ieeexplore.ieee.org/document/4312865), i.e.,
* `Cartoons`
* `Commercials`
* `Football`
* `Music`
* `News`
* `Talk Shows`
* `Weather Forecast`

This repository contains genre annotations and metadata in [csv format](https://github.com/polimi-ispl/ITTV/ittv.csv). Please note that audio data is not provided.

We provide the annotations for a balanced **training** (`train`) and **validation** (`val`) split, 
as well as for a disjoint **test set** (`test`) containing 525 installments from 
TV programs not included in the development set.

![](https://github.com/polimi-ispl/ITTV/blob/main/images/duration_table.png)

![](https://github.com/polimi-ispl/ITTV/blob/main/images/duration_boxplot.png)

## Known Potential Issues

As YouTube is continuously updating, some videos may not be available in the future. Although we intend to keep ITTV updated as best as possible, please note that the durations reported in the table above may differ from those of the content available at any given time.

Some YouTube videos (especially from the `Football` class and, to a lesser extent, `Cartoons`) may only be available in some countries due to regional restrictions imposed by the content creator. All videos are known to be accessible from Italy (last accessed on Nov. 25th, 2022.)
