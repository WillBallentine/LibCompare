# LibCompare

## ABOUT

This project sets out to compare and analyze the success of the top performing books as movies.

The movie is never as good as the book was right? That is the very question we are seeking to find out with this project.

**This project will attempt to answer the following questions:**

- Does publishing more books equate to more and better movies?
- Does the filming location matter for better ratings?
- Are older or newer published books more popular as movies?

## Methodology

This project seeks to employ the following feature set to analyze the data:

- Read in data from 2 .CSV files containing the data
- Use built-in Pandas and custom functions to clean and manipulate the data
- Use built-in Pandas functions to analyze the data
- Use Matplotlib to visualize the data
- Interpret the data in markdown cells after each section and at the end of the notebook

#### Data used

- 10000 Good Books DataSet[^1]
- Top 100 popular movies from 2003 to 2022 (iMDB) [^2]

## How To use this Repo

Start by cloning this repository to your local machine.

This repo utilizes several libraries that are included in the requirements.txt file.

To install these, navigate to the cloned repo folder on your machine in the terminal and run:

    pip install -r requirements.txt

Or if on Mac run:

    pip3 install -r requirements.txt

If this gives you any trouble I have also listed the libraries below for individual install:

- Pandas
- Numpy
- Matplotlib
- ipykernel

The main file in this project is called `compare.ipynb` and contains the analysis portion of this project.

#### Running the Program in Jupyter Notebook

1. Clone the repository.
2. Save the folder.
3. Open `jupyter notebook` from command line or start menu.
4. Navigate to the saved location of the repo.
5. Open `compare.ipynb`.
6. Click `Cell` tab and then `Run All`.

Citations:

[^1]:
    [10000 Good Books DataSet](https://www.kaggle.com/datasets/zygmunt/goodbooks-10k?select=books.csv)
    .

[^2]:
    [Top 100 popular movies from 2003 to 2022 (iMDB)](https://www.kaggle.com/datasets/georgescutelnicu/top-100-popular-movies-from-2003-to-2022-imdb)
    .

---
