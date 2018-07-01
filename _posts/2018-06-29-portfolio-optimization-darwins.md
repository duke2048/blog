---
layout: post
title: 'Basic darwins portfolio creation '
date: '2018-06-29 11:03:00 +0000'
categories: []
published: true
---
We will use the Risk Parity ([wikipedia](https://en.wikipedia.org/wiki/Risk_parity)) approach to allocate our assets.

From the link above:

> Roughly speaking, the approach of building a risk parity portfolio is similar to creating a minimum-variance portfolio subject to the constraint that each asset contributes equally to the portfolio overall volatility.

## Strategy

1. Run monthly
2. The darwins to invest comes from the [post]({% post_url 2018-06-29-filters-select-darwins%})
3. Assets weights are calculate using the Risk Parity method using 1 year lookback
4. Rebalance portfolio

## Visualizing

The behaviour of the portfolio allocation since 2017-06 was:

![](assets/images/20180630115200.png)

Stat|Portfolio Risk/Parity Allocation|Portfolio Equal Allocation
Total Return|30.56%|28.67%
\Max Drawdown|-4.89%|-5.82%
