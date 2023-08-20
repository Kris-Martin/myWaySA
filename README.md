# myWaySA

An interactive app, providing a one stop platform for tourism discovery and engagement in SA created for
[GovHack 2023.](https://hackerspace.govhack.org/)

## Contents

- [Authors](#authors)
- [Description](#description)
- [Figma](#figma)
- [Walkthrough Video](#walkthrough-video)
- [Sources and References](#sources-and-references)
- [Licenses](#licenses)

## Authors

Copyright (c) 2023 DataWay - Angus Colovic, Hollie Brown, Jamie Halls, Pulkit Verma,
Rupindeer Kaur, Tilly Symonds, Utkarsh Saxena, Amy Gaetjens and Kristy Martin. Software released under the MIT License, non-software content under Creative Commons Attribution 4.0 International Public License.

## Description
To gather a view of South Australia’s tourism industry, datasets were obtained from Tourism Research Australia. These show both the direct and indirect Gross value Added (GVA) of the Tourism Industry in South Australia, as well as employment and consumption. In this context, GVA refers ot the impact of the tourism industry on the Austrlaian economy, both directly (impacts from tourism) and indirectly (impacts arising as a result of the impacts from tourism). Consumption, likewise refers to the aggregated spending from tourists, in terms of producer prices.

Our goal from this data was to gather estimates for the impact of our proposed mobile app on the South Australian tourist industry. Our first step was to generate a forecast for consumption in Australia to the 2027-28 financial year. Long-term expenditure forecasts were obtained at a national level from Tourism research Australia. Growth rates were extracted from these forecasts and applied to South Australian consumption growth. We therefore assume in our forecast that growth in South Australian consumption mirrors forecasted growth in national total tourism expenditure. This ultimately delivers our baseline forecasts for tourism consumption in South Australia.

To estimate the impact of our proposed application on total consumption (that is,total tourist spending) we consider four factors. These are:
1. The percentage of tourists that have smartphones.
2. The adoption rate of the proposed app by tourists with smartphones
3. The expected integration rate of the app by businesses
4. The expected increase in purchases (in net monetary value) by tourists that have installed the app

As such, the net increase in total tourism consumption will be equal to:
% increase in consumption = % of tourists with smartphones % adoption rate of app
% integration rate by businesses % expected increase in purchases

For our analysis, the number of tourists with smartphones was expected to mirror the broader Australian population. Forecasts for this rate were obtained from Statista, which directly generated the values. The average annual growth rate in the proportion of people with smartphones was projected only for the 2027 financial year

The expected increase in the net monetary value of purchases was taken from literature (Narang and Shnakar 2019) who find in their case study of a large retail provider that app adopters spend 36% more in net monetary value.

Both the adoption rate of the proposed app by tourists, as well as the integration rate of the app by businesses were more difficult to estimate. This is due to a large degree of variability in adoption rates, depending closely on perceived usefulness, visual design, enjoyment, operation aspects and ease of use (Kuo et al. 2019) (Sanchez-Torres et al. 2021).

As such, we propose two scenarios.

In the low scenario, an app adoption rate of 25% and a business integration rate of 30% was assumed to be reached by the 2027 financial year.

In the high scenario, an app adoption rate of 45% and a business integration rate of 50% was assumed to be reached by the 2027 financial year.

Applying these scenarios, we find that in the 2027 financial year, a 2.3% increase is found in the low scenario above the baseline forecasted consumption. This corresponds to an increase in consumption (or total sales) of $322 million AUD.

Likewise, in the high scenario, a 6.6% increase in consumption is found, representing an increase in consumption of $966 million AUD.

Future analysis would focus on creating more robust estimates of the adoption and integration rates. This would involve a deeper degree of research into the factors that determine an app’s success, and existing market saturation.

So to make an interactive dashboard with some of the features that would be needed in the app. We leveraged open source government data on a google maps API to display this feature of the app.

We have entered this solution into both “Highlight the diversity of South Australia's tourism product through gamification” and “Increase visitor expenditure through Smart Tourism”. [Hackerspace]([https://hackerspace.govhack.org/](https://hackerspace.govhack.org/team_management/teams/2124))

## Figma
[Figma]([https://www.figma.com/file/iwP4CwWQU14SZ6cEM0cQsz/ESGenius-(Community)?type=design&node-id=0%3A1&mode=design&t=JUrbUJe3Y1pTHmHk-1](https://www.figma.com/community/file/1274979287495852823/MyWaySA))

## Walkthrough Video


## Link to Hackerspace Profile
https://hackerspace.govhack.org/team_management/teams/2124

## [Sources and References](https://hackerspace.govhack.org/team_management/teams/2124/team_data_sets)


## Licenses

[MIT](https://choosealicense.com/licenses/mit/)

[Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)
