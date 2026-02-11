# Analyzing Prestige Bias in Film through Academy Awards, IMDb Ratings, and Box Office Performance

All code was written by jkazma@umich.edu and jadb@umich.edu

## Motivation and Background

We were interested in finding patterns, trends, or variations across film ratings and award data. Mainly, this includes films that generally receive high general praise, but no academy recognition, which can include B-movies or cult classics. We're also interested in high performing movies in terms of academy awards or box office performance that may not have scored highly on IMDb (outside of intentionally malicious reviews or "review bombing"). The two datasets we found had the separate data that could answer our questions if joined together, which formed the motivation for this exploration.

There will be two datasets used for this project:
- A list of IMDb's Most Popular 500-600 films every year from 1920-2025 (https://www.kaggle.com/datasets/raedaddala/top-500-600-movies-of-each-year-from-1960-to-2024/data)

- A list of all Oscar nominees from 1927-2025 (https://www.kaggle.com/datasets/unanimad/the-oscar-award/data?select=full_data.csv)

## Installation and Imports

These are the installations needed to run all notebook files.
- `pandas`
- `plotly`
- `nbformat`
- `price_parser`
- `CurrencyConverter`

The `euroxref-hist.csv` is used for looking up historical data for film budgets in different currencies.

## Virtual Environment
We utilized virtual environments for the project. Creating the environments varies by operating system, as well as activating them, but these are the general commands used to recreate the environment and kernel for our notebooks. They would have to slightly modified depending on the OS.

### Commands
`!python -m venv films_env`

`!source activate films_env/bin/activate`

`!pip install pandas plotly nbformat price_parser CurrencyConverter`

## Codebook Narrative Order

This project is split into mulitple notebooks, therefore the order in which the notebooks should be opened and read in is:
1. dataset.ipynb
    - Loading in and cleaning the data
2. joining.ipynb
    - Joining the IMDb and Oscar dataset together
3. budget graph.ipynb
    - Visualizations for film budgets and profits
4. language graph.ipynb
    - Visualizations for film languages
5. imdb rating graph.ipynb
    - Visualizations for user and critic scores