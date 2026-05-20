# Paul Wilmott Introduces Quantitative Finance &mdash; Companion Series

A fourteen-deck companion to the textbook *Paul Wilmott Introduces Quantitative
Finance* (2nd Edition) by **Paul Wilmott** (John Wiley &amp; Sons, 2007). Each
deck is a single-page interactive presentation served on GitHub Pages &mdash;
KaTeX-rendered mathematics, dark-theme canvas illustrations, at least one
in-browser interactive widget per chapter, and a written line-by-line walk
through the most important results of the book.

The companion is independent and unofficial. The author retains all rights
to the original text; this series re-presents the material visually for
self-study and reference.

**Live index:** https://brendanjameslynskey.github.io/Wilmott_QF_Hub/

## Presentations in this series

### Markets and Derivatives

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [Products and Markets](https://brendanjameslynskey.github.io/Wilmott_QF_01_Products_and_Markets/) | live | Equities, dividends, splits, commodities, currencies, indices, time value of money, fixed-income basics, forwards and futures, no-arbitrage. Interactive forward-pricing calculator. |
| 02 | [Derivatives](https://brendanjameslynskey.github.io/Wilmott_QF_02_Derivatives/) | live | Calls, puts, payoff diagrams, put&ndash;call parity, binaries, spreads, straddles, strangles, butterflies, condors, calendars. Interactive payoff-and-P&amp;L composer. |

### The Random Walk

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 03 | [The Binomial Model](https://brendanjameslynskey.github.io/Wilmott_QF_03_Binomial_Model/) | live | One-step and multi-step binomial trees, risk-neutral probability, delta hedging, the continuous-time limit. Interactive binomial-tree pricer. |
| 04 | [The Random Behavior of Assets](https://brendanjameslynskey.github.io/Wilmott_QF_04_Random_Behavior_of_Assets/) | live | Returns, timescales, drift, volatility, the lognormal random walk, the Wiener process. Interactive GBM path simulator. |
| 05 | [Elementary Stochastic Calculus](https://brendanjameslynskey.github.io/Wilmott_QF_05_Stochastic_Calculus/) | live | The Markov and martingale properties, quadratic variation, Brownian motion, stochastic integration, SDEs, It&ocirc;'s lemma. Interactive Brownian-motion + quadratic-variation visualiser. |

### The Black&ndash;Scholes World

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 06 | [The Black&ndash;Scholes Model](https://brendanjameslynskey.github.io/Wilmott_QF_06_Black_Scholes_Model/) | live | A very special portfolio, elimination of risk by delta hedging, no arbitrage, the Black&ndash;Scholes PDE, assumptions, boundary &amp; final conditions, PDE solution methods. Interactive option-value surface viewer. |
| 07 | [The Black&ndash;Scholes Formul&aelig; and the Greeks](https://brendanjameslynskey.github.io/Wilmott_QF_07_Greeks_and_Hedging/) | live | Formul&aelig; for calls, puts, binaries; Delta, Gamma, Theta, Speed, Vega, Rho; implied volatility; the classification of hedging types. Interactive Greeks explorer. |
| 08 | [Overview of Volatility Modeling](https://brendanjameslynskey.github.io/Wilmott_QF_08_Volatility/) | live | Actual, historical, implied and forward volatility; GARCH; range-based estimators; skews and smiles; deterministic, stochastic and uncertain vol. Interactive implied-vol solver and smile/skew explorer. |

### Exotic and Multi-asset Options

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 09 | [Exotic and Path-dependent Options](https://brendanjameslynskey.github.io/Wilmott_QF_09_Exotic_Options/) | live | The option taxonomy: time and path dependence, dimensionality, order, embedded decisions. Barriers, Asians, lookbacks, compounds, Parisians. Interactive barrier-option Monte&nbsp;Carlo. |
| 10 | [Multi-asset Options](https://brendanjameslynskey.github.io/Wilmott_QF_10_Multi_asset_Options/) | live | Multidimensional lognormal random walks, the correlation matrix, exchange options via similarity reduction, basket options, the realities of correlation. Interactive correlated GBM scatter and basket-payoff explorer. |

### Fixed Income

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 11 | [Fixed-income Products, Yield and Swaps](https://brendanjameslynskey.github.io/Wilmott_QF_11_Fixed_Income/) | live | Zero-coupon and coupon bonds, the money-market account, FRAs, repos, STRIPS, day-count conventions, YTM, duration, convexity, bootstrapping forward rates, vanilla interest-rate swaps. Interactive bond-yield / duration calculator. |
| 12 | [Interest Rate Models](https://brendanjameslynskey.github.io/Wilmott_QF_12_Interest_Rate_Models/) | live | Stochastic short-rate models (Vasicek, CIR, Ho&ndash;Lee, Hull&ndash;White), the bond-pricing equation, the market price of risk, yield-curve fitting; the HJM forward-rate equation and the BGM LIBOR market model. Interactive short-rate path simulator. |

### Risk and Numerics

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 13 | [Portfolio Management, VaR &amp; Risk](https://brendanjameslynskey.github.io/Wilmott_QF_13_Portfolio_and_Risk/) | live | The Kelly criterion, diversification, Modern Portfolio Theory and the efficient frontier, CAPM, Value at Risk, credit risk and the Merton model, copulas, CrashMetrics. Interactive efficient-frontier + VaR explorer. |
| 14 | [Numerical Methods](https://brendanjameslynskey.github.io/Wilmott_QF_14_Numerical_Methods/) | live | Finite differences, Monte&nbsp;Carlo, numerical integration; the explicit FD scheme for Black&ndash;Scholes, Monte&nbsp;Carlo for European and American options (Longstaff&ndash;Schwartz), low-discrepancy sequences. Interactive Monte&nbsp;Carlo + finite-difference pricer. |

## Pedagogical arc

Wilmott's book is unusual in that it really *does* introduce quantitative
finance from the trading desk's point of view. The book moves quickly from
products to derivatives, builds the random walk in just enough rigour to
support Black&ndash;Scholes, then spends most of its length on the
practitioner consequences: smiles, skews, barriers, fixed income, the
HJM/BGM revolution, the numerical methods that price what closed forms
cannot, and the risk-management lessons that follow from the great
derivatives disasters. This companion follows the same arc &mdash; decks
01&ndash;05 build the machinery, 06&ndash;10 unfold the Black&ndash;Scholes
world and its exotic extensions, 11&ndash;12 take the same ideas into
fixed income, and 13&ndash;14 close with risk management and the numerics.

## How to read each deck

- Open the live presentation linked in the table above &mdash; everything
  renders in the browser, no install required.
- Scroll. Each deck is a vertical sequence of slides with a slide number in
  the corner; the table of contents on slide 00 links to each one.
- The interactive widgets are designed to be *touched*. Drag the sliders,
  click the canvases, change the seeds. The numbers update live.
- Keep the book open alongside &mdash; chapter and section numbers in each
  deck correspond to Wilmott's second edition.

## Credits and references

The presentations are a companion to, not a replacement for, the original
book. All credit for the underlying exposition belongs to:

> Wilmott, P. (2007). *Paul Wilmott Introduces Quantitative Finance,
> Second Edition.* John Wiley &amp; Sons. ISBN 978-0-470-31958-1.

This companion uses:
- [KaTeX](https://katex.org/) for math rendering
- HTML Canvas API for all interactive visualisations
- No build step, no JavaScript framework, no external data

Single-page HTML; clone the chapter repo and open `index.html` to run offline.

## Where this fits

- Part of the [Mathematics](https://github.com/BrendanJamesLynskey/Mathematics)
  hub &mdash; a collection of interactive presentation series in pure and
  applied mathematics.
- Companion to the [Mathematics for Machine Learning](https://github.com/BrendanJamesLynskey/MML_Hub)
  series &mdash; same dark-canvas style, same KaTeX maths, different domain.

## License

The presentations themselves are released for educational use.
The book's exposition, figures and worked examples remain copyright of
Paul Wilmott &mdash; this series re-presents the material visually rather
than reproducing the text.
