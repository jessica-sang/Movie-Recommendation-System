# Movie Recommendation System

A movie recommendation system project built with Jupyter, Python, Pandas, and scikit-learn.
This project allows users to type the name of a movie into an input box, and instantly get recommendations for other movies they might like. 

## Project Overview

The Movie Recommendation System uses user rating data to provide recommendations. Given a movie title, the system finds similar movies based on the preferences of users who liked the input movie. The recommendations are ranked according to a score that compares the preference of similar users to the general user base.

## Features

- Input a movie title to receive a list of similar movies.
- Recommendations are based on user ratings.
- Real-time updates as the user types a movie title.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/jessica-sang/Movie-Recommendation-System.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Movie-Recommendation-System
   ```

3. **Install the required packages manually:**
   Make sure you have Python installed. Then, install the necessary Python libraries:
   
   ```bash
   pip install pandas scikit-learn jupyter ipywidgets
   ```

4. **Run the Jupyter Notebook:**
   Ensure you have Jupyter installed. Start the notebook by running:

   ```bash
   jupyter notebook
   ```
   Open the .ipynb file and run the cells to explore the project.

## Usage

1. Start the Jupyter Notebook: Open the project in Jupyter Notebook.
2. Input a movie title: In the input field, type the name of a movie (e.g., "Toy Story").
3. Receive recommendations: The system will output a list of similar movies based on user ratings.

## Data

The project uses the following datasets:

- `movies.csv`: Contains movie information like movie ID, title, and genres.
- `ratings.csv`: Contains user ratings for different movies.

These datasets should be placed in the project directory before running the notebook.
