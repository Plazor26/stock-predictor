# Stock Price Predictor

This is a Flask-based web application that predicts stock prices based on historical data. The application features a custom "Dark Miku" aesthetic, which combines a dark, futuristic style with Hatsune Miku's iconic teal color scheme.

## Features

- **Stock Price Prediction**: Predicts the closing price of a stock for a given date using linear regression based on historical data.
- **Custom Aesthetic**: Styled with a unique "Dark Miku" theme, blending dark tones with teal accents for a modern, futuristic look.
- **Error Handling**: Provides user-friendly error messages for invalid ticker symbols or date formats.

## Tech Stack

- **Backend**: Flask
- **Frontend**: HTML, CSS (custom styling)
- **Data**: `yfinance` library for fetching stock data
- **Machine Learning**: Linear Regression from `scikit-learn`
  
## Installation

### Prerequisites

Make sure you have Python 3.7+ installed on your machine.

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/dark-miku-stock-predictor.git
    cd dark-miku-stock-predictor
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Requirements

Your `requirements.txt` file should include the following:
```plaintext
Flask
yfinance
pandas
scikit-learn
** (e.g., `AAPL` for Apple, `GOOGL` for Alphabet) in the input field.
2. Enter the **date** (in YYYY-MM-DD format) for which you want the stock price prediction.
3. Click **Predict** to get the estimated stock price for that date.

## Project Structure

```
stock_predictor/
├── app.py              # Flask application
├── model.py            # Stock prediction model
├── templates/
│   └── index.html      # HTML template for UI
├── static/             # Static files (CSS, JS, etc.)
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
```

## Technologies Used

- **Flask**: For building the web interface.
- **scikit-learn**: For the machine learning model (Linear Regression).
- **yfinance**: For fetching historical stock data.
- **pandas**: For data manipulation.

## Future Enhancements

- 🔄 **Additional Machine Learning Models**: Adding support for more complex models like Decision Trees or LSTM.
- 📱 **Mobile-friendly UI**: Improving the design to be more responsive on mobile devices.
- ⏲️ **Live Data Update**: Use real-time stock data for prediction rather than relying solely on historical data.

## Contributing

Feel free to submit issues or pull requests if you'd like to improve the project!

## License

This project is licensed under the MIT License.
