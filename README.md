# ForexTradingApp

Aplikacja przedstawia najnowsze dane, wykresy oraz przewidywania dotyczące popularnych lub wybranej przez użytkownika firmy lub waluty. 
Dane przedstawiane są na stronie html stworzonej przy użysciu *Boostrapa* a pobierane są z *Yfinance*. Wykresy są stworzone przy pomocy biblioteki *Matplotlib*. 
Strona oferuje także osobną sekcje przeznaczoną na przewidywania oparte na wytrenowanym modelu LSTM.

## Dane najpopularniejszych tickerów
![Zrzut ekranu 2024-02-01 164204](https://github.com/Nemezjusz/ForexPredictionDashboard/assets/50834734/666c275c-3a3e-4d71-8697-a31e09f40614)

## Wykresy dotyczące wybranej firmy lub waluty
![Zrzut ekranu 2024-02-01 164141](https://github.com/Nemezjusz/ForexPredictionDashboard/assets/50834734/0f8b883c-2aee-4303-8487-34e63226a5fa)

## Przewidywania modelu LSTM
![2024-02-01 164259](https://github.com/Nemezjusz/ForexPredictionDashboard/assets/50834734/fc6c7006-5227-419c-a013-c32b03749ca1)


## Instalacja

Clone the Repository:

    git clone https://github.com/Nemezjusz/ForexPredictionDashboard.git
    cd your-repo

Install Dependencies:

    pip install Flask yfinance matplotlib torch

Run the Application:

    flask run

    The application will be accessible at http://127.0.0.1:5000/ in your web browser.


