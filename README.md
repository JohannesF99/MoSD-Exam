# MoSD-Exam
The Repository for the "Management of Scientific Data" Exam containing Informations about the creation process of the slides as well as the data and tools used.

## Short directory overview

- _*data*_: contains all raw datasets
- _*src*_: contains all the Jupyter Notebooks used to process the data
- _*doc*_: contains alls the slides (not yet), documentation in plaintext and as rendered pdf
- _*slides*_: contains all the slides for the exam presentation

## Getting started

If you want to work with this project you first have to clone it to your computer.
Afterwards, create a virtual environment e.g. in the directory `venv` with `python -m venv ./venv/ `.
Now you can open any jupyter notebook and run the code. All needed dependencies are mentions in the notebook itself and the version numbers are mentioned in the documentation.
Remember that the steps in the `data_quality.ipynb` notebook requires the files that will be generated from the `data_processing.ipynb` notebook. So it's recommended to run them in this order.

## Questions

If anything is unclear, first ready through the documentation inside the _doc_ folder - it is as comprehensive as possible.
If still any questions arise please leave an issue or mail me at johannes.franke@uni-jena.de.