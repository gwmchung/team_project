# Team Project

### [Jump directly to Team Project part2](#team_project2)

### Primary focus:

The project explores the relationship between net migration and fertility rates on the population growth in Canada between 1961 and 2021 using “Global Life Expectancy at Birth” dataset from Kaggle. This dataset consists of a comprehensive dataset of life expectancy trends.

### Relationships explored:

1.	The relationship between fertility rates and population growth. On further analysis , sex ratio at birth (male births per female births) and life expectancy at birth were also studied and would be benificial for the second part of the team project.
2.	The relationship between net migration and population growth 

For our project, net migration is the net total number of migrants during the period 1961 to 2021. Fertility rate is the number of children that a hypothetical female would have over the course of her life if she experienced the age-specific fertility rates observed in a given calendar year. Furthermore, population growth is the increase in the number of people in Canada during the period 1961 to 2021. 

### Approach taken:

Our group members shared their research topic preferences so we could fairly select a topic that was of interest to everyone. Once we had highlighted our interest in ‘Healthcare’, we explored various databases to select the suitable dataset for the project. After shortlisting a few datasets, we dived deeper into each one of them together to explore them further. We analysed the datasets and the variables within it to see their relevance to our topic of interest as well as the business context attached to it. 
After finalising out dataset “Global Life Expectancy at birth”, we divided the tasks within the team so every member contributes effectively in the area of their expertise.  

### Intended Audience:

1. Policymakers, government officials, and researchers interested in understanding how fertility rates impact population growth.
2. Immigration policymakers, urban planners, and economists interested in understanding the factors influencing population growth trends beyond net migration alone.

### Question our analysis is trying to answer:

1. How does the fertility rate (births per woman) affect population growth rates over time?
2. What are the correlations between fertility rates and population growth over different time periods?
3. What are the trends in population growth over a specific period?
4. To what extent does net migration contribute to population growth?

### Patterns/trends identified:

The regression analysis conducted on our dataset can be found in the Jupyter notebook in the 'report' section of our team-project repo.
The relationship between fertility rates and population growth depicted a significant positive correlation. This is shown by the high F-statistic and the low p-value in the regression analysis. The results are statistically significant and for each one-unit increase in the fertility rate, the population growth is expected to increase by 0.4807 units, assuming all other factors remain constant.
The relationship between net migration and population growth showed a low F-statistic and p-value in the regression analysis. It was predicted that this relationship is not statistically significant and therefore it cannot be said that the net migration has any effect on population growth. 

### Conclusions:

* Fertility rates have a clear and significant impact on population growth in Canada. This suggests that policies aimed at influencing fertility rates could have a substantial effect on the country's population dynamics.
* Net migration does not significantly impact population growth, based on our analysis. This finding highlights the importance of considering other factors when planning for population growth.

### Specific libraries or frameworks:

1. Pandas
2. NumPy
3. Statsmodels
4. Matplotlib
5. Jupyter Notebooks

## Contact
* **Gloria Chung** 
gwmchung@gmail.com
* **Namra Schazil** 
namraarif@live.com
* **Rajwinder Takk** 
rtakk@live.com
* **Yuliia Makushenko** 
yuliia.makushenko@gmail.com

## Folder Structure

### Project 1
```markdown
|-- data
|---- processed
|---- raw
|-- reports
|-- README.md
|-- .gitignore
```

* **Data:** Contains the raw, processed and final data. 
* **Reports:** Jupyter notebooks containing analysis code. 
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the Technical Facilitator

## Rules of Engagement

1. Open Communication
    - provide honest and direct feedback to others
    - express concern if obstacle arises, during meetings as well as while doing own's work

2. Treat each other with respect
    - make sure feedback is constructive and not just criticism
    - respect each other's personal schedule and recognize the needs of families

3. Autonomy and accountability
    - each member is responsible for managing their own tasks and deadlines
    - each member should proactively seek help or resources if they encounter obstacles

4. Concensus on important decisions
    - when issues come up during meetnigs, collectively decide and agree on an actionable plan
    - everyone must agree on important decisions like topic, dataset to use, and which analysis to use

## Feedback videos from team members

