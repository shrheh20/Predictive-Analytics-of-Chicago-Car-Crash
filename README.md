# Predictive-Analytics-of-Chicago-Car-Crash

##Abstract:
This project focuses on leveraging the Chicago Traffic Crashes dataset available on Kaggle, with the primary objective of formulating actionable strategies to reduce the incidence of road accidents in Chicago significantly. Our approach involves an in-depth analysis of diverse parameters, including time, weather conditions, vehicle types, and driver behavior, to uncover underlying patterns and factors contributing to road accidents. A significant aspect of our methodology is the utilization of Tableau for creating dynamic and insightful visualizations. These visualizations not only aid in a more intuitive understanding of the data but also highlight critical trends and correlations in a user-friendly manner. Through this combination of rigorous statistical analysis and sophisticated data visualization techniques, the study aims to provide a set of evidence-based recommendations. These recommendations are intended to guide policymakers and stakeholders in implementing effective measures for enhancing road safety and substantially mitigating the risks associated with traffic in Chicago. The ultimate goal of this research is to inform and drive changes that lead to a notable reduction in traffic-related incidents, thereby making Chicago's roads safer for all users.

##Introduction:
Our report delves into the heart of traffic accident data from Chicago, offering a detailed exploration of critical factors such as crash types, damage, road conditions, and control devices. As we dissect the Chicago car crash dataset, we aim to provide a nuanced understanding of the dynamics influencing these incidents.
On a global scale, traffic accidents emerge as a pressing concern, as highlighted by the World Health Organization's 2023 report, revealing an annual toll of over 1.3 million lives and marking the leading cause of death for those aged 5 to 29. This global perspective amplifies the significance of our analysis, contributing not only to local insights but also to the broader discourse on road safety.
Within the context of Chicago, a 2023 report starkly outlines the gravity of the situation, with approximately 19,515 lives lost in car accidents within the first six months. This alarming statistic propels our focus on Chicago, turning the lens toward local challenges and prompting an exploration of specific patterns, contributing factors, and potential interventions tailored to the city's needs.
Our work centers on meticulously examining the dataset, employing visualization to make data accessible and comprehensible. By showcasing critical trends, we aim to invite all stakeholders to engage with and comprehend the complexities of traffic accidents in Chicago.
This report is a testament to our commitment to unraveling the layers of information within the dataset. In the subsequent sections, we present our analysis, combining visual and analytical perspectives on various factors related to traffic accidents. The report concludes with a thoughtful discussion of the implications of our findings and potential avenues for future research, highlighting the ongoing need for a safer and more informed approach to road safety.

##Approach
In this study, we imported the cleaned and preprocessed dataset into Tableau, a leading data visualization tool known for its robust analytics capabilities. Our primary objective was to conduct a comprehensive analysis that would reveal underlying patterns in the data and offer a nuanced understanding of the various dynamics of road accidents in Chicago.
The process began with creating intricate dashboards in Tableau, each meticulously designed to focus on specific aspects of the traffic data. These dashboards encompassed a range of analyses, including:
Crash Frequency Analysis: We utilized temporal data to map out the frequency of accidents over time. This included analyzing trends across different times, days of the week, and months of the year. Histograms, line charts, and heat maps were employed to visualize these trends, providing insights into when and how frequently accidents occur.
Identification of Top Reasons for Crashes: Leveraging the categorical data within the dataset, we identified the most common reasons cited for crashes. This involved using bar charts to represent and compare the prevalence of various factors such as speeding, distracted driving, and violation of traffic signals.
Severity Analysis: We conducted a detailed examination of the severity of accidents. This involved categorizing accidents based on severity and analyzing the distribution and underlying causes of severe accidents versus minor ones. Tables and bar plots were used to illustrate the severity levels' range and concentration.
Role of External Factors: An exploration of how external factors like weather conditions, road surface conditions, and traffic control devices influence accident occurrences and severity was undertaken. For this, we used bar plots to identify this relation.
Our approach was characterized by iterative refinement and validation. Each dashboard and visualization underwent rigorous testing to ensure accuracy and clarity. By harnessing the power of Tableau's visualization and analytical tools, we aimed to present a clear, detailed, and multi-dimensional picture of the traffic accident scenario in Chicago

Dashboard 1 - Overview:

