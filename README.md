# Movie Recommendation System Using Machine Learning

This project is a system that provides movie recommendations using a machine learning model. After selecting a specific movie, the system suggests similar movies and displays their posters.

## Contents
- [Installation](#installation)
- [Usage](#usage)
- [About the Project](#about-the-project)
- [License](#license)

## Installation

Follow these steps to run the project on your local machine.

### Requirements
- Python 3.6+
- Streamlit
- Requests
- Pickle

### Steps
1. Clone this repository:
    ```bash
    git clone https://github.com/username/movie-recommendation-system.git
    ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Download and place the `movie_list.pkl` and `similarity.pkl` files from the `artifacts` folder into the project directory.

4. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

## Usage

1. After starting the application, you will see the header "Movie Recommendation System Using Machine Learning" in your browser.
2. You can type or select a movie name in the `Type or Select Movie` box.
3. Click the `Find Recommendation` button to display similar movies and their posters on the screen.

## About the Project

This project uses The Movie Database (TMDb) API to fetch movie information and posters. The machine learning model used calculates similarities between movies using specific algorithms.

