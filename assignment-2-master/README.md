# Assignment #2 (Required)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Fall-2019/assignment-2/master)

### Due Date: 9/19 by the start of class

**This homework assignment is required.**

## Recommended Readings

- [Seaborn example gallery](https://seaborn.pydata.org/examples/index.html)
- [Altair user guide](https://altair-viz.github.io/)

## Reference materials

- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [altair](https://altair-viz.github.io/)

## Part 1: Installing the necessary dependencies

You will need to update the "musa-620" conda environment created as part of
last week's assignment. The necessary dependencies are listed in the
[environment.yml](environment.yml) file in this repository.

You can update the conda environment on your local environment following
[the guide](https://github.com/MUSA-620-Fall-2019/course-materials/blob/master/general-guides/updating-your-environment.md) on the course materials repository.

And then you are ready to launch a Jupyter notebook ([a guide](https://github.com/MUSA-620-Fall-2019/course-materials/blob/master/general-guides/launching-jupyter-notebook.md) is available on the
course materials repository).

Be sure to activate the "musa-620" environment before launching the notebook!

## Part 2: Exploratory Data Visualization

In this part, you'll use matplotlib, seaborn, and altair to explore a
dataset of your choosing and generate some charts in a Jupyter notebook.

### Part 2.1: Select a dataset

For this assignment, you can choose your own dataset to explore. I recommend selecting a dataset from [OpenDataPhilly](https://www.opendataphilly.org/). You are welcome to to use a dataset from elsewhere, **but please email me and let me know what you want to analyze.**

Datasets with timestamped entries will be particularly good for analysis, but there are many
interesting datasets to consider. They include:

- [311 Requests](https://www.opendataphilly.org/dataset/311-service-and-information-requests)
- [Voter turnout](https://www.opendataphilly.org/dataset/voter-turnout)
- [Complaints against police](https://www.opendataphilly.org/dataset/police-complaints)
- [Parking violations](https://www.opendataphilly.org/dataset/parking-violations)
- [Shooting victims](https://www.opendataphilly.org/dataset/shooting-victims)
- [L+I Violations](https://www.opendataphilly.org/dataset/licenses-and-inspections-violations)

and many more...

For OpenDataPhilly datasets, data files can be downloaded in the form of CSV files.

### Part 2.2: Explore and visualize the data

From within a Jupyter notebook, you should explore the
datasets and generate charts visualizing different aspects of the data.

**Requirements:**

- **1 Matplotlib chart** (of any type)
  - You should consider what aspect of the dataset might be best plotted using matplotlib.
  - Include your reasoning for using matplotlib to visualize this specific aspect of the data.
  - You will be graded on the aesthetics of the plot, namely, color choices and clarity.
- **1 seaborn chart** (of any type)
  - Please include the motivation behind your choice for the type of seaborn plot used and why.
- **3 interactive altair plots**
  - The following techniques should be used at least once:
    - A transformation (mean, count, binning, etc)
    - Brush selection
    - **Extra credit**: 2-chart dashboard, where filtering of one chart cross-filters the other chart (via `transform_filter()`)
- A short discussion (a few sentences) of the main conclusion of each chart
  (in a markdown cell below each chart). It does not need to be interesting or insightful,
  but it is good practice to always note the main conclusions so the notebook make sense after time passes.

## Grading Guidelines

See the [grading rubric](./rubric.md) for more details.

**Important:** Your notebooks should be a polished finished product. For example:

- please remove any extra or unneccesary code.
- please try to use markdown cells with section headers to mark different sections of the analysis.

## Submission

We'll be using GitHub for assignment submission again. You can set up your own private repository on GitHub for this assignment using the following link:

https://classroom.github.com/a/71lsWhMo

The assignment should be added to this GitHub repository before the deadline. You can add files to
the repository through the browser (github.com) interface or using the command line locally on your machine.
For more help, see:

- [Adding a file to a repository via Github](https://help.github.com/en/articles/adding-a-file-to-a-repository)
- [Adding a file to a repository using the command line](https://help.github.com/en/articles/adding-a-file-to-a-repository-using-the-command-line)

**Submission Steps:**

1. Add your `.ipynb` notebook file to your own private repository before the submission deadline.
1. Either add the dataset used in the analysis to the repository, or document the original source of the data so it can be downloaded during grading.
1. Please be sure that your name is listed at the top of the notebook file you submit.

**Note:** File sizes are limited to 25 MB when adding files to a repository via GitHub in a browser. If your
dataset is larger than this, you can try compressing it into a ".zip" to make the file smaller, and then
add it to the repository on GitHub. If you run into problems, please email me (nhand@design.upenn.edu).
