# Hammer Candlestick Algorithm

An algorithm for Hammer candlestick pattern recognition.

[Candlestick patterns](https://en.wikipedia.org/wiki/Candlestick_pattern)

## Build

To install the all the packages :

``` node
npm install
```

## Input

A `csv` file named `data.csv` should be present in `src` directory

## Run

``` node
node index
```

## Output

A `csv` file named `hammer.csv` will be generated in `output` directory. Which contains all hammer candlestick pattern identified in the given dataset.

In the console two plotly links will be displayed, which displays the candlestick chart for the given dataset and the filtered hammer candlesticks.

## Note
Since the code uses plotly for the charts, you must bring your own `Account_Name` and `API_Key`

[plotly](https://chart-studio.plotly.com/Auth/login/#/)

Replace your `ACCOUNT_NAME` and `API_KEY` in `./utils/chartUtils.js` to generate charts.
