# sector-rotation-strategy
Equity Trading Strategy using on systematic sector rotation. The strategy is based on part 1 (Rate of Change) of the paper written by Paolo Sassetti and Massimiliano Tani in 2003.

Heuristic (rule-based) based equity trading strategies have existed for well over 50 years. Ben Graham’s value investing approach was by itself to some extent heuristic-based (low PE ratio, low debt to current assets ratio, positive EPS growth etc.). The advent of powerful computation tools and the availability of data has only accelerated research on these criteria-based trading models. Large hedge funds like Renaissance Technologies generate several terabytes of data each day and run advanced quantitative models to select stocks.

One such approach is the systematic sector-rotation strategy published by two Italian academics – Paolo Sassetti and Massimiliano Tani. The paper was originally published in 2003 and has been quoted in various subsequent research on this subject. At its heart, the ideas comprised in it are quite simple.

At different points in the economic cycle, different sectors tend to perform well. Financials and consumer discretionary perform well during the early stages of the business cycle as the availability of cheap credit gets firms and consumers borrowing. As the economic cycle improves further and more businesses start making capital investments, capital goods, industrial and technology companies tend to do well. As the economy starts contracting again, consumer staples and healthcare stocks tend to outperform other stocks. This trend has been quite well documented notably by Fidelity research.
The sectors that have performed well in the recent past, will continue to perform well in the ‘recent’ future. This is at the crux of momentum-based strategies.
Sassetti and Tani ran a backtesting algorithm to test their hypothesis that a systematic-sector rotation strategy based on momentum indicators will beat the benchmark over the long run. Lo and behold, they found evidence of significant outperformance. They tested their hypothesis using three different approaches. This code implements this trading strategy using the 19 different sectors in India's BSE. It will only cover the first approach published on the paper called Rate of Change.

A full description of the algorithm, the original paper and the results are on this link:
https://everyfin.in/2021/03/26/equity-trading-strategy-systematic-sector-rotation/
