---
title: "dash-covid19"
excerpt: "A Dash app for viewing and exploring up-to-date information on the Covid19 pandemic"
collection: projects
---

Introduction
------------

> **NOTE**: This project is still in early planning phases

[dash-covid19](https://github.com/rbpatt2019/dash-covid19/) is a
[Dash](https://dash.plotly.com/) app for viewing up-to-date information related
to the spread of Covid-19 using the data provided by a variety of sources collated by [Our World in Data](https://ourworldindata.org/).

Docs and Code
-------------

This app is hosted by Heroku and lives [here](https://dash-covid19-pro.herokuapp.com/)

The documentation is forthcoming, and will likely live as either it's own app, or a tab within this app.

The code lives in [the repo](https://github.com/rbpatt2019/dash-covid19/).

About the Data
--------------

Fundametally, good data science requires two things: good data and good questions.
Since good questions frequently evolve from exploratory data analysis,
one could argue that good data science needs only one things: good data.
Crap in, crap out, as they say...
Now, how does one get data?
As a trained biologist, my first thought is structured experiments,
with repeated samples, controls groups, and as many data points as feasibly possible.
Unfortunately, this structured framework isn't always possible,
particularly when dealing with rpaidly evolving, as-of-yet not fully understood situations
like the current Covid-19 pandemic.
In these cases, where limitations are inherent to the problem, transparency becomes critical.
We must accept that the data are not, and cannot be, perfect,
recognise the limitations in the data,
and be open about any limitations when discussing interpretations of the data.

To that end, I have elected to use data collated by the team at
[Our World in Data](https://ourworldindata.org/) (OWID)
when constructing my app. The data are freely avaialble, and can be found in their
[repo](https://github.com/owid/covid-19-data/tree/master/public/data).
Their principle source of data is the
[European Center for Disease Prevention and Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide)
(ECDC), who provide daily updates of worldwide statistics.
OWID thoroughly discusses all their sources, methods for data handling,
and the reasoning behind any decisions they make relating to data management.
Please, visit their [repo](https://github.com/owid/covid-19-data/tree/master/public/data)
for any questions you may have about the data.
