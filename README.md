⭐ If you find this repository helpful, please consider giving it a ⭐ here on GitHub (click the star button in the top right corner) 
It's a quick way to show support for this openly available code. ⭐

![OReilly_logo_rgb.png](resources%2FOReilly_logo_rgb.png)

# Transformers - The definitive Guide
This is the corresponding code for the book Transformers - The definitive Guide

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with `CH` followed by the chapter number. For example, CH01.
The notebooks are then organized as follows: `ch01_attention_mechanism_variations.ipynb`, where `ch01` indicates the chapter
and `attention_mechanism_variations` what is done in the notebook. 

## Virtual Envrionment

The provided bash script `create_env.sh` automates the process of creating a Python virtual environment using either conda or pipenv, 
installing the required packages from a `requirements.txt file`. To use the script run `bash create_env.sh` in your 
terminal on Microsoft Windows (with WSL), Apple macOS, or Linux operating systems.

<span style="color:red">
NOTE: A virtual environment is not necessary for the notebooks in this repository, as they are designed to be run on a cloud service with GPU support. Therefore, the provided instructions for creating a virtual environment are more for reference and general guidance than a strict requirement. </span>

## Running the Notebooks

Every notebook contains buttons so that the notebook can be oppend and run on the chosen cloud service like this:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()   [![Gradient](https://assets.paperspace.io/img/gradient-badge.svg)]() 


Each notebook is connected with this Github repo, meaning by running a notebook, it will automatically clone the repo, so you can easily access all resources outside the notebook.
Like customs functions and classes as well as utility functions to automatically install the requirements per chapter: 


```
!git clone https://github.com/Nicolepcx/transformers-the-definitive-guide

current_path = %pwd
if '/transformers-the-definitive-guide' in current_path:
    new_path = current_path + '/utils'
else:
    new_path = current_path + '/transformers-the-definitive-guide/utils'
%cd $new_path
```
__NOTE:__ You need to run the notebooks with a GPU. 

## Project structure

```
├── LICENSE
├── README.md             <- The top-level README for developers using this project.
├── CH01                  <- Per chapter folder with Jupyter notebooks.
    ├── [name].ipynb      <- Jupyter notebooks with naming as mentioned above.
├── CH02                  <- Per chapter folder with Jupyter notebooks.
...                       <- Same structure for all chapters.
├── utils                 <- Custom classes and functions and utility functions.
├── resources             <- Some miscellaneous resources.

```
