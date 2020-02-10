# Final Project
## Outline

Title: Cash is King?

Summary:

#### Story Structure
Problem: While the poverty rate in Africa has slowly decreased, the number of extremely poor continues to rise. (show with visualization)

Potential solution: New policy solutions should be considered: direct transfers of cash to the poor - without any conditions or suggestions on how it should be spent - are potentially a productive and cost-effective way to help people out of poverty.

Myth 1 - Poor people who are given cash assistance with no conditions will waste it on temptation goods or luxury items.
- A study in Kenya of an unconditional cash transfer found that household consumption increased across a range of good such as food, medical and educational expenses, and social events but there was no increased expenditure on temptation goods like alcohol or tobacco. (depict in visualization)
- The study also showed that participating households increased investments (livestock, furniture, metal roofs) by 58% (US$272) Households also increased investments in income-generating activities and revenues from these activities increased by 34%.


Myth 2 - Cash interventions aren't as impactful as traditional social programs as a poverty reduction strategy.
- A Cash benchmarking study in Rwanda (randomized control trial) showed that cash transfers were more effective than and integrated nutrition and WASH (Water, Sanitation, and Hygiene) program. Neither had a significant impact on nutrition or child growth outcomes, but the cash transfer decreased child mortality by 70% and helped participants pay down debt. I will depict the exact results/comparisons in a visualization.
  
Call to action: Support direct cash transfers to the poor. Donate to the charity GiveDirectly that is providing cash transfers to the world's poorest and is involved in multiple rigorous studies to evaluate the long-term impact of cash transfers.

## Sketches

## Data

The World Bank [data](https://alycaito.github.io/portfolio/RegionalTable_1.9.csv) from PovcalNet will be used to demonstrate how the number of poor people in Sub-Saharan Africa is increasing over time. The dataset contains poverty estimates (assuming the poverty level of $1.90 a day) by region from 2015 to 1981 (although, not all regions have data back to 1981). It includes the poverty rate, poverty gap, squared poverty gap, and total regional population. The total number of people below the poverty line can be calculated by multiplying the poverty rate by the total regional population. I plan on using this data to demonstrate how the poverty rate has been decreasing in Sub-Saharan Africa, but the total number of people in poverty is actually increasing. 

Source: World Bank PovcalNet.

The [data](https://alycaito.github.io/portfolio/UCT_FINAL_CLEAN.dta) from Shapiro and Haushofer's randomized control trial contains survey data from 1440 households in 120 villages from 2011 to 2013. This data is in .dta format, which I will analyze in Stata. They also provide their dofiles (code) for conducting their econometric analysis, which I will use to replicate their results and then capture those estimates in a separate data file. I will use this data to depict the results I explained in my outline for Myth 1.

Source: Haushofer, Johannes; Shapiro, Jeremy, 2017, "Replication Data for: The Short-Term Impact Of Unconditional Cash Transfers To The Poor: Experimental Evidence From Kenya", https://doi.org/10.7910/DVN/M2GAZN, Harvard Dataverse, V1

The Cash Benchmarking [study](https://alycaito.github.io/portfolio/Benchmarking.pdf)  that I would like to use to demonstrate how direct cash transfers perform in comparison to an integrated nutrition and WASH program (implemented by Catholic Relief Services) does not have a public dataset published. However, everything I need to create a visualization is in Tables 7 to 9. Therefore, I will construct a dataset with relevant outcome data from tables 7-9. What I would like to do is use the regression coefficients and standard deviations to demonstrate the impact of the two programs (and control group) on a variety of outcome variables. 

McIntosh, C. & Zeitlin, A. (2018). Benchmarking a Child Nutrition Program against Cash: Experimental Evidence from Rwanda. Innovations for Poverty Action, Rwanda.

## Method and Medium
I will be using Shorthand to complete and present my final project. 

For the World Bank dataset and visualization, I currently intend to use the poverty rate and total number of people in poverty to create my visualization but I will experiment and see if some of the other measures included in my dataset yield interesting insights that I would like to present. The dataset contains data back to 1990 for Sub-Saharan Africa, but as part of my process I will determine how many years need to be included in my visualization to effectively present my point. 

For now, I have also kept the data story short. There is other data/studies that I could potentially tie in to bolster and/or clarify my message, but at this stage I will work with a streamlined version and then determine whether more details/data should be added. I intend to get feedback from my peers regarding the impactfulness and clarity of my story and plan to ask them what questions arise when they view my story. That will give me an idea if there are other gaps I need to fill in.

To help illustrate my data story, I plan to use images such as the one below to show the context/who direct cash transfer programs aim to help.

![](https://alycaito.github.io/portfolio/GettyImages_951670148.0.webp)
An outdoor produce market in Gisakura Village, Rwanda. UIG via Getty Images

[Return to homepage](/portfolio)
