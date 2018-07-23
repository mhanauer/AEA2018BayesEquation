---
title: "AEA2018BayesEquation"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
So the model is time across the outcome reading with random intercepts and slopes

$$ Level1:{y_{ij} = \beta_{0j} + \beta_{1j}Time_{ij} + e_{ij}}~~~ (1.1)$$ 
$$ Level~2~Intercept:~~~{\beta_{0j} = \gamma_{00} + u_{0j}} ~~~ (1.2)$$ 
$$ Level~2~Slope~Time:{\beta_{1j} = \gamma_{10} + u_{1j}} ~~~ (1.3)$$
 $$Mixed~model: ~~~{y_{ij} = (\gamma_{00} + u_{0j}) + (\gamma_{10}} +u_{1j})*Time_{ij} + e_{ij} $$
 


 
