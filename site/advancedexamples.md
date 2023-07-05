# Advanced examples

## Reading a SeaBird CTD `.cnv` data file

[SeaBird](https://www.seabird.com/) CTD instruments are widely used in Oceanography. Reading SeaBird CTD `.cnv` data files is therefore a common task. The files are text based and one could write code from scratch to read and parse them, but then lots of people would be reinventing the wheel, imperfectly.

We will use the existing `ctd` open-source Python package, https://pyoceans.github.io/python-ctd/. We'll go through a notebook that demonstrates its use. I copied the notebook to [notebooks/ctd-quick_intro.ipynb](./notebooks/ctd-quick_intro.ipynb). It can be run by installing the `ctd` package in your conda environment. If at the terminal, you'd do this, where `my_conda_env` is the name of your conda environment:
```bash
conda activate my_conda_env
conda install -c conda-forge ctd
```

Here's a depth profile image created by the `ctd` example notebook:

![CTD profile](https://pyoceans.github.io/python-ctd/_images/quick_intro-output_23_0.png)


```{note}
It's not uncommon for different people or groups to create open-source packages with overlapping capabilities. There is at least one other package that reads SeaBird `cnv` files: the `seabird` package, https://seabird.readthedocs.io. Often in these cases, each package may have some features that the other one doesn't.
```

## microSWIFT data file

Prospects for reading [microSWIFT](https://apl.uw.edu/project/project.php?id=swift) data files in Python:

- https://github.com/jacobrdavis
- https://github.com/edwinrainville/microSWIFT-io
