# All things data science/ analysis on the data from [Hitchwiki Maps](https://maps.hitchwiki.org/).

[This paper](https://arxiv.org/pdf/2506.21946) introduces the dataset of hitchhiking rides that we are dealing with here.

## Where can you find what?

`analysis` ... general analysis of the data and code for scientific papers about hitchhiking

`cleaning/` ... ideas how to tidy up the data

`import_data/` ... taking significant amounts of self-logged hitchhiking experiences and bringing it into the [hitchhiking data standard](https://github.com/Hitchwiki/hitchhiking-data-standard) to be imported there in bulk & fetching hitchhiking data from other sources and integrating it with the main dataset of hitchhiking rides.

`routing` ... experiments for route finding when hitchhiking

`visualization/` ... hitchhiking maps - using the data to build models that can predict hitchhiking waiting time and to draw maps


install pyvenv from requirements.txt is suffcient at the start

Get started to export hitchhiking data by running `getting_started.ipynb`.


## Developer setup

Every sub-directory might define its own specific environement. In general either a conda env from `environment.yml` or a pyvenv from `requirements.txt` should get you started.

For linting and formatting we suggest ruff using `ruff.toml`.