The dashboard offers an overview of traffic crashes in Chicago, encapsulating various dimensions of the data through a series of interlinked visualizations.
Heatmap of Crashes by Beat: At the dashboard's core is a heat map that visually represents accident hotspots across the city. The color gradations indicate the concentration of crashes, with warmer colors denoting higher frequencies. This visualization identifies areas with higher traffic incidents, which could be critical for deploying resources and safety measures.
Number of Accidents by Year: Adjacent to the heat map is a bar chart that shows the annual distribution of accidents from 2016 to 2019, allowing viewers to discern trends over time. The bar

chart reveals a significant increase in accidents from 2016 to 2018, followed by a sharp decrease in 2019. This could indicate the impact of interventions or changes in reporting over the years.
Top 10 Beats Prone to Accidents: Below the annual trends, there is a Treemap that breaks down the accident data by police beats, which are specific areas patrolled by police officers. The size of each box represents the relative number of accidents, with different colors signifying different beats. The visualization highlights the beats with the highest number of accidents, thus drawing attention to regions where traffic safety measures may be most urgently needed.
Severity of Injuries: The final element of the dashboard is a highlight table that details the types of injuries and their occurrences in accidents. The chart categorizes injuries from fatal to non-incapacitating, including a category for incidents where no injuries were reported. This table provides insights into the human impact of traffic crashes and can be instrumental for healthcare and emergency services planning.
The dashboard provides several insights into the number of crashes by beat and the severity of injuries.
•
The areas with the most crashes are typically located downtown and on major highways. This is likely due to the increased volume of traffic in these areas.
•
The top 10 Beats prone to accidents are 1834, 114, 122, 1831, 813, 1833, 1232, 815, 331, and 2413.
•
The most common type of injury from traffic accidents is no indication of injury, followed by Non incapacitating injury, reported, not evident, incapacitating injury, and fatal injury.
•
Overall, this dashboard aims to provide a comprehensive at-a-glance view of the traffic crash data, which can be instrumental for policymakers, urban planners, and emergency response teams in identifying trends, allocating resources, and formulating strategies to improve road safety in Chicago.
Overall, this dashboard aims to provide a comprehensive at-a-glance view of the traffic crash data, which can be instrumental for policymakers, urban planners, and emergency response teams in identifying trends, allocating resources, and formulating strategies to improve road safety in Chicago.
7
Dashboard 2 - Fatal Injuries Analysis:
In the "Fatal Injuries Analysis" dashboard, we present a comprehensive analysis focused on the contributing factors to traffic accidents in Chicago that result in fatalities. The section offer insights into the causative elements, the conditions under which accidents occur, and their correlation with the severity of injuries sustained.
Top 10 Factors causing accidents: This is a key feature in our analysis. It clearly indicates that 'following too closely' and 'failing to yield right-of-way' are the predominant factors contributing to road accidents. This visualization effectively communicates the hierarchy of factors, allowing for an immediate grasp of the primary behaviors most frequently associated with accidents on the road.
8
Number of Fatal Injuries due to lighting conditions: Adjacent to the treemap, the bar chart conveys a surprising trend: most fatal injuries occur during daylight. These finding challenges common perceptions suggests that visibility may not be the sole factor in the severity of accidents. This points further investigation into the behavioral aspects contributing to these incidents. Number of fatal injuries based on weather conditions: The graph shows a high number of fatalities associated with clear weather. This highlights a critical area for road safety attention, as it suggests that drivers may be more prone to risk-taking or less vigilant under favorable weather conditions.
Number of injuries associated with road conditions: The graph indicates that dry road conditions see the highest number of fatal injuries. This counterintuitive data point suggests that there may be a false sense of security on dry roads, which could lead to more dangerous driving behaviors.
The dashboard provides several insights into the causes of accident and top 3 factors causing accidents are all related to driver error, so it is important to drive safely and follow all traffic laws.
•
The number of fatal injuries due to following too closely is significantly higher than the number of fatal injuries due to any other factor. This suggests that following too closely is a very serious problem, and drivers need to be more aware of this danger.
•
The number of fatal injuries due to improper backing is also significant. This suggests that drivers need to be more careful when backing up their vehicles.
•
The number of fatal injuries due to failing to yield the right-of-way is also significant. This suggests that drivers need to be more aware of other vehicles and pedestrians on the road.
•
The number of fatal injuries due to dry road conditions see the highest number of fatal injuries. This counterintuitive data point suggests that there may be a false sense of security on dry roads, which could lead to more dangerous driving behaviors.
These visualizations collectively guide our understanding of where safety interventions may be most urgently needed, especially in addressing human errors and challenging assumptions about 'safe' driving conditions. Our findings underscore the importance of continuous monitoring and analysis of traffic accident data to improve road safety measures. Through this dashboard, we provide a critical tool for stakeholders aiming to reduce the risks related to fatal road accidents.
9
Dashboard 3 - Traffic Analysis:
The "Traffic Analysis" dashboard provides a multi-dimensional view of traffic accidents in Chicago, examining the interplay between time of day, traffic control devices, types of roadways, and the resulting injuries.
At the forefront, the area chart "Number of accidents per hour by year" displays the distribution of accidents throughout the day, segmented by year. The peaks and troughs of this chart likely correspond to typical rush hour periods, revealing critical times when accidents are most frequent. The layering by year allows for an at-a-glance comparison across time, showing trends and changes in accident occurrence throughout different times of the day.
10
Adjacent to this, the stacked bar chart "Type of injuries on different trafficway types" categorizes accidents by the severity of injuries and the type of trafficway. This visual representation enables an immediate comparison of the injury severity across various road types, such as curves, ramps, and alleys, providing insights into potentially hazardous trafficway alignments that could benefit from safety improvements.
Below these charts, the dashboard presents two bar graphs providing a granular look at the context of accidents. The "Number of Accidents based on Traffic Device Condition" graph breaks down the frequency of accidents in relation to the operational status of traffic control devices. It is apparent that a significant number of accidents occur at locations with no controls, followed by properly functioning traffic signals, which might indicate areas where traffic control measures could be enhanced or where driver awareness could be increased.
Together, these visualizations offer a comprehensive understanding of the factors contributing to traffic accidents and their outcomes. The data presented could be instrumental for city planners and traffic safety officials in prioritizing interventions and allocating resources to improve road safety in Chicago.
Here are some additional insights from the data:
•
The number of accidents is highest during the morning and evening rush hours, and lowest during the middle of the day. This is likely due to the increased volume of traffic during these times.
•
The number of accidents has been decreasing over time. This is likely due to a number of factors, including improved safety features in vehicles, better road design, and increased awareness of traffic safety.
•
Alignment accidents are the most common type of accident. This is likely due to the fact that alignment accidents can occur on any type of road, and they can be caused by a variety of factors, such as driver error, road conditions, and weather.
•
Curve accidents are the second most common type of accident. This is likely due to the fact that curve accidents can be difficult to control, and they can be caused by a variety of factors, such as driver error, speed, and road conditions.
•
The most severe injuries from traffic accidents are fatal injuries. This is a reminder of the importance of driving safely and following all traffic laws.
11
Challenges Faced:
Data Completeness: While the dataset was clean, ensuring all relevant data was present posed challenges for certain parameters, impacting the depth of analysis.
Variable Interpretation: Interpreting the impact of certain variables on crash severity required careful consideration, especially when factors overlapped.
Temporal Analysis: Understanding temporal patterns faced challenges due to the dynamic nature of traffic conditions, requiring robust statistical methods
Limited Time-series: Limitations in the number of accidents recorded by year restricted us from forecasting future accidents rates.
Conclusion:
The project has culminated in a detailed examination of the traffic accident scenario in Chicago, providing a dataset that could be valuable for policymakers, urban planners, and road safety advocates. The study utilized Tableau for data visualization, aiming to render complex datasets more accessible and to facilitate various perspectives for dataset exploration. This approach allows for a multifaceted understanding of the data, potentially uncovering insights that might not be as apparent in traditional analyses.
The visualizations developed in this study are designed to offer an interface for stakeholders to explore the dataset. They aim to present the data in a format that can be easily navigated and understood, which may assist decision-makers in formulating traffic management and safety strategies. The interactive nature of these dashboards also provides the flexibility to delve into specific aspects of the data as per the users' requirements in urban planning and road safety improvements.
Moreover, the findings from this analysis contribute to the ongoing discourse on urban mobility challenges, particularly in densely populated cities like Chicago. The study highlights areas where
12
targeted interventions might be beneficial, such as identifying high-risk zones, analyzing the impact of environmental factors on accident rates, and examining patterns in accident severity.
The methodologies and insights derived from this project might also be applicable to other urban settings, suggesting a potential model for similar traffic safety analyses. This project demonstrates the utility of data-driven analysis as a tool in creating safer and more efficient urban transportation networks.
Overall, this project provides a comprehensive analysis of Chicago's traffic accidents, emphasizing the crucial role of safety approaches in urban planning. With urban landscapes evolving, continuous analysis and adaptive strategies are essential for ensuring the safety of city dwellers, making informed decisions, and shaping proactive measures.
