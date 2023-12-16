# Risk-modelling

Risk analysis conducted for Inpost company: univariate, multivariate analysis, bactesting, VaR modelling, ...

Considered risk variables are:
* Diesel prices,
* petrol prices,
* currency exchange rates.

These are, according to me, the most important risk factors for logistic and transport company such like Inpost. The analysis was conducted for the period 2012-2022.

## Data

Data was collected from the following sources:
* [NBP](https://nbp.pl/en/statistic-and-financial-reporting/rates/)
* [Orlen](https://www.orlen.pl/pl/dla-biznesu/hurtowe-ceny-paliw#paliwa-archive)

## Analysis

The analysis was conducted in Python. It consists of three different parts:
* Uni- and multivariate analysis of risk factors + backtesting,
* Minimal risk portfolio analysis,
* VaR modelling using different methods (historical, parametric, Monte Carlo, Garch, ...).

The corresponding files are:
* `I_risk_analysis.ipynb`,
* `II_portfolio_analysis.ipynb`,
* `III_VaR_modelling.ipynb`.

Project was conducted as a part of the course "Risk modelling" at Wrocław University of Science and Technology.