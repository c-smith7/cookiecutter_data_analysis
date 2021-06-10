#  Cookiecutter for Data Analysis


This template is based on @chris1610 cookiecutter template. Full details and walk-through of his cookiecutter can be found over at [**Practical Business Python:  Building a Repeatable Data Analysis Process with Jupyter Notebooks.** ](http://pbpython.com/notebook-process.html)

I made some minor changes to the directory structure. I reformatted the notebooks in the analysis directory to personal preference. And that's pretty much it. 

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

To use Cookiecutter, you must have it installed along with Python 3. Once you have Python installed, the recommended way to install Cookiecutter is as follows. Install to the current user's folder, upgrade if available:

```bash
$ pip3 install -U --user cookiecutter
```
```bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```

## Usage

cd into the folder you want to save your project in, run the template as follows:

```bash
$ cookiecutter https://github.com/c-smith7/cookiecutter_data_analysis
```
Then fill in the following project details when prompted:
```bash
$ project_name [project_name]: data_analysis_project
$ directory_name [data_analysis_project]: 
$ description [background info on the project]:
```

Now, in this example, the folder `data_analysis_project` will be created in the directory that you cd into. 

Now that you have cookiecutter and this data analysis cookiecutter template downloaded on your machine, the next time you want to use this cookiecutter simply run:
```bash
$ cookiecutter cookiecutter_data_analysis
```

If you'd like to create your own cookiecutter and use this as a template, [cookiecutter docs](https://cookiecutter.readthedocs.io/en/1.7.2/first_steps.html) has a quick run through of how to make one. 
