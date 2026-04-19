# alpha-mean-reversion

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/alpha-mean-reversion/blob/main/notebooks/alpha_mean_reversion.ipynb)

> Mean reversion alpha signal

> A trend-filtered mean-reversion signal. L4 enters long when RSI(14) < 30 AND price is above the 200-day EMA — oversold within an uptrend. S4 enters short when RSI(14) > 70 AND price is below the 200-day EMA — overbought within a downtrend. The trend filter prevents catching falling knives.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Helper functions |
| 3 | L4/S4 signal generation |
| 4 | Returns & performance |
| 5 | Per-ticker breakdown |
| 6 | Parameter sensitivity (RSI period, OS/OB thresholds) |
| 7 | Export signals for td-swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

