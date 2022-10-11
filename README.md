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

This repository contains genre annotations and metadata in [csv format](https://github.com/polimi-ispl/ITTV/meta.csv). 

We provide a balanced [training](https://github.com/polimi-ispl/ITTV/train_fold.csv) and
[validation](https://github.com/polimi-ispl/ITTV/val_fold.csv) split, 
as well as a disjoint [test set](https://github.com/polimi-ispl/ITTV/test_fold.csv) containing 525 installments from 
TV programs not included in the development set.
