**# Dsci-5260**
 chicago Traffic crash 
 # Research Project
## Description
This repository contains:
- **Research Paper:** A Word document with research details.
- **Code:** A Google Colab notebook implementing the project.
#Data set :
https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/about_data

**Abstract **

This study takes a closer look at traffic accidents in Chicago, with a special focus on pedestrian and bicycle safety. The goal is to uncover patterns and factors behind these accidents to create more effective safety measures. The majority of crashes, including rear-end collisions, turning accidents, and collisions with parked automobiles, occur in moderate speed zones, particularly those with speed restrictions between 20 and 40 mph. Due to the high volume of vehicles, bikers, and pedestrians in these regions, encounters and accidents occur frequently. Although there are fewer incidents in low-speed zones (such as residential or school neighbourhoods), vulnerable road users, such as cyclists and children, are frequently involved. However, collisions at high-speed zones are more serious but less common. Compared to regions with only stop or yield signs, traffic signals significantly improve road safety by lowering the frequency and intensity of collisions. The study also investigates how weather and time of the week affect collisions. Thursdays have the most collisions, but weekends have fewer collisions but a higher likelihood of serious ones, probably as a result of riskier driving practices like speeding or intoxicated driving. Unexpectedly, weather also affects accidents. The majority of collisions occur at speed limits of 25 to 30 mph, which are typically in cities. This emphasizes the need for improved pedestrian crossing, signs, and traffic calming techniques in these congested regions. 
Using data visualizations like box plot and heatmaps the study also identifies critical trends, outliers, and correlations. By analyzing these patterns, the research offers practical insights to help reduce crashes, injuries and fatalities while improving traffic flow in Chicago’s busy streets.

#RESEARCH OBJECTIVE 
This research aims to measure the efficiency of presently implemented safety measures and determine the influence of the environment on the occurrence of accidents and the rates at which the accidents occur, as well as the time of day, weather conditions, and road surface characteristics. Traffic accidents are the subject of a broad literature review concerning several aspects of road safety; however, the principal focus of the study is on pedestrian and bicycle safety in Chicago. If the causes of specific types of crashes, road structures, danger zones, and specific crash patterns are analyzed, people can understand the reasons behind the accidents. This approach will allow the successful creation of targeted and effective safety interventions, upgrades, designs, and policies relevant to decreasing transportation incidents in Chicago. In achieving these objectives, this research strives to improve strategies for traffic safety, reduce crashes, injuries, and fatalities, and address traffic system congestion in Chicago's transportation modes. 

#RESEARCH QUESTIONS
1. What is the relationship between speed limits and crash types?
2.a. How effective are traffic signals in reducing crashes compared to other control devices?
   b. How does a traffic control device affect the chances of rear-end collisions?
3. How do crash severity and contributory causes vary by time and day of the week?
4. Effects of Weather on Motor Vehicle Accidents: How do weather characteristics affect crash rates and severity?

 #Conclusion
This study provided a comprehensive analysis of traffic collisions in Chicago, focusing on understanding the factors contributing to accidents and their severity while evaluating the effectiveness of existing safety measures. The study examined important facets of traffic safety, such as the connection between speed limit and crash types, the function of traffic signals, the effects of time and environment on crash severity, and the crucial role of weather, using a larger dataset from the Chicago police department’s E-crash reporting system. 
A major finding highlighted in the study is the prevalence of crash zones in moderate speed zones (20mph-40mph), where there are a lot of vehicles, pedestrians, and bicycles interacting with one another. Even though there were fewer collisions at higher speed limits (50mph or more). They frequently led to more dire consequences. Lower speed restrictions in residential and school zones resulted in fewer incidents, but they frequently affected vulnerable groups like children and pedestrians highlighting the need for safety measures in these locations.
Compared to regions controlled by other traffic control systems, traffic signals dramatically decreased crash rates and accident severity, making them an essential safety component. Rear-end crashes are more frequent but typically less severe in non-signalized zones, according to the study. 
Curiously, although signals lower the number of crashes overall, they may marginally raise the percentage of serious incidents, maybe as a result of sudden braking or misunderstanding amongst drivers at junctions. Additionally , behavioural and temporal patterns were important. The most crashes occur on Thursdays, whereas the chance of serious accidents was higher on weekends, even though there were fewer crashes overall. Risky driving practices like speeding and drunk driving were shown to be possible causes of this development. Weather also has a significant role; rainy conditions raised the percentage of severe collisions, underscoring the difficulties of wet roads, while clear weather saw the most accidents, primarily as a result of increased traffic volume and speed. 
Several machine learning methods were assessed for their capacity to forecast crash severity from a modelling standpoint, because of its low recall logistic regression has  trouble detecting serious accidents, although it did well in terms of precision and accuracy. For severe cases, the decision tree showed superior recall more successfully recording crucial instances. But the random forest method fared better than both the models, striking a good balance between accuracy, recall, and precision. Model performance was further improved by using SMOTE especially when it came to forecasting serious but infrequent accidents.  These results allow for the  formulation of a number of recommendations. It is essential to upgrade the infrastructure with bike lanes, improved pedestrian crossing and traffic calming techniques in moderate speed zones. Accident hazards can be considerably reduced by increasing the use of traffic lights in high risk regions; safety results can be further enhanced by policy interventions such as targeted driver education programs and tougher enforcement on weekends and in inclement weather. 
Further studies should examine how to apply sophisticated ensemble learning algorithms to improve predictive skills and how to integrate real time weather and traffic data for dynamic risk assessment.  The city of Chicago can significantly reduce traffic accidents, fatalities, and create safer streets for all the road users by putting these policies into practice. This study emphasises how crucial data driven decision making is in the design of urban safety and offers a strong basis for ongoing initiatives to enhance transportation safety.  


