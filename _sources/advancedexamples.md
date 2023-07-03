# Advanced examples

## Reading a Seabird CTD `.cnv` data file

Seabird CTD instruments are widely used in Oceanography. Reading Seabird CTD `.cnv` data files is therefore a common task. The files are text based and one could write code from scratch to read and parse them, but then lots of people would be reinventing the wheel, imperfectly.

Someone has created an open-source Python package to do this: `seabird`, https://seabird.readthedocs.io. We'll go through a notebook 

- I've installed the `seabird` package into my dinosip conda env
- I copied the notebook to [notebooks/seabird-BasicsReadingData.ipynb](./notebooks/seabird-BasicsReadingData.ipynb)

## microSWIFT data file?

- https://github.com/jacobrdavis
- https://github.com/edwinrainville/microSWIFT-io
