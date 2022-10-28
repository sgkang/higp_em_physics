**[summary](#summary) | [prerequisites](#prerequisites) | [setup](#setup) | [resources](#resources) | [license](#license)**

[![License](https://img.shields.io/github/license/sgkang/higp_em_physics.svg)](https://github.com/sgkang/higp_em_physics/blob/main/LICENSE)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)
![example workflow](https://github.com/sgkang/higp_em_physics/actions/workflows/python-package-conda.yml/badge.svg)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Follow%20%40sgkang09)](https://twitter.com/sgkang09)

# 

**Instructor**
- [Seogi Kang](https://github.com/sgkang) 


## Summary

XXX

## Prerequisites

**Software**

* Some knowledge of Python is assumed.
* All coding will be done in Jupyter notebooks. I'll explain how they work
  briefly but it will help if you've used them before.
* We will ll use [numpy](https://numpy.org/), [matplotlib](https://matplotlib.org/), and
  [ipywidgets](https://ipywidgets.readthedocs.io/)
  You don't need to be an expert in these tools but some familiarity will help.

### Step 1: Download the MT inversion tutorial

To clone this repository, open up a terminal and navigate to where you want this repository stored on your computer.

Then run
```
git clone https://github.com/sgkang/higp_em_physics.git
```
to clone the repository, and `cd` into the `higp_em_physics` directory
```
cd higp_em_physics
```

### Step 2: Create `em` conda environment

From inside of the `higp_em_physics` repository, create the `em` conda environment
```
conda env create -f environment.yml
```
and activate the environment
```
conda activate em
```
```
cd ..
```

### Step 3: Install  `SimPEG`

```
git clone https://github.com/simpeg/simpeg.git
```
```
cd simpeg
```
```
git checkout -f tiled_fdem_nsem
```
```
pip install -e .
```
```
cd ..
```
```
cd higp-em-2022
```

### Step 4: Launching the notebooks

Once you have activated the conda environment, you can launch the notebooks
```
jupyter lab
```
Jupyter will then launch in your web-browser.


## Resources

**Resources on MT processing and inversions**
- [MTH5](https://github.com/kujaku11/mth5)
- [MTpy](https://github.com/MTgeophysics/mtpy)
- [aurora](https://github.com/simpeg/aurora)
- [SimPEG](https://www.simepg.xyz)

**Resources on SimPEG**
- [Docs](http://docs.simpeg.xyz/)
- [Discourse](http://simpeg.discourse.group/)
- [Slack](http://slack.simpeg.xyz/)


## License

All code and text in this repository is free software: you can redistribute it and/or
modify it under the terms of the MIT License.
A copy of this license is provided in [LICENSE](LICENSE).

