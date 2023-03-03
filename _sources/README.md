<img src="thumbnail.png" alt="thumbnail" width="300"/>
 
# xbatcher for Machine Learning (Part 1) Cookbook

[![nightly-build](https://github.com/ProjectPythia/xbatcher-ML-1-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/xbatcher-ML-1-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.mypythia.org/badge_logo.svg)](http://binder.mypythia.org/v2/gh/ProjectPythia/xbatcher-ML-1-cookbook/main?labpath=notebooks)

This Project Pythia Cookbook covers a complete workflow for a convolutional neural network. Here, we emphasize how to create xarray-based training datasets with the `xbatcher` package.

## Motivation

By the end of this tutorial, you should be able to use core features of `xbatcher` to create valid training datasets for a convolutional neural network. You should also be able to recombine the CNN results into a valid xarray dataset for further viewing and analysis. Additionally, this tutorial shows some software designs that could be useful for organizing your ML experiments in the future.

## Authors

[Christopher Dupuis](@cmdupuis3), [Anirban Sinha](@anirban89), [Ryan Abernathey](@rabernat)

### Contributors

<a href="https://github.com/cmdupuis3/xbatcher-ML-1-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=cmdupuis3/xbatcher-ML-1-cookbook" />
</a>

## Structure

This Cookbook is mostly broken up by stages of the ML workflow, and is designed such that the training, testing, and prediction phases can be run somewhat separately. While every stage of this workflow is included explicitly, the training, testing, and prediction workflows are also included as separate functions that can be run instead of the inline sections. This enables you to minimize or remove sections you have already run, or already understand.

## Running the Notebooks

You can either run the notebook using [Binder](https://mybinder.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://mybinder.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/cookbook-example` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cookbook-example.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd cookbook-example
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
