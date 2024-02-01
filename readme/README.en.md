# ForexTradingApp

The application presents the latest data, charts, and predictions regarding popular or user-selected companies or currencies.
The data is presented on an html page created using *Bootstrap* and is fetched from *Yfinance*. The charts are created using the *Matplotlib* library.
The page also offers a separate section for predictions based on a trained LSTM model.

## Data for the most popular tickers
![Screenshot 2024-02-01 164204](https://github.com/Nemezjusz/ForexPredictionDashboard/assets/50834734/666c275c-3a3e-4d71-8697-a31e09f40614)

## Charts for the selected company or currency
![Screenshot 2024-02-01 164141](https://github.com/Nemezjusz/ForexPredictionDashboard/assets/50834734/0f8b883c-2aee-4303-8487-34e63226a5fa)

## LSTM model predictions
![2024-02-01 164259](https://github.com/Nemezjusz/ForexPredictionDashboard/assets/50834734/fc6c7006-5227-419c-a013-c32b03749ca1)


## Installation

Clone the Repository:

    git clone https://github.com/Nemezjusz/ForexPredictionDashboard.git
    cd your-repo

Install Dependencies:

    pip install Flask yfinance matplotlib torch

Run the Application:

    flask run

    The application will be accessible at http://127.0.0.1:5000/ in your web browser.