# Airlines-Delay-and-Cancellation-Exploration
# Dataset
This project explores a dataset that reports flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from January 2003 to April 2023.

The dataset has 338371 flight details with 21 features. The data ranges from January 2003 to April 2023.

The variables in the dataset contains information about Airline' name, carrier, cancellation reason, delay (and cause of delay), etc.

Also, a flight is considered delayed when its arrival delay is longer than 15 minutes.

# Summary of Findings
- Late aircraft and NAS are primary reasons for cancellations, while security causes negligible cancellations.
- Distribution of Arrival Delay: Highly right-skewed with a peak around 10-15 minutes.
- Late aircraft and carrier delays contribute the highest proportion of delay minutes, with late aircraft causing the maximum average delay of 26.87 hours.
- Southwest Airlines (WN) has the highest number of arriving flights. G4 has the highest proportion of cancelled flights, and WN has the highest existence value.
- The highest flights occurred in June, with a clear seasonal pattern. Flights increased overall from 2003 to 2008, with the highest in 2019.
- Positive correlation exists between weather delay and arrival delay, indicating a moderate positive relationship.
- Cancellation rates are higher in winter, with Southwest (WN) having the lowest rates overall. Regional carriers face higher rates in winter.
- G4 has the highest proportion of cancelled flights (4.04%), while HA has a lower rate of 0.48%.
- G4 has the highest spread value, suggesting operational unreliability. WN has the highest existence value.
- Atlanta, GA, is the most crowded airport among the top 20, followed by Chicago, IL, and Dallas/Fort Worth.
- Strong correlation exists between carrier and late aircraft delays. Weather delays correlate most strongly with carrier delays.
- SkyWest Airlines Inc., United Air Lines Inc., ExpressJet Airlines Inc., Southwest Airlines Co., and American Airlines Inc. are the top 5.
- Positive correlation between monthly weather delay and arrival delay, with June, July, and August having the lowest delays.
- Weather delays are highest in December, January, and February, correlating with winter storms.
- Southwest has the least delayed, diverted, and cancelled flights, while Allegiant Air has the most cancelled flights.

# Key Insights for Presentation

In the presentation, I'm showing the analysis of cancelled and delayed airlines.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Files
1. [Airline_Exploration.ipynb]: Data exploration with data visualization
2. [Airline_slide_deck.ipynb]: Presentation using Jupyter slides

# Communicate Data Findings
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore the dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

[Airline_Exploration.ipynb]:<Airline_Exploration.ipynb>
[Airline_slide_deck.ipynb]:<Airline_slide_deck.ipynb>
