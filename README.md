# What makes a hit song? - A Spotify Web-API Project

## Overview & How to use this Repo

This repository contains the code and data for a data science project aimed at predicting the popularity of songs using machine learning techniques. The project utilizes web scraping techniques along with the Spotify API to gather data on popular songs from 2020 to 2023 and to predict the potential popularity of recently released songs in 2024. The notebooks used to complete this notebook have been used in the order numbered as they appear in the repo. If you wish to replicate, or use this project for inspiration, please utilize the notebooks, and view them in the correct order.

## Data Collection

The project begins with web scraping of the Spotify platform using the Spotify API. The goal was to gather information on the 50 most popular songs from 2020 to 2023, including audio features, artist popularity, and genre data. Additionally, data was collected on recently released songs from the 'New Music Friday' playlist on April 12th, 2024.

## Data Exploration, Analysis and Modeling
Exploratory data analysis (EDA) was conducted to understand the distribution of various features and identify any trends over the four years. Correlation analysis was performed to explore relationships between different features and song popularity. Three types of linear regression models, as well as ensemble techniques such as XGBoost, SVR, and Random Forest Regressor, were trained using the collected data. The models were trained to predict the popularity of songs based on their audio features and other relevant data.

## Prediction of Recently Released Songs

The trained models were used to predict the potential popularity of songs extracted from Spotify's ['New Music Friday Playlist'](https://open.spotify.com/playlist/37i9dQZF1DX4JAvHpjipBk?si=5917a22db567447f) on April 12th, 2024, based on their audio features. This playlist was chosen for extraction, as well as the rest of our data, due to Spotify limitations of their API. The 'New Music Friday Playlist' is Spotify's most followed and popular new music playlist on their platform. The predictions provide insights into the potential success of these songs on Spotify.

## Results and Conclusion

The results of the model predictions, along with model evaluation metrics, are presented across notebooks 2 & 3. The conclusions drawn from the analysis and predictions are discussed in detail in to-be added presentation files.

## Dependencies

Ensure you have the following dependencies installed to run the code:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- XGBoost

## Usage

To reproduce the analysis and predictions, follow these steps:
*Please be weary, as this project was done by extracting data from a live WebAPI, [you may need to get your own developer key](https://developer.spotify.com/documentation/web-api)*

1. Clone this repository to your local machine.
2. Navigate to the `notebooks/` directory.
3. Open the Jupyter notebooks and execute the code cells sequentially.

## Contributors

- [Youssef Agour](https://github.com/Y-OUSSE-F)
- Yodahe Samson (to be linked)
- Adel Belova (to be linked)
- Ngoc Minh Thu Mai (to be linked)

## License

This project is licensed under the [MIT License](LICENSE).

