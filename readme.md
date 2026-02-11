{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "d325c609",
   "metadata": {},
   "source": [
    "# Analyzing Prestige Bias in Film through Academy Awards, IMDb Ratings, and Box Office Performance\n",
    "\n",
    "All code was written by jkazma@umich.edu and jadb@umich.edu"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "93ff985d",
   "metadata": {},
   "source": [
    "## Motivation and Background\n",
    "\n",
    "We were interested in finding patterns, trends, or variations across film ratings and award data. Mainly, this includes films that generally receive high general praise, but no academy recognition, which can include B-movies or cult classics. We're also interested in high performing movies in terms of academy awards or box office performance that may not have scored highly on IMDb (outside of intentionally malicious reviews or \"review bombing\"). The two datasets we found had the separate data that could answer our questions if joined together, which formed the motivation for this exploration.\n",
    "\n",
    "There will be two datasets used for this project:\n",
    "- A list of IMDb's Most Popular 500-600 films every year from 1920-2025 (https://www.kaggle.com/datasets/raedaddala/top-500-600-movies-of-each-year-from-1960-to-2024/data)\n",
    "\n",
    "- A list of all Oscar nominees from 1927-2025 (https://www.kaggle.com/datasets/unanimad/the-oscar-award/data?select=full_data.csv)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "1fc4437c",
   "metadata": {},
   "source": [
    "## Installation and Imports\n",
    "\n",
    "These are the installations needed to run all notebook files.\n",
    "- `pandas`\n",
    "- `seaborn`\n",
    "- `plotly`\n",
    "- `nbformat`\n",
    "- `price_parser`\n",
    "- `CurrencyConverter`"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "bbc8f30a",
   "metadata": {},
   "source": [
    "## Virtual Environment\n",
    "We utilized virtual environments for the project. Creating the environments varies by operating system, as well as activating them, but these are the general commands used to recreate the environment and kernel for our notebooks. They would have to slightly modified depending on the OS.\n",
    "\n",
    "### Commands\n",
    "`!python -m venv films_env`\n",
    "\n",
    "`!source activate films_env/bin/activate`\n",
    "\n",
    "`!pip install pandas plotly nbformat price_parser CurrencyConverter`"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "48b82948-9910-4ba7-bca3-e7c30c147c16",
   "metadata": {},
   "source": [
    "### Activate virtual environment and install everything"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "117f1b95",
   "metadata": {},
   "source": [
    "## Codebook Narrative Order\n",
    "\n",
    "This project is split into mulitple notebooks, therefore the order in which the notebooks should be opened and read in is:\n",
    "1. dataset.ipynb\n",
    "    - Loading in and cleaning the data\n",
    "2. joining.ipynb\n",
    "    - Joining the IMDb and Oscar dataset together\n",
    "3. graphing.ipynb\n",
    "    - Visualizations for film budgets and profits\n",
    "4. language graph.ipynb\n",
    "    - Visualizations for film languages\n",
    "5. imdb graphing.ipynb\n",
    "    - Visualizations for user and critic scores"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "55d3918d-9c11-4813-98dc-14019f6da664",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
