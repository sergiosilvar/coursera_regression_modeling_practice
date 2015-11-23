# Gapminder dataset

## Sample
The [dataset](./data/gapminder.csv) used in this study is a donation of [Gapminder](http://www.gapminder.org/about-gapminder/) exclusively for this specialization. Basically, is a sub selection of 15 out of more than 200 variables available at their site about economic, military, social and health subjects from 213 United Nation countries. The purpose of this organization is provide statistical content to produce the [Gapminder World](http://www.gapminder.org/world/) and Gapminder Countries softwares, which animation enhances the comprehension of the time analysis over the variables, and creating videos, Flash presentations and PDF charts showing major global development trends with animated statistics and colorful graphics.

For this study, from the 15 variables available for countries, I'll use one as the response variable and four as the explanatory:

* Response variable: Life expectancy
* Explanatory variables: Income per person, Consumption of alcohol, CO2 emissions and Employ rate

The goal is to verify the relationship of the explanatory variables to the response. The theoretical assumption is that a high income result in high life expectancy, as the population can spend in food, health activities, leisure and fulfill retirement projects. The employ rate can elevate the life expectancy allowing more people to receive wages and spend it as described above. The consumption of alcohol can be view in two perspectives: the positive perspective is this consumption being interpreted as leisure time and economic power to spend in this product. The negative perspective is alcohol being used as drug in poor countries, like an addictive behavior. Finally, the CO2 emissions is assumed to increment the life expectancy in a way the higher the CO2 emission, the more economic developed the country is, with employ en wages rates in high perspective.

## Procedures
The data are collected by Gapminder staff from [Institute for Health Metrics and Evaluation](http://www.healthdata.org/), [US	Census	Bureau’s	International	Database](https://www.census.gov/population/international/data/idb/informationGateway.php),	[United	Nations
Statistics	Division](http://unstats.un.org/unsd/default.htm),	and	the	[World	Bank](http://data.worldbank.org/). So, there isn't to much to describe here, as the data is in essence collected by other institutions.

## Measures
This dataset offers variables from social, economic, military and health issues about the countries, as described below:

1. Life expectancy
>  2011 life expectancy at birth (years)
The average number of years a newborn child would live if current
mortality patterns were to stay the same.


1. Income per person
> 2010 Gross Domestic Product per capita in constant 2000 US$. The
inflation but not the differences in the cost of living between countries
has been taken into account.

1. Consumption of alcohol
> 2008 alcohol consumption per adult (age 15+), litres.
Recorded and estimated average alcohol consumption, adult (15+) per
capita consumption in litres pure alcohol.

1. CO2 emissions
> 2006 cumulative CO2 emission (metric tons), Total amount of CO2
emission in metric tons since 1751.

1. Employ rate
> 2007 total employees age 15+ (% of population)
Percentage of total population, age above 15, that has been employed
during the given year.

An overview of the descriptive analysis is given in the table below. The total of observations is 213 contries, but some have missing values. The "count" row gives the number of non missing values:

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>lifeexpectancy</th>
      <th>incomeperperson</th>
      <th>alcconsumption</th>
      <th>co2emissions</th>
      <th>employrate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>191.000000</td>
      <td>190.000000</td>
      <td>187.000000</td>
      <td>2.000000e+02</td>
      <td>178.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>69.753524</td>
      <td>8740.966076</td>
      <td>6.689412</td>
      <td>5.033262e+09</td>
      <td>58.635955</td>
    </tr>
    <tr>
      <th>std</th>
      <td>9.708621</td>
      <td>14262.809083</td>
      <td>4.899617</td>
      <td>2.573812e+10</td>
      <td>10.519454</td>
    </tr>
    <tr>
      <th>min</th>
      <td>47.794000</td>
      <td>103.775857</td>
      <td>0.030000</td>
      <td>1.320000e+05</td>
      <td>32.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>64.447000</td>
      <td>748.245151</td>
      <td>2.625000</td>
      <td>3.484617e+07</td>
      <td>51.225000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>73.131000</td>
      <td>2553.496056</td>
      <td>5.920000</td>
      <td>1.859018e+08</td>
      <td>58.699999</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>76.593000</td>
      <td>9379.891165</td>
      <td>9.925000</td>
      <td>1.846084e+09</td>
      <td>64.975000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>83.394000</td>
      <td>105147.437697</td>
      <td>23.010000</td>
      <td>3.342209e+11</td>
      <td>83.199997</td>
    </tr>
  </tbody>
</table>

The management of the missing values will be defined in the next assignment because for now were no able to foresee  the best way to address this issue, replace missing values or drop the country.

<!--

1. Rate of armed forces
> Armed forces personnel (% of total labor force) Work

1. Breast cancer per 100th
> 2002 breast cancer new cases per 100,000 female
Number of new cases of breast cancer in 100,000 female residents
during the certain year.


1. Female employ rate
> 2007 female employees age 15+ (% of population)
Percentage of female population, age above 15, that has been
employed during the given year.


1. HIV rate
> 2009 estimated HIV Prevalence % - (Ages 15-49)
Estimated number of people living with HIV per 100 population of age
group 15-49.

1. Internet use rate
>  2010 Internet users (per 100 people)
Internet users are people with access to the worldwide network.

-->
