# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Bank Customer Churn Analysis  
### Behavioural Segmentation Based on Spending and Transaction Patterns

## Project Overview
Customer churn represents a significant risk for retail banking institutions.
This project analyses customer churn using behavioural data, with a specific focus
on spending patterns and transaction activity.

The objective is to identify behavioural segments associated with higher churn risk
and translate analytical insights into actionable business recommendations.

## Target Audience
- Banking product managers
- Customer retention and CRM teams
- Business stakeholders with limited technical background

## The dataset
The dataset is available at Kaggle and can be accessed at the following link:  
[Credit Card Customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

## Data Description
The dataset contains anonymised customer-level information, including:
- Transaction amounts and frequency
- Credit utilisation metrics
- Account tenure and engagement indicators
- Customer attrition status

No personally identifiable information (PII) is included in the dataset.

---

## Methodology
The analysis follows a structured data analytics workflow:

1. Data cleaning and preparation
2. Exploratory Data Analysis (EDA)
3. Behavioural correlation analysis (sanity check)
4. Behavioural clustering using KMeans
5. Cluster interpretation and churn risk assessment
6. Visual validation using Python and Tableau

Clustering is used as an interpretative tool to identify behavioural segments,
rather than as a predictive model.

---

## Tools and Technologies
- **Python** (Pandas, NumPy, Scikit-learn)
- **Seaborn** for static visualisations
- **Plotly** for interactive exploration
- **Tableau** for stakeholder-oriented dashboards
- **Jupyter Notebook** for analysis and documentation
- **Git & GitHub** for version control

---

## Tableau Dashboard
The Tableau dashboard provides an interactive overview of churn-related behavioural
patterns, including transaction changes, spending dynamics, and utilisation metrics.

The dashboard is designed for non-technical stakeholders and complements
the Python analysis by presenting aggregated insights. The interactive Tableau dashboard is available here:  
[Customer Churn Tableau Dashboard](dashboard/Bank_churn.twbx)
### Dashboard Visualisations Overview

- **Transaction Amount Change vs Attrition**  
This visualisation shows that customers who churn tend to exhibit lower or declining transaction amount growth compared to retained customers, indicating reduced spending engagement prior to attrition.

- **Transaction Count Change Distribution**  
The distribution highlights that churned customers are more concentrated in lower transaction frequency change ranges, suggesting reduced card usage intensity over time.

- **Transaction Count vs Transaction Amount**  
This scatter plot demonstrates a stronger and more stable positive relationship between transaction volume and transaction value for retained customers, reflecting consistent spending behaviour.

- **Utilisation Ratio Distribution**  
Distributional analysis reveals noticeable differences in utilisation behaviour between churned and retained customers. These patterns are not strongly reflected in correlation metrics due to the categorical nature of churn and the non-linear relationship between utilisation and attrition.


---

## Key Insights
- Declining transaction activity is strongly associated with churn.
- Customers with low engagement and weak spending growth exhibit the highest churn risk.
- Behavioural patterns are more informative than demographic attributes for churn analysis.
- Clustering enables targeted retention strategies based on customer behaviour.

---

## Ethical Considerations and Data Governance
- All data used in this project is anonymised and does not contain PII.
- Results are used for analytical insight rather than automated decision-making.
- Behavioural segmentation carries a risk of bias if misused for unfair targeting.
- Any real-world deployment should include regular bias monitoring and compliance
  with data protection regulations such as GDPR.

---

## AI Assistance
An AI assistant was used during the project to:
- Support code debugging and error resolution
- Assist with analytical reasoning and narrative structure
- Help refine cluster naming and stakeholder-oriented explanations

The AI assistant did not generate final analytical results or automate decision-making.

---

## Project Maintenance and Future Updates
In a real-world setting, this project could be maintained by:
- Regularly updating transactional data
- Re-evaluating behavioural clusters as customer behaviour evolves
- Monitoring cluster stability and churn distribution over time
- Updating the Tableau dashboard to reflect new data snapshots

## Credits

- The project is based on the **Code Institute Data Analytics & AI Skills Bootcamp**
  masterclasses and learning materials, which guided the overall analytical
  structure, use of Python libraries, and clustering methodology.

- The **Bank Customer Churn dataset** was used for educational and analytical
  purposes. The dataset contains anonymised customer data and does not include
  any personally identifiable information (PII).

- **Python** was used for data cleaning, exploratory data analysis, clustering,
  and statistical summaries, with key support from the following libraries:
  - Pandas and NumPy for data manipulation
  - Seaborn and Matplotlib for static visualisations
  - Plotly for interactive visualisation
  - Scikit-learn for scaling, PCA, and clustering

- **Tableau** was used to design the interactive dashboard aimed at
  non-technical stakeholders, enabling exploration of transaction behaviour,
  spending changes, and churn patterns.

- **Git and GitHub** were used for version control, project organisation,
  and documentation of the development process.

- **Jupyter Notebook** was used as the primary environment for analysis,
  combining code, visual outputs, and explanatory markdown cells to
  communicate insights clearly.


## Limitations and Future Work
- The analysis is based on a static snapshot of customer behaviour.
- Time-series modelling could provide earlier churn signals.
- Predictive models (e.g. logistic regression) could complement clustering.
- Additional behavioural features may further improve segmentation.

---

## Learning Reflection
This project strengthened practical skills in:
- Behavioural data analysis
- Clustering and segmentation techniques
- Multi-tool workflows combining Python and Tableau
- Communicating insights to technical and non-technical audiences

Future learning goals include predictive modelling and advanced customer analytics.
