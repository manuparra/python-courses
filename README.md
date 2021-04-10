# Compilation of selected Python courses for different levels and areas.

This repository contains several courses I have taught, differentiated by level and/or area. 

#### Requirements
* Have Python 3 (3.5) or newer installed. You can check the version by typing `python3 --version` in your command line. You can download the latest Python version from [here](https://www.python.org/downloads/).
* Have [Jupyter Notebook installed](http://jupyter.readthedocs.io/en/latest/install.html):
 * If not, use https://mybinder.org/ to create a full Jupyter NoteBook instance in the Cloud and add the URL of this repository to start.
 * You also can install Jupyter Notebooks within Docker container with many flavours (general, science, data-science, ...)

If you can not access Python and/or Jupyter Notebook on your machine, you can still follow the web based materials. However, you should be able to use Jupyter Notebook in order to complete the exercises.


## Beginner
1. Strings [[notebook]](./python-beginner/notebooks/strings.ipynb) [[exercise]](./python-beginner/exercises/strings_exercise.ipynb)
1. Numbers [[notebook]](./python-beginner/notebooks/numbers.ipynb) [[exercise]](./python-beginner/exercises/numbers_exercise.ipynb)
1. Conditionals [[notebook]](./python-beginner/notebooks/conditionals.ipynb) [[exercise]](./python-beginner/exercises/conditionals_exercise.ipynb)
1. Lists [[notebook]](./python-beginner/notebooks/lists.ipynb) [[exercise]](./python-beginner/exercises/lists_exercise.ipynb)
1. Dictionaries [[notebook]](./python-beginner/notebooks/dictionaries.ipynb) [[exercise]](./python-beginner/exercises/dictionaries_exercise.ipynb)
1. For loops [[notebook]](./python-beginner/notebooks/for_loops.ipynb) [[exercise]](./python-beginner/exercises/for_loops_exercise.ipynb)
1. Functions [[notebook]](./python-beginner/notebooks/functions.ipynb) [[exercise]](./python-beginner/exercises/functions_exercise.ipynb)
1. Testing with pytest - part 1 [[notebook]](./python-beginner/notebooks/testing1.ipynb) [[exercise]](./python-beginner/exercises/testing1_exercise.ipynb)
1. Recap exercise 1 [[exercise]](./python-beginner/exercises/recap1_exercise.ipynb)
1. File I\O [[notebook]](./python-beginner/notebooks/file_io.ipynb) [[exercise]](./python-beginner/exercises/file_io_exercise.ipynb)
1. Classes [[notebook]](./python-beginner/notebooks/classes.ipynb) [[exercise]](./python-beginner/exercises/classes_exercise.ipynb)
1. Exceptions [[notebook]](./python-beginner/notebooks/exceptions.ipynb) [[exercise]](./python-beginner/exercises/exceptions_exercise.ipynb)
1. Modules and packages [[notebook]](./python-beginner/notebooks/modules_and_packages.ipynb)
1. Debugging [[notebook]](./python-beginner/notebooks/debugging.ipynb) [[exercise]](./python-beginner/exercises/debugging_exercise.ipynb)
1. Goodies of the Standard Library - part 1 [[notebook]](./python-beginner/notebooks/std_lib.ipynb) [[exercise]](./python-beginner/exercises/std_lib1_exercise.ipynb)
1. Testing with pytest - part 2 [[notebook]](./python-beginner/notebooks/testing2.ipynb) [[exercise]](./python-beginner/exercises/testing2_exercise.ipynb)
1. Virtual environment [[notebook]](./python-beginner/notebooks/venv.ipynb)
1. Project structure [[notebook]](./python-beginner/notebooks/project_structure.ipynb)
1. Recap exercise 2 [[exercise]](./python-beginner/exercises/recap2_exercise.ipynb)


## Intermediate

#### Idiomatic Python
Python is a powerful language which contains many features not presented in most other programming languages. Idiomatic section will cover some of these Pythonic features in detail. These materials are especially useful for people with background in other programming languages.

1. [Idiomatic loops](./python-intermediate/html/idiomatic_loops.html) [[notebook]](./python-intermediate/notebooks/idiomatic_loops.ipynb)
1. [Idiomatic dictionaries](./python-intermediate/html/idiomatic_dicts.html) [[notebook]](./python-intermediate/notebooks/idiomatic_dicts.ipynb)
1. [Idiomatic Python - miscellaneous part 1](./python-intermediate/html/idiomatic_misc1.html) [[notebook]](./python-intermediate/notebooks/idiomatic_misc1.ipynb)
1. [Idiomatic Python - miscellaneous part 2](./python-intermediate/html/idiomatic_misc2.html) [[notebook]](./python-intermediate/notebooks/idiomatic_misc2.ipynb)
1. Idiomatic Python exercise [[exercise]](./python-intermediate/exercises/idiomatic_python_exercise.ipynb)

## Engineer

This section is focused on a bit more complex Python elements with array management/manipulation with NumPy and graphical libraries such as MathPlotLib.

See data folder required for many exercices in [[datafolder]](./python-engineering/data/).

1. Introduction to numpy [[notebook]](./python-engineering/00_Introduction_to_numpy.ipynb) 
1. Arrays management [[notebook]](./python-engineering/01_Arrays_management.ipynb) 
1. Plots with matplotlib [[notebook]](./python-engineering/00_Plots_with_matplotlib.ipynb) 
1. Controlling plots elements and customization [[notebook]](./python-engineering/01_Controlling_plot_elements.ipynb) 
1. Arrays n-dimensional [[notebook]](./python-engineering/02_Arrays_N_dimensional.ipynb) 
1. Indexing and slicing [[notebook]](./python-engineering/03_Indexing_y_slicing_c.ipynb) 
1. Arrays of objects [[notebook]](./python-engineering/04_Objects_Arrays.ipynb) 
1. Mixed arrays [[notebook]](./python-engineering/05_Mixed_Arrays.ipynb) 
1. Arrays manipulation [[notebook]](./python-engineering/06_Arrays_manipulation.ipynb) 

## Data Science

This section contains a complete data science course, covering aspects of working with data, manipulation, ETL, Data Mining and Machine Learning with Python.

See data folder required for many exercices in [[datafolder]](./python-datascience/data/).

1. Introduction to Pandas [[notebook]](./python-datascience/03.00-Introduction-to-Pandas.ipynb) 
1. Introduction to Pandas Objects [[notebook]](./python-datascience/03.01-Introducing-Pandas-Objects.ipynb) 
1. Data indexing and selection [[notebook]](./python-datascience/03.02-Data-Indexing-and-Selection.ipynb) 
1. Operations in Pandas  [[notebook]](./python-datascience/03.03-Operations-in-Pandas.ipynb) 
1. Missing values  [[notebook]](./python-datascience/03.04-Missing-Values.ipynb) 
1. Hierarchical  [[notebook]](./python-datascience/03.05-Hierarchical-Indexing.ipynb) 
1. Concatenating and appending data  [[notebook]](./python-datascience/03.06-Concat-And-Append.ipynb) 
1. Joining and merging data  [[notebook]](./python-datascience/03.07-Merge-and-Join.ipynb) 
1. Agregation and grouping data  [[notebook]](./python-datascience/03.08-Aggregation-and-Grouping.ipynb) 
1. Pivot tables  [[notebook]](./python-datascience/03.09-Pivot-Tables.ipynb) 
1. Working with strings  [[notebook]](./python-datascience/03.10-Working-With-Strings.ipynb) 
1. Working with time series  [[notebook]](./python-datascience/03.11-Working-with-Time-Series.ipynb) 
1. Performance evaluation and queries  [[notebook]](./python-datascience/03.12-Performance-Eval-and-Query.ipynb) 
1. Introducing SciKitLearn  [[notebook]](./python-datascience/05.02-Introducing-Scikit-Learn.ipynb) 
1. Hyper-parameters and modelo validation  [[notebook]](./python-datascience/05.03-Hyperparameters-and-Model-Validation.ipynb) 
1. Feature engineering  [[notebook]](./python-datascience/05.04-Feature-Engineering.ipynb) 
1. Linear regression  [[notebook]](./python-datascience/05.06-Linear-Regression.ipynb) 
1. Support vector machine (SVM)  [[notebook]](./python-datascience/05.07-Support-Vector-Machines.ipynb) 
1. Random forest  [[notebook]](./python-datascience/05.08-Random-Forests.ipynb) 
1. Principal component analysis  [[notebook]](./python-datascience/05.09-Principal-Component-Analysis.ipynb) 
1. K-Means  [[notebook]](./python-datascience/05.11-K-Means.ipynb) 
1. Images features  [[notebook]](./python-datascience/05.14-Image-Features.ipynb) 

