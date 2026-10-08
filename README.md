# [OpenScienceLab Cookbook Template] Replace with Your Title

<img src="assets/ASF_logo.svg" alt="thumbnail" width="300"/>

[![nightly-build](https://github.com/ASFOpenSARlab/ASF_Cookbook_Template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ASFOpenSARlab/ASF_Cookbook_Template/actions/workflows/nightly-build.yaml)


This Cookbook Template was adapted from the Project Pythia [Cookbook Template](https://github.com/projectpythia/cookbook-template/blob/main/README.md). It has been updated to provide templates for ASF Cookbooks using the Pixi package manager.

See the [Project Pythia Cookbook Contributor's Guide](https://projectpythia.org/cookbook-guide/#:~:text=forking%20workflow.-,G.%20Deploying%20your%20Cookbook,%C2%B6,-Pythia%20Cookbooks%20are) for instructions on deploying your Cookbook to GitHub Pages.

This Cookbook covers ... (replace `...` with the main subject of your cookbook ... e.g., _working with radar data in Python_)

## Motivation

(Add a few sentences stating why this cookbook will be useful. What skills will you, "the chef", gain once you have reached the end of the cookbook?)

## Authors

First Author, Second Author, etc. _Acknowledge primary content authors here! You can include links to their GitHub profiles or other unique pages._

### Contributors

<a href="https://github.com/ASFOpenSARlab/ASF_Cookbook_Template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/ASFOpenSARlab/ASF_Cookbook_Template" />
</a>

## Structure

(State one or more sections that will comprise the notebook. E.g., _This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."_ Then, describe each section below.)

### Section 1 ( Replace with the title of this section, e.g. "Foundations" )

(Add content for this section, e.g., "The foundational content includes ... ")

### Section 2 ( Replace with the title of this section, e.g. "Example workflows" )

(Add content for this section, e.g., "Example workflows include ... ")

## Running the Notebooks

You can either run the notebooks in the Cookbook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables "one click"
execution in the cloud. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon (see screenshots [here](https://foundations.projectpythia.org/preamble/how-to-use/#running-pythia-foundations-examples)),
and a text box will appear. Type or paste the Pythia Binder link
(`https://binder.projectpythia.org`) and click "Launch".
After a few moments you should be presented with a
notebook that you can interact with. You’ll be able to execute code
and even change the example programs. At first the code cells
have no output, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in the Pythia Foundations chapter [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter).

Note, not all Cookbook chapters are executable. If you do not see
the rocket ship icon, such as on this page, you are not viewing an
executable book chapter.


### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "your_account/your_cookbook" with the GitHub org or user name and title of your cookbook repository)

1. Create a copy of this Cookbook template repository, by clicking the `Use this template button` and selecting the `Create a new repository` option on this [repository's GitHub page](). 

1. Clone the new repository:

   ```bash
    git clone https://github.com/your_account/your_cookbook.git
   ```

1. Move into the `your_cookbook` directory
   ```bash
   cd your_cookbook
   ```
1. Launch in Jupyter Lab with the included Pixi environment
    ```bash
    pix run lab
    ```
