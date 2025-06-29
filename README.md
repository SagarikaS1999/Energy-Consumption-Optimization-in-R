# 🔋 Optimizing Energy Consumption with Predictive Analytics

This project was developed as part of IST 687: Introduction to Data Science, in collaboration with eSC, a sustainable energy company. The goal was to utilise advanced analytics and machine learning to optimise energy consumption during peak periods, leveraging R, Shiny, and statistical modelling.

## 📌 Objective

To build an end-to-end solution that:
- Analyzes energy usage data across counties in the Carolinas
- Identifies patterns and inefficiencies in consumption
- Applies predictive models to forecast energy demand
- Provides dynamic dashboards to support data-driven decision making

## 🛠 Tools & Technologies Used

- **R**: Data wrangling, analysis, and modelling
- **R Shiny**: Interactive dashboard and visualization
- **ggplot2 / tidyverse**: Data cleaning and visual analytics
- **SVM & GLM**: Predictive modeling
- **RMarkdown**: Documentation and reporting

## 📂 Project Structure

| File/Folder | Description |
|-------------|-------------|
| `Complete R Code.Rmd` | Main R Markdown file with data cleaning, analysis, and modeling |
| `shiny app code.txt` | Folder containing UI and server files for interactive dashboard |
| `Final Datasets` | Cleaned and raw datasets used for analysis |
| `IDS_Project_Report.pdf` | Final project report submitted for IST 687 |
| `README.md` | You're reading it! Project overview and instructions |

## 📊 Key Results

- Applied two predictive models—Generalized Linear Models (GLM) and Support Vector Machines (SVM)—to forecast energy usage across building types and environmental conditions.

- Why we used them: GLM was selected for its interpretability and strong handling of linear relationships, while SVM was chosen for its performance with high-dimensional, non-linear datasets.

- #### Impact: These models enabled us to accurately predict peak energy demand and provide actionable recommendations to eSC, allowing them to optimize resource allocation without new infrastructure.

- #### Outcome: SVM delivered better predictive accuracy, achieving a lower Root Mean Square Error (RMSE: 0.0784) compared to GLM (RMSE: 0.5255), making it the preferred model for this analysis.

- Built an interactive Shiny app to explore county-level energy usage trends.
