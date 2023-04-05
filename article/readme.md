# Article
•	INTRODUCTION
Basically, a startup company is a young company with a business model that simply supports innovation. These companies are very pivotal as far as the development of a country is concerned. Thus, they primarily meet the demands of a growing economy. Hence, we can boldly conclude that the influx of such companies in a particular domain or ecosystem is a measure of the extent that domain will thrive. 

This project is to document a systematic approach to analyzing the Indian startup’s ecosystem annually using python from 2018 - 2021. This analysis follows the Cross Industry Standard Process for Data mining (CRIPS-DM) approach.

1.	Objectives:
The objective of this project is to give insights to key stakeholders, management to make informed decisions, and investors aiming to venture into the Indian startup ecosystem.  All of this can be possible by analyzing data on funding received by these companies from 2018 – 2021 as a standard measurement.

Furthermore, the project was validated using the hypothesis to test the dataset. Thus, technological and technological industries, are more likely to receive funding from investors.

## Hypothesis
Null Hypothesis: Investment in the Indian ecosystem is not biased towards any of the sectors

Altenate Hypothesis: Investments in the Indian ecosystem is biased towards at least one sector

## Questions
- Are start-ups located in specific areas more likely to succeed or to receive more financing than those located other areas?

-- From the plot above, it can be infered that the mean funding amount received by startups in Mumbai turns to be higher than that of the other cities in India. We can conclude that startups located in Mumbai are likey to get high funding than if they were located elswhere in India.

- Has the amount of investments in the ecosystem increased over the 4 year span (the datasets we are looking at), or has it decreased?

-- The amount of funding was approaximately same from the year 2018 to 2019, however, the funding amount had a sharp increase from 2019 and continued to increase in 2020. In 2021, the total funding amount fell back to almost the same level as it was in 2018. This is interesting because 2019 marks the begining of the deadly covid-19 pandemic which impacted sevral ecomies worlwide

- What is the median investment amount received by Indian startups at different stages of their growth?

-- From the visualization, it can be seen that companies at the Series -H stage seems to receive a higher funding amount than all other stages

- Does the nature of the industry has any impact on the amount of funding received?

-- from the visualization it obtained that the finance industry received more funding from 2018 to 2021.


- Which startup (s) had the highest rate/count of funding (this counts the startup that occured most but not with duplicate funding)

-- From the plot above, it can be seen that just within 4 years BharatePe company was able to secure 10 funding instances, making it the the highest amongst the companies which received multiple fundings.

# Hypothesis testing
Null Hypothesis
Companies whose headquaters are located in the Indian capital city, New delhi) receive more funding than that of those located other cities

Alternate Hypothesis
Companies whose headquaters are located in the Indian capital city, New delhi) does not necessarilly receive more funding than that of those located in other cities

To test the hypothesis, we will need to find out which city's startups received the highest funding. If this city is not New Delhi then we further need to find out the average funding received by startups in New Delhi and further compare it with the city with the highest funding.

the plot that visualizes the "Means of funding amounts per Top 15 Headquaters" in question four already shows that Mumbai is the leading City. to get a better sense of how much Mumbai is leading New Delhi, we will plot below the mean of all fundings in New Delhi