* [Gloria](https://youtu.be/E-LZbu2g2wY)
* [Rajwinder](https://youtu.be/M0dGDwzgb1Y)
* [Yuliia](https://www.youtube.com/watch?v=mJ5yiZzk_I8)
* [Namra](https://youtu.be/Mr_K2p4Yh2w?feature=shared)


## <a name="team_project2">Team Project 2</a>:

**What are the main goals and objectives of our visualization project?**

Goals:

- To visually represent the relationship between fertility rates and population growth in Canada.

- To highlight the impact of net migration on population growth.

- To make the analysis accessible and understandable to a broad audience, including policymakers and researchers.

Objectives:

- Provide clear and informative visualizations that convey key insights from the data.

- Support data-driven decision-making with visual evidence.

- Highlight significant trends, correlations, and anomalies in the data.


**How can we tailor the visualization to effectively communicate with our audience?**

- Use simple, clear, and concise visual elements to avoid overwhelming the audience.

- Include annotations and labels to highlight key data points and trends.

- Provide context with titles, subtitles, and descriptive captions.

- Use color schemes that are accessible and distinguishable for all viewers, including those with color vision deficiencies.

- Incorporate interactive elements where feasible to allow users to explore the data further.

**What type of visualization best suits our data and objectives (e.g., bar chart, scatter plot, heatmap)?**

For visualizing the data for all the different countries, choropleth map is best for visualizing our data and objectives because it allows us to see geographic representation, visualize spatial patterns, ease to compare, intuitive to interpret, relevant to decision-making, communicate complex data.

For visualizing the data for the trends in the population growth, birth rate, and net migration rate, a line graph is best.  All three simple lines of different colours, plotted on the same graph, clearly compares the trends of the three variables.  

**Are there any specific libraries or frameworks that are well-suited to our project requirements?**

Pandas, Matplotlib, Seaborn, Plotly, Plotly.express, Geopandas, Scikit-learn, Kaleido.


**How can we iterate on our design to address feedback and make iterative improvements?**

Iterating on a design based on feedback is a critical process for improving a visualisation. There are several steps that could be followed to incorporate feedback and make iterative improvements:
-	Feedback can be gathered from a diverse group of viewers who interact with the data visualisation. This can be done through surveys, usability testing or direct observation. The feedback can cover various aspects of data visualization such as usability issues, design flaws, data accuracy or aesthetic concerns. 
-	Once the feedback is gathered, it can be assessed to identify any common themes or recurring issues.  The impact of the feedback on the overall effectiveness of the data visualization can be studied especially focusing on usability or clarity.
-	The design of the data visualization can be updated based on prioritized feedback like redesigning elements, adjusting data representation, improving labels, refining visual aesthetics. 
-	The updated data visualizations should be retested for usability; and feedback should be gathered again to address new concerns. 
-	Based on the new feedback, the data visualisations could be adjusted to make iterative improvements. An important aspect of iterative improvement is to track and document the changes to understand the changes in the future. 


**What best practices can we follow to promote inclusivity and diversity in our visualization design?**

There are several steps that can be taken to make sure that the data visualisation in accessible to a large population overcoming the barrier of visual and hearing impairments:
-	Provision of alternative descriptive text means that people using screen readers can access the data easily.
-	Tactile or braille versions of data visualisations can be created which can be expensive but cater to the needs of people with visual impairments. Graphical and spatial visualisations with efforts for people with special needs allow greater accessibility. Failure to do so will prevent our visualisation to achieve the desired effect on all audience and in some cases will have a harmful effect by excluding them from important data. 
-	Data visualisations should provide information in a clear, concise, and easy to use format. Moreover, the information should be presented in a predictable and barrier-free ways that allow interactive opportunities for users. 
-	Colour Blindness Simulator should be used to check how colors are perceived by people with various types of colorblindness. WebAIM offers an online tool to check the contrast between two colors, so our choice of colors is not too bright and overwhelming for people with sensory issues and those on the autism spectrum. 
-	Viridis package can be used to make plots easier to read by those with colorblindness, and to maintain contrast so plots are readable in greyscale.
-	If we want to prevent replying solely on colors and patterns to present our visualisations, we should use clear data labels on individual data points or bars in a bar graph. Every visual element on the graph should be clearly described in a legend to reduce anxiety for our audiences. Certain typefaces and fonts are considered more accessible so should be considered when designing data visualisation.
-	To maximise the accessibility of our data visualisations, we can consider open access or Creative Commons licenses.

There are several aspects of data visualisations that can be considered when collecting and translating data into visuals forms to enhance inclusivity:
-	Including a range of data impacts the ways in which that data is later visualised for example a binary ‘gender’ variable means excluding nonbinary identities from our dataset. 
-	‘Underwater labour’ is the idea of behind the scenes work that goes into data visualisation and should therefore be acknowledged so that the contribution of those people is visible and valued. In the case of data visualisation, credit should be given to community organisers who facilitated data collection, designers creating color palletes for visualisation, technical writers, student research assistant, IT support staff and caregivers for children during project work etc. 
-	The data visualisation should be reproducible to understand and trace the data we see in graphics. 

**How can we ensure that our visualization accurately represents the underlying data without misleading or misinterpreting information?**

There are several key aspects that were considered to allow our visualisation to represent the data accurately which would be effective in communicating the intended message without misleading viewers:

-	Before proceeding with the visualisation, we took our time to thoroughly comprehend the dataset ‘Global Life expectancy at Birth’ and decode all the variables. After studying the variables, we chose the appropriate type of visualisation for example, a time series graph plots an aggregated value on a timeline and can be a good choice for quantitative variables. A choropleth map is a thematic map that is used to represent statisticak data using the color mapping symbology technique. 

-	We ensured that the axes on our graph are labeled clearly, and scales are selected appropriately to avoid misleading the audiences about the magnitude of difference of the variables. For example, our independent variables, net migration and birth rate had different scales and it was not the best choice to display them on the same y-axis so we utilised the max method to show each point as a ratio of the respective maximum point in the series. The transformed data was then plotted on the same axes to appreciate the trend between the independent variables and population growth.

-	Use of clear and descriptive labels, titles and legends in our data visualisation allowed viewers to understand and interpret the information correctly. Consistent color schemes (as well as grey scale to allow for visual impairments), fonts and styles were utilised to avoid data misinterpretation. For example, in our visualisation, distinct colors were used to show the relationship between net migration and population growth, and birth rate and population growth. This allows to direct the viewers’ attention to important aspects of the data and can clarify complex information. 


**Are there any privacy concerns or sensitive information that need to be addressed in our visualization?**

The Global Life expectancy data is relatively low risk in terms of privacy concerns but it’s always a good practice to handle all data with care and respect. 

-	The ‘Global Life expectancy at Birth’ dataset is aggregated at the country level rather than at an individual level which reduces the privacy and confidentiality concerns as it does not involve personal information about individuals. However, we still made sure that any data we used was truly anonymized and doesn’t include any sensitive and disintegrated details that could be traced back to the individuals. 

-	We obtained data for our visualisation from Kaggle which is a trusted open-source platform for public data and allows for its data usage for public analysis. Therefore, we minimised risk of data collection through unethical route and ensured that privacy regulations were respected in the process. The data is sourced from the World Bank which implements technical and organisational measures to protect personal data from unauthorised processing, as well as to prevent accidental loss, destruction, or damage.

-	The data was cleaned and represented correctly to the best of our knowledge and skills. No data points were altered in the processing stage to depict a true picture of the relationship between the variables studied in our project: net migration and population growth; and birth rate and population growth. Misrepresentation of data can harm groups or individuals and can also be an ethical concern.

-	The ‘Global life expectancy at birth’ dataset contains information about the life expectancy of male and female populations across different regions and income levels so careful consideration was given to generate visualisations which avoids reinforcing stereotypes or biases. 


** Feedback videos on part2 from team members
* [Gloria](https://youtu.be/cJTXSTIOAMk)
* [Rajwinder](https://youtu.be/sMFN9WzQ_1Y)
* [Yuliia](https://www.youtube.com/watch?v=jyKOGDvpE3o)
* [Namra](https://youtu.be/VbocgXb1x94?si=IqTHR12wApzvpO7c)
