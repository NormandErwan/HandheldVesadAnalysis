# Handheld VESAD - Experiment Analysis

> Extension of a mobile screen by augmented reality: Handheld VESAD (Virtually Extended Screen-Aligned Display).

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/) Erwan Normand, 2018.

This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

This analysis is part of the Erwan Normand's [master thesis](https://github.com/NormandErwan/HandheldVesadThesis). See also the the [thesis presentation](https://github.com/NormandErwan/HandheldVesadPresentation) and the [experiment prototype](https://github.com/NormandErwan/HandheldVesadPrototype).

## Usage

Open [Handheld VESAD Analysis.ipynb](https://github.com/NormandErwan/HandheldVesadAnalysis/blob/master/Handheld%20VESAD%20Analysis.ipynb) in GitHub to see the analysis.

## Setup

1. Install an Anaconda environment such as [Miniconda](https://conda.io/miniconda.html). If you want to learn more about conda [read the docs](https://conda.io/docs/index.html).

2. [Start conda](https://conda.io/docs/user-guide/getting-started.html#starting-conda) and create a new environment with the following packages:

```
conda create --name handheld-vesad jupyter pandas matplotlib seaborn statsmodels ipywidgets
```

3. Activate the environment:
    - Windows: `activate handheld-vesad`
    - Linux and MacOS: `source activate handheld-vesad`

The following extensions where also used to develop, but are not required to run the notebook:

```
conda install -c conda-forge jupyter_contrib_nbextensions
jupyter contrib nbextension install --user

jupyter nbextension enable ruler/main
jupyter nbextension enable codefolding/main

pip install autopep8
jupyter nbextension enable code_prettify/autopep8
```

4. Run: `jupyter notebook "Handheld VESAD Analysis.ipynb"`

## Credits

We did the analysis with [Jupyter](https://jupyter.org/), [pandas](https://pandas.pydata.org/), [NumPy](http://www.numpy.org/), [Seaborn](https://seaborn.pydata.org/), [SciPy](https://scipy.org/) and [StatsModels](http://www.statsmodels.org/).
