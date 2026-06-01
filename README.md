# Seasonal and Trend Decomposition Methods for Time Series Forecasting

This project demonstrates different decomposition methods for time series analysis, including additive, multiplicative, and robust decomposition techniques.

## Business context

Time series data contains multiple layers of information woven together like threads in a tapestry. Decomposition methods allow us to separate these threads, revealing the underlying patterns that drive temporal behavior. By understanding seasonal patterns, long-term trends, and random fluctuations independently, we gain deeper insights into the forces shaping our data.

Time series decomposition is based on the idea that time series can be broken down into four fundamental components: trend, seasonality, cyclical patterns, and random variations. Let's explore this concept with Python using synthetic data.

The relationship between components can take different forms. The relationship between components can take different forms:

## Article

Medium article: [Seasonal and Trend Decomposition Methods](https://medium.com/@kylejones_47003/seasonal-and-trend-decomposition-methods-for-time-series-forecasting-c5d4564c981a)

## Project Structure

```
.
├── README.md           # This file
├── main.py            # Main entry point
├── config.yaml        # Configuration file
├── requirements.txt   # Python dependencies
├── src/               # Core functions
│   ├── core.py        # Decomposition functions
│   └── plotting.py     # Tufte-style plotting utilities
├── tests/             # Unit tests
├── data/              # Data files (if needed)
└── images/            # Generated plots and figures
```

## Configuration

Edit `config.yaml` to customize:
- Data generation parameters (date range, frequency, seed)
- Decomposition period
- Which decomposition methods to run
- Output settings

## Caveats

- By default, the script generates synthetic data with known trend, seasonality, and noise.
- Additive decomposition assumes components add together.
- Multiplicative decomposition assumes components multiply together.
- Robust decomposition uses Savitzky-Golay filtering for trend estimation.

## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).