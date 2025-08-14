# Advanced examples

## Reading and visualizing cast data from SeaBird CTD `.cnv` data files

[SeaBird](https://www.seabird.com/) CTD instruments are widely used in Oceanography. SeaBird CTD software also integrate data from other sensors. Reading SeaBird CTD `.cnv` data files is therefore a common task. The files are text based and one could write code from scratch to read and parse them, but then lots of people would be reinventing the wheel, imperfectly. 

In the [read-aplsurp-ctd-casts-with-ctd-package.ipynb](notebooks/read-aplsurp-ctd-casts-with-ctd-package.ipynb) notebook, we use the [`ctd` open-source package](https://pyoceans.github.io/python-ctd/) to read SeaBird CTD files and the [`folium` open-source package](https://python-visualization.github.io/folium/) to create interactive maps of cast locations using information read from the cast files. 

To see more of the capabilities of the `ctd` package, check out the [demonstration notebook found on the ctd website](https://pyoceans.github.io/python-ctd/quick_intro-output.html). 


<!-- It can be run by installing the `ctd` package in your conda environment. If at the terminal, you'd do this, where `my_conda_env` is the name of your conda environment:
```bash
conda activate my_conda_env
conda install -c conda-forge ctd
``` -->


```{note}
It's not uncommon for different people or groups to create open-source packages with overlapping capabilities. There is at least one other package that reads SeaBird `cnv` files: the `seabird` package, https://seabird.readthedocs.io. Often in these cases, each package may have some features that the other one doesn't.
```
