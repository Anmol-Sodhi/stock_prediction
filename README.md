Stock Analysis and Prediction Tool

Overview

This tool analyzes and predicts stock prices using historical data, technical indicators, and sentiment analysis. It generates visualizations to help investors make informed decisions by understanding potential future stock movements and correlations with economic indicators.




Setup Instructions
Step 1: Download Conda

Go to the official Conda website(https://docs.conda.io) and download the installer for your operating system (Windows, macOS, or Linux).
Follow the installation instructions for your platform.



Step 2: Download the Project Files

Clone the project repository using the terminal:

git clone (repository-url)

cd (your project-directory)

Install Dependencies

Create a new Conda environment with Python 3.8.19 by running the following command and Install the necessary dependencies:

conda create --name test_env python=3.8.19

conda activate test_env

pip install -r requirements.txt







3.Ensure that the following CSV files are placed in the same directory as the script everytime you run it:

Russel_3000_ticker_list.csv
TSX List.csv
TSXV.csv
CSE Listings.csv
India stock list.csv
These files contain lists of valid stock tickers and are required for the script to verify the tickers you input.





4. Run the Script
 
In the Command Prompt or Terminal, ensure you're in the project directory.

Run the script by typing:

python stocks.py





5. Enter Tickers When Prompted
The script will prompt you to:


Enter the tickers (comma-separated):


Type in the stock ticker symbols you want to analyze, separated by commas.

For example:

Enter the tickers (comma-separated): AAPL

or

Enter the tickers (comma-separated): AAPL, MSFT
etc




Step 6: View the Outputs

The script will perform the analysis and generate several visualizations.

Sentiment Analysis Graph

What It Is: A graph showing how specific words from news articles contribute to the overall sentiment about the stock.
Action Required: Close the sentiment graph window after viewing it to proceed to the next graphs.
Stock Analysis Graph

What It Is: A graph displaying the stock's historical prices, predictions, and technical indicators.
Correlation Heatmap

What It Is: A grid showing how the stock price correlates with various economic indicators.




Understanding the Visualizations

1. Sentiment Analysis Graph
Positive Terms (Blue Bars):

Words that have a positive impact on investor sentiment.
Negative Terms (Red Bars):

Words that have a negative impact on investor sentiment.
How to Read It:

The height of each bar represents how much that word influences the overall sentiment.
Helps identify key factors affecting market perception of the stock.


2. Stock Analysis Graph
Bollinger Bands (Blue Lines):

Upper and lower bands that help identify volatility and potential price movements.
Prophet Forecast (Purple Line):

Predicted future stock prices based on historical data.
Bullish Signals (Green Triangles):

Indicators of potential upward trends in stock price.
Bearish Signals (Red Triangles):

Indicators of potential downward trends in stock price.

3. Correlation Heatmap
Color-Coded Grid:

Shows how closely related the stock price is to various economic indicators.
Red Areas: Strong positive correlation.
Blue Areas: Strong negative correlation.
How to Read It:

Helps you understand which economic factors may impact the stock price.




***IMPORTANT***

Sequence of Graphs:

First, the Sentiment Analysis Graph will appear.
You need to close this graph window to proceed.
Then, the Stock Analysis Graph and Correlation Heatmap will appear.
Closing Graph Windows:

To close a graph, click the 'X' button on the window.
Alternatively, press Alt + F4 (Windows) or Command + W (Mac) while the window is active.
Internet Connection:

Ensure you have a stable internet connection throughout the process.
Processing Time:

The script may take several minutes to run, especially if analyzing multiple tickers.
Please be patient and wait for the graphs to appear.



--------------------------------------------------------------------------------


When the output is generated , first the sentiment graph will appear, close that and then the stock prediction graph and economic indicator grid will appear.
























