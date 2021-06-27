# nuclear-question


## Table of Contents
* [Link to Tableau](#link-to-tableau)
* [Goals](#goals)
* [Why Nuclear Energy?](#why-nuclear-energy)
* [Data Questions](#data-questions)
* [Known Issues and Challenges](#known-issues-and-challenges)
* [Impact](#impact)
* [Deaths from Nuclear Power Accidents](#deaths-from-nuclear-power-accidents)
* [Deaths from Fossil Fuel Air Pollution](#deaths-from-fossil-fuel-air-pollution)
* [Deaths by Energy Source](#deaths-by-energy-source)
* [Death Reduction and % from Nuclear](#death-reduction-and-%-from-nuclear)
* [Pollution and Power](#pollution-and-power)
* [Tools](#tools)
* [Data Sources](#data-sources)

## Link to Tableau
https://public.tableau.com/app/profile/ian.alister.gray/viz/TheNuclearQuestion/AssessingNuclearPower

## Goals

The goal of this project is to look at the impact that Nuclear Energy, its human cost, and how it stacks up against other forms of energy production.

## Why Nuclear Energy? 

Given that the discovery of atomic fission has been one of the most influential scientific discoveries of our time, shaping everything from pop culture to international politics, it's important to understand the impacts that it has had on our world. 

## Data Question

The core data question at the center of this analysis is "Do the benifits of Nuclear energy outweigh the risks associated with nuclear proliferation?"

## Known Issues and Challenges
My initial vision for the project was to include data pertaining to the liklihood of a nuclear conflict and compare that to whatever benefits I might find related to nuclear power, but the more I read, the more it became apparant that no such data exists. Different people have come up with different formulas to calculate it, but it is impossible to know how accurate they are because it is very difficult to assess the liklihood of something happening for the first time, especially an event with as many varriables as this.

Given this to be the case, I focused my analysis on the impacts of nuclear energy.

For the sake of consistency, all visuals are filtered to the year 2017.

## Impact
### Reducing Fossil Fuel Pollution
- Deaths from Nuclear Power Accidents
- Deaths from Fossil Fuel Air Pollution
- Deaths by Energy Source
- Death Reduction and % from Nuclear

## Deaths from Nuclear Power Accidents
Here we look at the deaths assiciated with the handful of plant disasters throughout history. It is noteworthy that while the accidents at Chernobyl and Fukushima were truly tragic, they are outliers in an otherwise low fatality industry.


## Deaths from Fossil Fuel Air Pollution
If we look at the aproximately 6,000 dead associated with those disasters, and we consider this the cost in human life of nuclear power, then we need to put this in its context of what other sources of energy cost in human life. The findings reveal that around 5 million people die each year from complications and illnesses associated with fossil fuel air pollution.

## Deaths by Energy Source
Next we can look at the rate at which different energy sources kill people. This is a count of lives lost per terawatt of electricity produced. Fossil Fuels are the worst in this measure, with coal in particular being the worst offender.

## Death Reduction and % from Nuclear
If we know the rate at which fossil fuels kill with pollution, then we can determine how many more people would have died had the energy produced by nuclear power been produced by fossil fuels instead, or looking at it from the other direction, the rate at whcih pollution deaths were reduced by the presence of nuclear power. Comparing this with the percentage of power a country recieves from nuclear reveals a strong correlation between a higher presence of nuclear energy in a county and the reduction of that countries air pollution deaths.


## Pollution and Power
The last visual in the presentation is an exploratory map that allows you to look at individual countries and see their stats such as percentage of power from nuclear, pollution deaths, pollution death reduction rate, and counts of lives saved by nuclear energy. This info is displayed in the tooltip, as well as a pie graph depicting the rate at which total pollution deaths were reduced by nuclear energy, and a line graph depicting pollution deaths through the last 20 years. 


## Tools
* Python
* Tableau

## Data Sources
- Air Pollution - Our World in Data
- What is the cleanest source of energy? - Our World in Data
- Energy Mix - Our World in Data
- World Population - Our World in Data
- https://thebulletin.org/2020/08/counting-the-dead-at-hiroshima-and-nagasaki/
- https://www.nature.com/articles/d41586-020-00794-y
- Nuclear Power Plants - Data.World
- Nuclear Power Accidents - Data.World