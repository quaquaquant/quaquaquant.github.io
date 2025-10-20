---
title: FX
permalink: /
layout: site
---

# FX forward-test results

This page showcases simulated trading results for several major FX pairs.
Individual strategies were trained on free historical data from
[TrueFX](https://www.truefx.com/truefx-historical-downloads/) and evaluated
on a hold-out interval.

For each pair, you’ll find a combined chart showing price, strategy equity,
and drawdown alongside key performance metrics. There are three simulations
per pair: long-only, short-only, and long/short. All results are net of spread.

Trades are executed with limit orders, and the strategies are designed to
tolerate up to a few seconds of signal-to-execution latency.
For a more detailed view, the trade-by-trade data is available and can be shared
for further analysis.

* TOC
{:toc}

## EURUSD September 2025

**Training:** March–August 2025  
**Evaluation**: September 2025  
**Spread**: fixed 1 pip (0.0001)

### Long-only

{% capture eurusd_long_metrics %}
{% include metrics/fx/eurusd-long.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/eurusd-long.svg"
   alt="EURUSD long-only: price, equity, drawdown"
   metrics=eurusd_long_metrics
%}

### Short-only

{% capture eurusd_short_metrics %}
{% include metrics/fx/eurusd-short.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/eurusd-short.svg"
   alt="EURUSD short-only: price, equity, drawdown"
   metrics=eurusd_short_metrics
%}

### Long/Short

{% capture eurusd_both_metrics %}
{% include metrics/fx/eurusd-both.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/eurusd-both.svg"
   alt="EURUSD long/short: price, equity, drawdown"
   metrics=eurusd_both_metrics
%}

## USDJPY September 2025

**Training:** March–August 2025  
**Evaluation**: September 2025  
**Spread**: fixed 2 pips (0.02)

### Long-only

{% capture usdjpy_long_metrics %}
{% include metrics/fx/usdjpy-long.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/usdjpy-long.svg"
   alt="USDJPY long-only: price, equity, drawdown"
   metrics=usdjpy_long_metrics
%}

### Short-only

{% capture usdjpy_short_metrics %}
{% include metrics/fx/usdjpy-short.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/usdjpy-short.svg"
   alt="USDJPY short-only: price, equity, drawdown"
   metrics=usdjpy_short_metrics
%}

### Long/Short

{% capture usdjpy_both_metrics %}
{% include metrics/fx/usdjpy-both.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/usdjpy-both.svg"
   alt="USDJPY long/short: price, equity, drawdown"
   metrics=usdjpy_both_metrics
%}

## USDCHF September 2025

**Training:** March–August 2025  
**Evaluation**: September 2025  
**Spread**: fixed 2 pips (0.0002)

### Long-only

{% capture usdchf_long_metrics %}
{% include metrics/fx/usdchf-long.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/usdchf-long.svg"
   alt="USDCHF long-only: price, equity, drawdown"
   metrics=usdchf_long_metrics
%}

### Short-only

{% capture usdchf_short_metrics %}
{% include metrics/fx/usdchf-short.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/usdchf-short.svg"
   alt="USDCHF short-only: price, equity, drawdown"
   metrics=usdchf_short_metrics
%}

### Long/Short

{% capture usdchf_both_metrics %}
{% include metrics/fx/usdchf-both.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/usdchf-both.svg"
   alt="USDCHF long/short: price, equity, drawdown"
   metrics=usdchf_both_metrics
%}

## AUDUSD September 2025

**Training:** March–August 2025  
**Evaluation**: September 2025  
**Spread**: fixed 2 pips (0.0002)

### Long-only

{% capture audusd_long_metrics %}
{% include metrics/fx/audusd-long.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/audusd-long.svg"
   alt="AUDUSD long-only: price, equity, drawdown"
   metrics=audusd_long_metrics
%}

### Short-only

{% capture audusd_short_metrics %}
{% include metrics/fx/audusd-short.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/audusd-short.svg"
   alt="AUDUSD short-only: price, equity, drawdown"
   metrics=audusd_short_metrics
%}

### Long/Short

{% capture audusd_both_metrics %}
{% include metrics/fx/audusd-both.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/audusd-both.svg"
   alt="AUDUSD long/short: price, equity, drawdown"
   metrics=audusd_both_metrics
%}

## NZDUSD September 2025

**Training:** March–August 2025  
**Evaluation**: September 2025  
**Spread**: fixed 2 pips (0.0002)

### Long-only

{% capture nzdusd_long_metrics %}
{% include metrics/fx/nzdusd-long.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/nzdusd-long.svg"
   alt="NZDUSD long-only: price, equity, drawdown"
   metrics=nzdusd_long_metrics
%}

### Short-only

{% capture nzdusd_short_metrics %}
{% include metrics/fx/nzdusd-short.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/nzdusd-short.svg"
   alt="NZDUSD short-only: price, equity, drawdown"
   metrics=nzdusd_short_metrics
%}

### Long/Short

{% capture nzdusd_both_metrics %}
{% include metrics/fx/nzdusd-both.txt %}
{% endcapture %}

{% include cm.html
   img="/assets/charts/fx/nzdusd-both.svg"
   alt="NZDUSD long/short: price, equity, drawdown"
   metrics=nzdusd_both_metrics
%}
