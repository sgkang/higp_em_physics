**[summary](#summary) | [prerequisites](#prerequisites) | [setup](#setup) | [resources](#resources) | [license](#license)**

[![License](https://img.shields.io/github/license/sgkang/higp_em_physics.svg)](https://github.com/sgkang/higp_em_physics/blob/main/LICENSE)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)
![example workflow](https://github.com/sgkang/higp_em_physics/actions/workflows/python-package-conda.yml/badge.svg)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Follow%20%40sgkang09)](https://twitter.com/sgkang09)

# The Physics of Geophysical Prospecting Methods: Resistivity and Controlled Source vs Natural EM methods

**Instructor**
- [Seogi Kang](https://github.com/sgkang) 


## Assumptions about the course

This course is for 3rd/4th year students in geoscience.
Basic background of physics are not preferred, but not required. 
In this repository, there are Apps, which provide hands-on examples that students can explore the physics of EM geophysicsal proppecting methods. The apps developed by Jupyter Notebooks, Python and SimPEG are used, but strong software background is not required.

## Learning goals

- Understand electrical resistivity and its linkage to geologic units.
- Understand physical principles of Electromagnetic (EM) methods
    - Charge build-up (or current channeling, galvanic currents)
    - EM induction
- Identify difference between controlled-source EM and magnetotellurics (MT)
- Identify all EM methods are governed by the same physical principles
- Understand survey setup of EM methods and data
- Understand sensitivity of EM methods to conductors & resistors

### Step 1: Download the EM physics tutorial

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
cd higp_em_physics
```

### Step 4: Launching the notebooks

Once you have activated the conda environment, you can launch the notebooks
```
jupyter lab
```
Jupyter will then launch in your web-browser.

## Resources for open-source geophysical software, `SimPEG`

- [Docs](http://docs.simpeg.xyz/)
- [Discourse](http://simpeg.discourse.group/)
- [Slack](http://slack.simpeg.xyz/)

## License

All code and text in this repository is free software: you can redistribute it and/or
modify it under the terms of the MIT License.
A copy of this license is provided in [LICENSE](LICENSE).

