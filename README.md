## Feature Engineering Techniques for Machine Learning to Automate Traffic Control Intervals Based on the Real-Time Traffic Data
Traffic delays and accidents in urban areas are primarily caused by congestion at intersections. Some systems use predetermined traffic schedules that do not adjust to real-time traffic conditions. Additionally, some systems rely on traffic police officers to manage traffic control at congested intersections, which can be prone to human error. This paper presents an automated solution that utilizes machine learning models to predict green signals and traffic cycles based on real-time data. The research improves the original dataset by incorporating Level of Service (LOS) Ratings and the Haversine Formula to feature engineer average vehicle speeds, traffic density, and the distance between intersections. These features are essential for effective modelling. Ultimately, the Polynomial Regression model demonstrated excellent predictive performance compared to other models. This solution facilitates efficient traffic control and optimizes overall traffic flow.

---
### The original dataset
The original dataset is from the Bangkok Metropolitan Administration (BMA). 
Link to the website: http://www.bmatraffic.com/index.aspx 

---
### This GitHub contains
- The original Excel files of Bangkok's Traffic Data in 2023
- The Python Code for data pre-processing, feature engineering, and modelling experiments
