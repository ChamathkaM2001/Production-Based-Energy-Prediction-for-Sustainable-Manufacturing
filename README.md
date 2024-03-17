# Production-Based-Energy-Prediction-for-Sustainable-Manufacturing
### Table  Of Content
-[Project Overview](#project-overview)

-[Data Sources](#data-sources)

-[Model Development](#model-development)

-[Tools Used](#tools-used)

-[Results](#results)

-[Limitations](#limitations)

### Project Overview
---
In the context of Unilever Sapugaskanda's production plant in Sri Lanka, the project aims to address the challenge of predicting electricity consumption before production commences. By leveraging historical data, the project seeks to develop a predictive model that correlates production units per SKU with electricity consumption. This model is envisioned to provide Unilever with predictive insights, empowering them to optimize manufacturing processes, reduce environmental impact, and allocate resources efficiently. Through the application of advanced predictive analytics, the project aims to bridge the gap between energy prediction technologies and practical implementation, ultimately enhancing operational efficiency, financial savings, and ecological sustainability within the manufacturing operations of Unilever Sapugaskanda.

### Data Sources
---
The dataset for the project spans from mid-2017 to mid-2023 and focuses on the HFD plant, which produces Viva and Horlicks, comprising 18 stock-keeping units. It includes around 2500 records capturing daily production quantities and actual energy consumptions. Data sources encompass DB-Wise Electricity Data, Production Plans for Viva and Horlicks, On-Site Data Collection in 2023, Constant Values collected during factory visits, and Documented Data Transformation. These sources provide detailed insights into energy consumption patterns, production plans, and technical specifications of equipment, facilitating accurate estimation of energy usage during production processes. Discussions with Unilever management and on-site visits further enhance understanding and analysis reliability.

Data Sources:
  
1.DB-Wise Electricity Data

2.Production Plans for Viva and Horlicks

3.On-Site Data Collection (2023)

4.Constant Values collected during factory visits

5.Documented Data Transformation

These sources collectively contribute to a comprehensive dataset, ensuring accurate analysis and insights into energy consumption patterns and production processes at the HFD plant.

### Model Development 
---
In the model development phase, after conducting a literature review, three models were considered: Multiple Linear Regression, XGBoost, and Random Forest Regression. Among them, the Random Forest Regression model emerged as the most adept in accurately predicting energy consumption, owing to its proficiency in handling complex relationships and capturing non-linear patterns. Trained on a comprehensive dataset spanning mid-2017 to mid-2023, the Random Forest model demonstrated superior predictive accuracy. Performance evaluation metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) were utilized, and cross-validation techniques were employed to refine the model. The results were integrated with PowerBI for enhanced visualization and interpretability, ensuring alignment with Unilever's objectives. Ethical considerations, including data privacy and model transparency, were prioritized throughout the process.

### Tools used
---
1.Python: Utilized for robust data analysis capabilities.

  Libraries: NumPy, Pandas, Scikit-Learn
  
2.Random Forest and Linear Regression Models: Implemented for predictive analysis.

3.Data Augmentation Techniques: Applied to enhance model robustness and adaptability to diverse scenarios.

4.PowerBI: Employed for data presentation and creating interactive dashboards.

### Results
---

This project yields significant outcomes addressing energy consumption in manufacturing:

1. **Critical Issue Addressed:** 
   - Directly tackles the pressing concern of energy consumption in manufacturing, leading to reduced greenhouse gas emissions, cost savings, and increased market competitiveness.

2. **Data-Driven Approach Utilized:**
   - Harnesses machine learning models to identify complex relationships between production factors and energy consumption, enabling more accurate predictions and informed decision-making.

3. **Promotion of Sustainable Manufacturing:**
   - Aligns with sustainable manufacturing principles by reducing environmental impact, improving operational efficiency, and promoting responsible production practices.
  
  ### Recommendations 
  ---
**Sustainability Integration:**
Explore integrating renewable energy data into predictive models to enhance accuracy and align with sustainable energy practices.

**Energy Efficiency Metrics:**
Introduce energy efficiency metrics into predictive models to identify areas for improvement, contributing to cost savings and sustainability goals.

**Emissions Reduction Strategies:**
Consider incorporating emissions data alongside electricity consumption predictions to identify strategies for reducing environmental impact.

**Sustainable Production Planning:**
Align production schedules with periods of higher renewable energy availability or lower carbon intensity for more sustainable operations.

**Long-Term Sustainability Roadmap:**
Develop a comprehensive long-term sustainability roadmap for integrating environmental, social, and governance (ESG) factors into energy consumption predictions, ensuring ongoing commitment to sustainability

###  Limitations
---
While proficient in capturing complex relationships within data, the Random Forest model has limitations:

-Handling Nonlinear Patterns:

Challenges may arise in handling certain nonlinear patterns depending on the data's nature.

-Interpretability Concerns:

Compared to simpler models like Multiple Linear Regression, the Random Forest model may have limited interpretability.