#Recommendations: 
Actionable and practical suggestions centre on specific infrastructure upgrades, legislative modifications, and public awareness campaigns to address the significant problem of traffic collisions in Chicago. Improving bike lanes, crosswalks, and signs for pedestrians and cyclists in moderate speed zones can greatly lower the frequency of frequent crash types such turning and rear-end collisions, another crucial step is to increase the usage of traffic signals in high-risk locations while maximising their timing to reduce serious collisions. Lawmakers ought to impose more stringent speed limits and encourage cautious driving on weekends and in inclement weather, when there is a greater chance of serious collision. Campaign for education can raise driver's awareness of safe driving habits, especially in residential areas and at crossroads. These programs could not consist of media advertising, community workshops and media campaigns. 
Additionally leveraging real-time data from traffic and weather systems to adapt safety measures dynamically and using machine learning models to predict and mitigate risks proactively can ensure resources are allocated where they are needed the most. These measures if implemented strategically can result in safer roads and considerable decrease in traffic-related fatalities and injuries.  


#Limitations:
•Data Imbalance: Severe crashes are underrepresented.
•Temporal Scope: Post-2017 trends might not reflect pre-existing crash dynamics.
•Reporting Bias: Self-reported crashes might exclude unreported incidents.


#LIST OF REFERENCES
Admin. & Admin. (2024, September 19). Who causes more car accidents, men or women? | Malman Law. Malman Law. 
https://www.malmanlaw.com/malman-law-injury-blog/who-causes-more-car-accidents-men-or-women/
 
Accident Analysis & Prevention | Vol 43, Issue 1, Pages 1-494 (January 2011) | 	ScienceDirect.com by Elsevier. (n.d.). 
       https://www.sciencedirect.com/journal/accident-analysis-and-prevention/vol/43/issue/1
 
Kristianssen, A., Andersson, R., Belin, M., & Nilsen, P. (2017). Swedish Vision Zero policies for safety: A comparative policy content analysis. Safety Science, 103, 260–269.      
	https://doi.org/10.1016/j.ssci.2017.11.005 
   
Khayesi, M. (2006), February,  The Handbook of Road Safety Measures.    https://pmc.ncbi.nlm.nih.gov/articles/PMC2563494/ 
 
Ma, Y., Xu, J., Gao, C., Mu, M., E, G., & Gu, C. (2022). Review of research on road traffic operation risk prevention and control. International Journal of Environmental Research and Public Health, 19(19), 12115.
             https://doi.org/10.3390/ijerph191912115 
 
Maslamani, Y. A. (n.d.). Effect of the Structured Traffic Education Program (STEP) on knowledge and commitment toward traffic rules in the first year of legal driving in Saudi Arabia. Informit. 
https://search.informit.org/doi/abs/10.3316/informit.T2024060200001990074894717
  
NHTSA estimates traffic fatalities continued to decline in the first quarter of 2024. (2024, June 24). NHTSA.
        	https://www.nhtsa.gov/press-releases/2024-Q1-traffic-fatality-estimates
 
Ryan. (2018, July 31). What are the major contributing factors to traffic accidents? The   law offices of OEB. OEB Law, PLLC. 
 https://www.wreckintoacheck.com/faqs/what-are-the-major-contributing-factors-to-traffic-accidents/
 
World Health Organization: WHO. (2019, October 2). Road safety. 
https://www.who.int/health-topics/road-safety#tab=tab_1
 
World Health Organization: WHO. (2023, December 13). Road traffic injuries.     	https://www.who.int/news-room/fact-sheets/detail/road-traffic-injuries
 
Will crash experience affect the driver’s behavior? An observation and analysis on time headway variation before and after a traffic crash. (n.d.). TUP Journals & Magazine IEEEXplore. 
https://ieeexplore.ieee.org/document/8954865/citations#citations


