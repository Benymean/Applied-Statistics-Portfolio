# 1.Analysis of Traffic Congestion and Analysis of Cake Quality

This repository contains a reproducible R markdown file that delves into two primary analyses: understanding and predicting traffic congestion patterns in a U.S. metropolitan area and determining the effect of recipe and baking temperature on the breaking angle of a chocolate cake.

## Table of Contents

1. [Traffic Congestion Analysis](#traffic-congestion-analysis)
   - [Overview](#overview)
   - [Dataset Description](#dataset-description)
   - [Questions Addressed](#questions-addressed)
2. [Cake Quality Analysis](#cake-quality-analysis)
   - [Overview](#overview-1)
   - [Dataset Description](#dataset-description-1)
   - [Questions Addressed](#questions-addressed-1)
3. [Dependencies](#dependencies)
4. [License](#license)

## Traffic Congestion Analysis

### Overview

Traffic congestion remains an ongoing challenge, causing traffic delays, inconveniences for commuters, economic losses, and contributing to air pollution. This analysis seeks to understand and predict traffic congestion patterns in a U.S. metropolitan area.

### Dataset Description

The dataset `traffic.csv` contains information about 62 regions within the metropolitan area with the following variables:
- `spi`: Speed Performance Index representing the level of traffic congestion.
- `transport`: Public Transportation Accessibility index.
- `road`: Road Capacity Index.
- `weather`: Weather Severity Index.
- `fuel`: Average fuel price (in USD per gallon) in each region.
- `wind`: Average wind speed (in mph) in each region.

### Questions Addressed

This analysis aims to:
1. Produce a plot and a correlation matrix of the data.
2. Fit a model using all the predictors to explain the `spi` response.
3. Conduct an F-test for the overall regression.
4. Validate the full model.
5. Determine the R^2 value and its implications.
6. Use model selection procedures to find the best regression model.

# 2. Cake Quality Analysis

### Overview

An experiment was conducted to understand the effects of the recipe and baking temperature on the breaking angle of a chocolate cake, which is a measure of its quality.

### Dataset Description

The dataset `cake.csv` contains information about different chocolate cake recipes baked at varying temperatures. The variables include:
- `Angle`: Angle at which the cake broke.
- `Recipe`: Recipe used for the cake.
- `Temp`: Temperature at which the cake was baked (ranging from 175°C to 225°C).

### Questions Addressed

This analysis seeks to:
1. Determine if the design is balanced or unbalanced.
2. Construct preliminary graphs to investigate data features.
3. Define the full interaction model for the study.
4. Analyze the data to study the effects of temperature and recipe on the cake's breaking angle.
5. Draw conclusions on the effect of temperature and recipe on the response angle.

## Dependencies

- R
- R Package: `tinytex`
