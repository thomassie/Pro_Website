---
layout: page
title: R Shiny
published: true
---

Here you can find some projects that I have done using the R package [R Shiny](https://shiny.rstudio.com/). Shiny allows to make interactive web apps straight from R. That is, people who are not familiar with R code are given the opportunity to explore data and infer insights from it. Really nice!

  * [**Discrete logistic growth**](###discrete-logistic-growth):
    Time-discrete population growth, the road to chaos, and a comparison to the case when additional, demographic stochasticity is present.
  * [**Climate data**](###climate-data): Have look at the climate of specific countries and regions in the world and how average temperatures changed there.
  * [**Hurricanes and typhoons**](###hurricanes-and-typhoons): Get an idea about hurricanes and typhoons: their paths and strengths, as well as a couple of summary statistics.  


## Discrete logistic growth

Imagine an organism that propagates once a year, and all individuals within a population do so at the same point in time. This is the case for many, many living creatures, especially when their life cycle is influenced by seasons. That is, there are specific conditions during a year that are more favourable than others for fathering and raising offspring. Without any restrictions related to population density (food, diseases, competition...) such an organisms would show exponential growth. For example, if any individual would create two descendants, then the population would evolve according to 2<sup>n</sup>, with n being the number of reproduction cycles, i.e., years.

However, we all know that no population growths without limits. There are certain factors that regulate the number of individuals, such as the availability of resources (food, space...), or the susceptibility to diseases. These factors are related to the number of individuals living in a given space, that is population density. Therefore, these growth-limiting factors are called density-dependent.
[here](https://thomassie.shinyapps.io/logisticgrowthtimediscrete/)

![LogisticGrowth.png]({{site.baseurl}}/img/LogisticGrowth.png)  


### Climate data
Explore climate data from different countries and regions, and get an idea about what the annual cycle of average surface temperatures looks like. For example, it is intereting to see in which regions the cycle shows an unimodal shape with a maximum in June/July/August (Northern hemisphere), or when this peak is shifted to November/December/January (Southern hemisphere).  

[here](https://thomassie.shinyapps.io/climatedataapp/)

![ClimateData.png]({{site.baseurl}}/img/ClimateData.png)  

### Hurricanes and typhoons

(comming soon)