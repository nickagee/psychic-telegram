# psychic-telegram (aka Recomendataions with 'IBM')

Recommendations with IBM

## Table of Contents

1. [Project Overview](#overview)
2. [Setup/Testing Instructions](#setup)
3. [File/Folder Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Overview <a name="overview"></a>

In this project I was given the task of analyzing the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like.

## Setup/Testing Instructions <a name="setup"></a>

Git clone this repo to your local environment and then run the following commands in a new terminal.

```bash
$ cd pyschic-telegram
$ conda env create -f environment.yml
$ conda activate psy-tele
$ jupyter lab
```

Now open a new web browser and navigate to [http://localhost:8888/lab](http://localhost:8888/lab)

## File/Folder Descriptions <a name="files"></a>

Within the `main/` folder is where the mechanics of the application are found.

**Recommendations_with_IBM.ipynb** is the jupyter notebook that contains all the code for setting up and running the recommendation models and analytics.

**data/** is the folder that contains the datasets utilized in this project.

## Licensing, Authors, Acknowledgements <a name="licensing"></a>

The data that was utilized in this project was obtained from Udacity Data Science Nano Degree.
