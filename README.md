#  Cookiecutter for Data Analysis

![Badge](https://img.shields.io/badge/Project%20Status-Completed-blue)

This template is based on @chris1610 cookiecutter template. Full details and walk-through of his cookiecutter can be found over at [**Practical Business Python:  Building a Repeatable Data Analysis Process with Jupyter Notebooks.** ](http://pbpython.com/notebook-process.html)

I made some minor changes to the directory structure. I reformatted the notebooks in the analysis directory to personal preference for data anlaysis. 

## Directory structure

```bash
├── analysis
│   ├── 1-Data_Wrangling.ipynb  # Wrangling & cleaning notebook
│   └── 2-EDA.ipynb        # Final analysis notebook
├── data               # Categorized data files
│   ├── interim        # Working folder
│   ├── processed      # Cleaned and ready to use
│   └── raw            # Unmodified originals
└── reports            # Final reports
    └── visualizations  # Polished visualizations
```

## Installation

To use Cookiecutter, you must have it installed along with Python. Once you have Python installed, install Cookiecutter into the current user's folder, upgrade if available:

PIP:
```bash
$ pip3 install -U --user cookiecutter
```
CONDA:
```bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```

## Usage

Next, `cd` into where you want to save you project file, and run the template as follows:

```bash
$ cookiecutter https://github.com/c-smith7/cookiecutter_data_analysis        
```

In the terminal, you will then be prompted for your desired project name, directory/file name, and brief description of your project.  

```bash
project_name [project_name]: data_analysis_project
directory_name [data_journalism_project]: project_file
description [More background on the project]: Brief project description..
```

In the above example, `project_file` will be the name of the directory created. Also, the project name and description will automatically populate in the IPYNB notebooks.

The next time you want to use this cookiecutter, simply run:
```bash
$ cookiecutter cookiecutter_data_analysis
```

If you'd like to create your own cookiecutter and use this as a template, [cookiecutter docs](https://cookiecutter.readthedocs.io/en/1.7.2/first_steps.html) has a quick run through of how to make one. 

## Demo



[![Twitter Badge](https://img.shields.io/badge/@cvsmith__7-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/messages/compose?recipient_id=245625455)  
[![Gmail Badge](https://img.shields.io/badge/carlvsmith7-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:carlvsmith7@gmail.com)