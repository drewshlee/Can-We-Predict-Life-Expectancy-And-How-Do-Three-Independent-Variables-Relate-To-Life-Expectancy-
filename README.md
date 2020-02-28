# Can-We-Predict-Life-Expectancy-Life-Expectancy-and-its-relation-to-GDP-Capita-Population-School

## Background

In 1948, the World Health Organization was established to develop and maintain stringent public health standards across the world. In doing so, the WHO has determined that life expectancy is one of the most important measures of the overall health of community. Thus, for the WHO, life expectancy is not only an important health indicator that brings in profits and donations (shows that the WHO is doing its job), but also an indicator that shows that the WHO is doing their job in promoting and developing public health worldwide. 

With the aforementioned in mind, I wanted to investigate life expectancy under the lens of three independent variables that, without any analysis, would seem to affect life expectancy: GDP per Capita, Population, and Schooling. 

GDP per capita is the amount of output per person (simplified), and is typically an indicator of economic success, which usually leads to greater public health standards, and subsequently, life expectancy

With population size, I wanted to investigate this variable because a larger population size may either lead to greater public health standards (because of the sheer amount of people and great minds) and life expectancy, or may shorten life expectancy because of overpopulation and the rapid spread of disease. 

And lastly, education has always been a subject of hotly contested debate in regard to life expectancy. Some researchers claim that life expectancy is determined by money and social mobility, while others, and popular media/the WHO, claim that [education is of particular importance in regard to life expectancy](https://www.newscientist.com/article/2166833-more-education-is-what-makes-people-live-longer-not-more-money/)

To investigate these the relationships among these three variables and life expectancy, I took a look at [WHO Life Expectancy Data through Kaggle](https://www.kaggle.com/kumarajarshi/life-expectancy-who). 

Can life expectancy be predicted? How do GDP per capita, schooling, and population factor into life expectancy? 
How can we use linear regressions and WHO data to predict life expectancy and analyze the relationships between these three variables and life expectancy?

## Data Sources

1). [Life Expectancy (WHO)](https://www.kaggle.com/kumarajarshi/life-expectancy-who) - LifeExpectancyData.xlsx; Kaggle



## Sample Data Visualization

![Image of Schooling and Life Expectancy](https://github.com/drewshlee/Can-We-Predict-Life-Expectancy-Life-Expectancy-and-its-relation-to-GDP-Capita-Population-School/blob/master/SchoolingAndLifeExpectancy.JPG)


## Analysis

I will analyze: 
 - GDP per Capita's affect on Life Expectancy
- Schooling's affect on Life Expectancy
- All three variables and their affects on Life Expectancy

## Analysis Results

- Schooling shows the most clear-cut positive correlation. Life expectancy increased as schooling increased, for the most part. The WHO should either continue to focus on developing education in low life-expectancy countries, or should starting focusing on education to get the greatest return on time invested.

- GDP per Capita and Life expectancy don't show as clear of a correlation. Life expectancy seems to even out as GDP per capita continues to increase. However, life expectancy is generally lower at lower GDP per capita.

- Regression analysis shows that population is not significant in determining life expectancy

- Life expectancy prediction: Life Expectancy = 43.52 + .000088GDP/Capita + .00000000083Population + 2.07Schooling
If Population is not considered significant because of its high P value, 
Life Expectancy = 43.52 + .000088GDP/Capita + 2.07Schooling

-Developed and some selected developing countries showed improvements in life expectancy by means of increased GDP per capita and better education/schooling. 

## Some links regarding GDP per Capita, Schooling, and Life expectancy

- https://www.prb.org/us-educational-attainment-mortality/
- https://genus.springeropen.com/articles/10.1186/s41118-019-0055-0
- https://smartech.gatech.edu/bitstream/handle/1853/56031/effect_of_gdp_per_capita_on_national_life_expectancy.pdf
