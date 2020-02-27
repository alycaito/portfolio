# Final Project

# Part I
## Outline

Title: Cash is King?

Summary: While the idea of giving cash without conditions to those in poverty has been controversial as a poverty-reduction strategy, emerging evidence supports that cash is effective at improving livelihoods and may produce better outcomes than traditional social programs. After all, who knows better what the poor needs than the poor themselves.

Goal: Debunk common myths about cash transfers and increase support for cash-based policies/charities.

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
![](https://alycaito.github.io/portfolio/project_outline.PNG)

![](https://alycaito.github.io/portfolio/project_sketch1.PNG)

![](https://alycaito.github.io/portfolio/project_sketch2.PNG)

![](https://alycaito.github.io/portfolio/project_sketch3.PNG)

## Data

The World Bank [data](https://alycaito.github.io/portfolio/RegionalTable_1.9.csv) from PovcalNet will be used to demonstrate how the number of poor people in Sub-Saharan Africa is increasing over time. The dataset contains poverty estimates (assuming the poverty level of $1.90 a day) by region from 2015 to 1981 (although, not all regions have data back to 1981). It includes the poverty rate, poverty gap, squared poverty gap, and total regional population. The total number of people below the poverty line can be calculated by multiplying the poverty rate by the total regional population. I plan on using this data to demonstrate how the poverty rate has been decreasing in Sub-Saharan Africa, but the total number of people in poverty is actually increasing. 

Source: World Bank PovcalNet.

The [data](https://alycaito.github.io/portfolio/UCT_FINAL_CLEAN.dta) from Shapiro and Haushofer's randomized control trial contains survey data from 1440 households in 120 villages from 2011 to 2013. This data is in .dta format, which I will analyze in Stata. They also provide their dofiles (code) for conducting their econometric analysis, which I will use to replicate their results and then capture those estimates in a separate data file. I will use this data to depict the results I explained in my outline for Myth 1.

Source: Haushofer, Johannes; Shapiro, Jeremy, 2017, "Replication Data for: The Short-Term Impact Of Unconditional Cash Transfers To The Poor: Experimental Evidence From Kenya", https://doi.org/10.7910/DVN/M2GAZN, Harvard Dataverse, V1

The Cash Benchmarking [study](https://alycaito.github.io/portfolio/Benchmarking.pdf)  that I would like to use to demonstrate how direct cash transfers perform in comparison to an integrated nutrition and WASH program (implemented by Catholic Relief Services) does not have a public dataset published. However, everything I need to create a visualization is in Tables 7 to 9. Therefore, I will construct a dataset with relevant outcome data from tables 7-9. What I would like to do is use the regression coefficients and standard deviations to demonstrate the impact of the two programs (and control group) on a variety of outcome variables. The dataset with the relevant regression coefficients is [here.](https://alycaito.github.io/portfolio/cash_benchmarking_data.xlsx)

McIntosh, C. & Zeitlin, A. (2018). Benchmarking a Child Nutrition Program against Cash: Experimental Evidence from Rwanda. Innovations for Poverty Action, Rwanda.

## Method and Medium
I will be using Shorthand to complete and present my final project. 

For the World Bank dataset and visualization, I currently intend to use the poverty rate and total number of people in poverty to create my visualization but I will experiment and see if some of the other measures included in my dataset yield interesting insights that I would like to present. The dataset contains data back to 1990 for Sub-Saharan Africa, but as part of my process I will determine how many years need to be included in my visualization to effectively present my point. 

I have created a few preliminary sketches to outline a few ideas I would like to present. As I continue to refine my story I will revise my original sketches and add new ones as I further explore the datasets.

For now, I have also kept the data story short. There is other data/studies that I could potentially tie in to bolster and/or clarify my message, but at this stage I will work with a streamlined version and then determine whether more details/data should be added. I intend to get feedback from my peers regarding the impactfulness and clarity of my story and plan to ask them what questions arise when they view my story. That will give me an idea if there are other gaps I need to fill in.

To help illustrate my data story, I plan to use images to show the context/who direct cash transfer programs aim to help.

# Part II

## Initial Wireframes 
Below is a link to the story sketches I intially drew and used for user feedback.

[Wireframes link](/wireframes.md)

## User Research

**Target Audience:** people interested in international development, people who are concerned about global poverty, people who want to donate to charitable organizations and want to make sure their contributions are maximized/used productively

**Approach to identifying respondents:** I decided to interview two friends in the Heinz public policy program. Since my project presents data on a policy, I felt that other policy students would be best positioned to give me useful feedback on my wireframes. They are also the closest to my target audience that is easily accessible to me. For the last person, I decided to interview my sister who is a marketing student. I wanted to make sure the story makes sense to someone outside the policy realm and she also has a different perspective on what might be interesting or confusing for users.

**Interview Script:** 
Hi, I'm looking for feedback on a data story for my Telling Stories with Data class. It will take 10 minutes for you to read through the story and discuss your thoughts on it. While reading through the story, please keep a mental note of things you like and don't like, as well as things you might find confusing. Afterwards, I will ask you a few follow-up questions.

1. What do you think is the purpose of this story? How would you summarize it?

2. What are your thoughts on evidence presented for unconditional cash transfers?

3. Do you have any questions that you feel the story does not address?

4. Is there anything else that is confusing about the story?

5. Please share your observations on the data visualizations. What worked well or caught your attention? Is there anything you would do differently?

**Feedback**

Below is a summary of the participants' feedback
![](https://alycaito.github.io/portfolio/feedback1.PNG)
![](https://alycaito.github.io/portfolio/feedback2.PNG)
![](https://alycaito.github.io/portfolio/feedback3.PNG)

**Overall Findings:** I found that all my participants understood the purpose of the story well, so in general I think the overall structure of the story is succeeding. The last graph that I used to express how cash performed better than another program was universally disliked, I will definitely rework this visualization to be more clear and impactful. From the feedback I think that I need to tie in more context. I had been intentionally keeping the text to a minimum, but in order to give the viewer a more detailed and clear picture of the story, I think there are some areas in which I need to include more explanation. However, I did receive feedback that the sections where there is a lot of text are less engaging, so I intend to add some photos to make those parts of the story more interesting. One of my participants mentioned it could be beneficial to add another myth if I have one, and I do, so I decided to add another. The visualization for it is still TBD, but I will use a multi-country study from UNICEF to illustrate my point.

## New Wireframes
I created these wireframes using Balsamiq after getting user feedback. There are some placeholders in the wireframes for some text to further describe the datasets that I have not yet fully fleshed out yet.

[Revised wireframes link](/wireframes_revised.md)

[Return to homepage](/portfolio)

# Part III

## Final Data Story

**Making the story work for my audience**
My audience is primarily 

**Reflection**

One thing that I decided to change from my wireframes to my final version was the infographic showing that 9 out of 10 people living in extreme poverty will be living in Sub-Saharan Africa by 2030. Originally I had planned to make a simple pie chart showing the same thing, but I think the new graphic is far more engaging and effective than a simple pie chart. 

The visualization that I struggled the most with is the final chart, which shows the results of the cash benchmarking study. My first sketches of these visualizations were pretty bad (in my opinion and my feedback participants') and only focused on one component of the study results. I wanted to tell an accurate story about the results of the study without having too much disjointed information that was hard to interpret. One of the things that I wasn't sure how to depict is that for some measures and programs, there is no statistically significant impact. It seemed liked when I got feedback from participants, that people did not like the confidence interval/error bars on the graph, so I decided I needed to find a way to show that information without it. I also couldn't leave that information out, because it is critical to understanding the study results. I finally settled on a bar chart, showing the percentage increase in the measures relative to the control group. Initially there was a 0% where there was "no impact" but I thought this could be confusing and decided to edit the image to make it say "no impact" instead. I think this visualization could probably still be improved, especially since I recognize it may not be entirely clear what the "no impact" text maps on to. For the bar colors in this chart, I decided to use green for cash and a darker green for the larger cash transfer, which I think is an intuitive color scheme.

In general, I think it was difficult for me to come up with visualizations for the results of the academic studies I highlighted. I wanted the visualizations to be clear and accurate, and so I think I had to sacrifice making them look more visually interesting. I wish I could have come up with a way to depict the study results in a way other than several bar charts, but when I tried to brainstorm how to do this without making the visualizations unnecessarily complicated or misleading I came up short. However, I am happy with the end results. For me, making sure the charts are easily interpretable and accurate representations of the data are the highest priorities, and if that means the visualizations are not the most eye-catching that's ok. My purpose was to present study results that the audience may never read otherwise in a digestable way, and I think I achieved that.

I had hoped to create another section in my data story including another "myth" but I unfortunately did not have the time to do so. I do think that this could have strengthened the narrative more, but I also believe that the primary message is still communicated clearly without it. 



[https://carnegiemellon.shorthandstories.com/cash-transfers-acaito/index.html]

<script src="https://embed.shorthand.com/embed_9.js"></script>
<div data-shorthand-embed="carnegiemellon.shorthandstories.com/cash-transfers-acaito/"><h1>Cash Transfers</h1><p>A Poverty Reduction Strategy in Sub-Saharan Africa?</p></div>
