<h1>Accidents Hotspot Analysis and Nearby Hospital Recommendation using Weather and Traffic Data</h1>

<h3>Project Overview</h3>

This project aims to enhance road safety and emergency response by analyzing historical data on traffic accidents, weather conditions, and hospital locations in the United States. The goal is to predict accident hotspots and recommend nearby hospitals to reduce response times in emergencies. The analysis covers data from February 2016 to March 2023, spanning 49 states in the USA.

<h3>Key Features</h3>

Accident Hotspot Prediction: Identification of areas with a high likelihood of accidents based on historical data.
Hospital Recommendation: Real-time suggestions for the nearest hospitals to an accident location.
Traffic and Weather Analysis: Insight into the correlation between traffic, weather conditions, and accident rates.
User-Friendly Interface: A responsive interface for quick access to hospital information during emergencies.

<h3>Project Structure</h3>

<h5>1. Data Collection and Overview</h5>
Datasets Used:<br>
US Traffic Events Data: Comprehensive records of car accidents across the USA <br>
Weather Events Dataset: Data on weather conditions that could impact road safety.<br>
US Hospitals Dataset: Information on 7513 hospitals, including locations and available facilities. <br>
<h5>2. Data Analysis</h5>

Patterns Identified:<br>
Temporal: Higher accident rates during rush hours and weekends.<br>
Seasonal: Increased accidents during adverse weather conditions and holidays.\
Geographical: Specific regions identified as accident hotspots.\
Weather Impact: Correlation between severe weather conditions and higher accident probabilities.\
Traffic Volume: Higher traffic volumes linked to increased accident rates.\
Driver Behavior: Impact of distracted driving and speeding on accident frequency.
<h5>3. Predictive Modeling</h5>
Algorithm Used:<br>
Random Forest: Employed for predicting accident occurrences based on historical data.
<h5>4. Accident Hotspot Identification</h5>
Methodology: Analysis of trends in accident frequencies to pinpoint high-risk areas.<br>
<h5>5. Hospital Recommendation System</h5>
Algorithm Used:<br>
K-Nearest Neighbors (KNN): Used to recommend the nearest hospitals to an accident site.
<h5>6. User Interface Development</h5>
Features:<br>
Real-time display of nearby hospitals to assist in emergency response.<br>
Designed for quick and easy decision-making in critical situations.
<h5>7. Project Scaling</h5>
Phases of Scaling:<br>
Initial analysis on 25% of the data using Azure DataBricks with 2 nodes.<br>
Gradual scaling to 50%, 75%, and 100% of the data for comprehensive analysis.
<h5>8. Technologies and Tools</h5>
Data Processing: Azure DataBricks<br>
Storage: Azure Blob Storage<br>
Machine Learning: Random Forest (for accident prediction), K-Nearest Neighbors (for hospital recommendation)<br>
Geographical Information Systems (GIS): For accurate location-based analysis.
