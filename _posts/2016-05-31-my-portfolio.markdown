---
layout: portfolio
title:  "Chris Castle's Portfolio"
---
This is a collection of my work over the last few years. 

## Kindle Clips
The Kindle clips project I'm working on with my partner Mike Kelly [can be found here][jekyll-kc]. The [Github repo is here][jekyll-kc-github] It's a work in progress but we hope to have a public demo available soon.

## Shiny web app

The pitchdeck for a Shiny app I wrote which predicts player position based on physical attributes [can be found here][jekyll-nfl-pitch]. Shiny is a web application framework for R. It allows R users to make interactive web apps. The app itself [is available to for use here.][jekyll-nfl]

<a href="https://chriscastle.shinyapps.io/DDP-proj-NFL-combine/" target="_blank">
![shiny example]({{ localhost:4000 }}/assets/shinyapp-example.png){: .shiny-image} </a>
*Physical attributes are given as inputs and a simple decision tree predicts the player's position*

## Analytic reports written in R/R Markdown

[Lending Club Analysis][jekyll-lc] - A report on Lending Club's customers and business model using their publicly available data. 

<a href="http://www.googledrive.com/host/0Bw6a2LJ4wLU-Mkt4cDRTakZuWUk">
![lending club graph]({{ site.url }}/assets/loan-repaid-rate.png){: .right-image} </a>
*a graph of the rate of loans repaid by interest rate from the Lending Club report*{: .right-image}

[Quantifying Exercise Quality][jekyll-qeq] - A report on the effectiveness of using physical censors to judge the *quality* of certain exercises. 

<a href="http://rpubs.com/christopher_castle/154339">
![exercise density]({{ localhost:4000 }}/assets/exercise-density.png){: .right-image} </a>
*a single sensor's measurement distributions for each quality of a given exercise*{: .right-image}

[Major Weather Events in the U.S.][jekyll-weather] - What are the worst weather events inflicting the United States? We use NOAA data to determine the worst type of weather events to human health and property.

[Regression models using Motor Trend car data][jekyll-motor] - Multivariate regression models are used to analyse the relationship between transmission and fuel efficiency.

<a href="http://rpubs.com/christopher_castle/MotorTrend">
![mpg by weight]({{ localhost:4000 }}/assets/motor-mpgbyweight.png){: .right-image} </a>
*miles-per-gallon plotted with weight and horsepower and faceted by transmission type and number of cylinders. From the Motor Trend data set*{: .right-image}

[Simulation of the Central Limit Theorem][jekyll-clt] - A fundamental topic in inferential statistics. The report shows that by repeatedly taking the sample mean from an exponential distribution that the resulting distribution of those sample means is essentially normal given a large enough sample size. 

[Analysis of the Titanic crash][jekyll-titan] - One of the first reports in R Markdown I wrote a few years ago. C

## Resume
You can [get the PDF of my resume here]({{ site.url }}/assets/CastleResume.pdf).

<a href="http://89million.github.io/assets/CastleResume.pdf" target="_blank">
![resume]({{ localhost:4000 }}/assets/CastleResume.png){: .center-image} </a>


[jekyll-lc]: http://www.googledrive.com/host/0Bw6a2LJ4wLU-Mkt4cDRTakZuWUk
[jekyll-titan]: http://www.googledrive.com/host/0Bw6a2LJ4wLU-anFza19sWkZrOWc
[jekyll-kc]: https://kindleclips.herokuapp.com/
[jekyll-kc-github]: https://github.com/mikechriskelly/kindleclips
[jekyll-nfl]: https://chriscastle.shinyapps.io/DDP-proj-NFL-combine/
[jekyll-nfl-pitch]: http://rpubs.com/christopher_castle/148572
[jekyll-qeq]: http://rpubs.com/christopher_castle/154339
[jekyll-weather]: http://rpubs.com/christopher_castle/137535
[jekyll-clt]: http://rpubs.com/christopher_castle/137490
[jekyll-motor]: http://rpubs.com/christopher_castle/MotorTrend