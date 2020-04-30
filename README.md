# Exploring European Soccer Data from 2008 to 2016

This project was developed for the Udacity Data Analyst Nanodegree in order to develop the skills to investigate a database and communicate findings with Python 3.

# Table of Contents
1. [Data](#data)
2. [Research Questions](#questions)
3. [Prerequisites to contribute](#requisites)
4. [How to visualize the study](#visualize)
5. [License](#license)


<a name="data"></a>
## Data

The used database is the [European Soccer Database](https://www.kaggle.com/hugomathien/soccer/data) from Kaggle.
It includes the following data:
* +25,000 matches
* +10,000 players
* 11 European Countries with their lead championship
* Seasons 2008 to 2016
* Players and Teams' attributes* sourced from EA Sports' FIFA video game series, including the weekly updates
* Team line up with squad formation (X, Y coordinates)
* Betting odds from up to 10 providers
* Detailed match events (goal types, possession, corner, cross, fouls, cards etc...) for +10,000 matches

However, the scope of this project was only to analyze the data referring to the match statistics. Therefore, it does not have any investigation about the players attributes, team formations and betting odds.

<a name="questions"></a>
## Research Questions
* Which are the best teams at home-field games?
* Which are the best teams at away-field games?
* Which league had the biggest fouls per match average?
* Which teams had the biggest ball possession average?
* Which teams had most corners per match?
* Which are the teams with most crosses per match?
* Which are the best teams in nacional leagues by season?
* Are there any strong correlations between the result of the match and the ball possession, team fouls, team crosses or team corners?
* Are there any matches with exceptional game values (goals, cards, fouls, crosses, etc.)?

<a name="requisites"></a>
## Prerequisites to contribute
First, you need to download the .csv files extracted from the database at this Google Drive [link](https://drive.google.com/drive/folders/1mzhIeTG8M9hvxIgt4KdJI4TJXI9ac8JQ) and move them to the project directory on your computer. From there you can choose one of the following methods:

### Method 1
If you want to contribute, this project requires **Python 3** and its following libraries installed:

* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [IPython](https://ipython.org/install.html)

Besides, you also need to install a software to use [Jupyter Notebook](https://jupyter.org/).  
I recommend downloading [Anaconda](https://www.anaconda.com/) (Python distribution), which already has all the necessary modules and Jupyter Notebook installed.

### Method 2
You can also decide to use [Google Colab](https://colab.research.google.com/), in this case, all you have to do is open the notebook (`.ipynb` file) on Google Colab with your account.

<a name="visualize"></a>
## How to visualize the study
You can just download the files and open the `.html` file on your browser.

<a name="license"></a>
## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


