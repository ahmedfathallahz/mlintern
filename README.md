# Strategic Content Refresh: Performance Decay Analysis

## Title + Abstract

This study investigates content performance decay to recover lost search traffic. I compared recent performance against historical data to identify pages experiencing traffic drops. By analyzing 30-day windows, I identified high-impact pages for optimization. My findings demonstrate that targeted content refreshes can effectively reverse decay and restore search visibility.

## Introduction / Problem Statement

Content decay occurs when pages lose their search ranking and traffic over time due to outdated information or shifting search intent. This leads to wasted impressions. Identifying these pages allows me to prioritize content maintenance and maximize existing organic search equity.

## Data

I utilized the FlyRank ML Internship dataset. I focused on daily content performance logs, filtering for pages with over 50 clicks in the baseline period to ensure relevance. The dataset used is pseudonymized and public-safe.

## Methodology

I employed a comparative performance analysis:

1. Baseline: Aggregated clicks from the 30-day period prior to the recent window.

2. Recent: Aggregated clicks from the last 30 days.

3. Growth Rate Calculation: (Recent - Baseline) / Baseline.

I focused on identifying pages with significant negative growth rates indicating decay.

## Results

The analysis identified a clear segment of content experiencing downward trends. I visualized this by calculating the growth rate delta across the portfolio, which highlights the specific pages that require immediate intervention to halt traffic loss.

## Limitations & Honest Framing

This analysis relies solely on GSC click data. I acknowledge that external factors like seasonality or algorithm updates are not fully captured in this model. This is a directional analysis for decision support.

## Ranked Recommendations

1. Update Content: Refresh outdated facts and improve value.

2. Meta Optimization: Rewrite titles to boost CTR.

3. Internal Linking: Boost authority by linking from high-performing pages.

## Reproducibility

The analysis is reproducible using the notebooks stored in the /work directory of this repository.

## Acknowledgments & Data Credit

Built on the FlyRank ML Internship dataset (https://flyrank.ai).
Internal Linking: Boost authority by linking from high-performing pages.
Reproducibility
The analysis is reproducible using the notebooks stored in the /work directory of this repository.
Acknowledgments & Data Credit
Built on the FlyRank ML Internship dataset (https://flyrank.ai).
