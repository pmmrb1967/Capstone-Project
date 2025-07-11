# IBM Data Science Capstone Project: SpaceX Falcon 9 First Stage Landing Prediction

## 📌 Project Overview
As part of the **IBM Data Science Professional Certificate**, this capstone project simulates the role of a Data Scientist at **Space Y**, a fictional competitor to SpaceX. The goal is to **predict whether SpaceX will successfully reuse the Falcon 9 rocket's first stage**—a critical factor in reducing launch costs.  

### 🚀 Business Scenario
- **SpaceX’s cost advantage**: Reusability of the first stage cuts launch costs to **\$62M** (vs. \$165M for competitors).  
- **Key question**: *Can we predict first-stage landings to estimate launch costs for Space Y?*  
- **Solution**: Use **public SpaceX launch data** to build a machine learning model and interactive dashboards.

---

## 🔍 Project Workflow
### 1. **Data Collection**
   - **Sources**: SpaceX API, web scraping from [Wikipedia’s Falcon 9 launch list](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches).  
   - **Tools**: Python (`requests`, `BeautifulSoup`), REST APIs.  

### 2. **Data Wrangling & EDA**
   - Cleaned and transformed data using **Pandas** and **SQL**.  
   - Explored relationships between launch parameters (e.g., payload mass, orbit type) and landing success.  

### 3. **Interactive Dashboards**
   - Built visualizations with **Folium** (geospatial) and **Plotly Dash** (interactive analytics).  
   - Example: Launch success rates by launch site.  

### 4. **Predictive Analysis (Classification)**
   - Trained models (**Logistic Regression, SVM, Decision Trees**) to predict first-stage landing success.  
   - Evaluated performance using **accuracy, precision-recall, and F1-score**.  

### 5. **Final Presentation**
   - Summarized insights in a **PowerPoint/PDF report** (peer-reviewed).  

---

## 🛠️ Technologies Used
| Category          | Tools/Libraries |
|-------------------|-----------------|
| **Data Collection** | Python, APIs, Web Scraping |
| **Data Analysis**  | Pandas, NumPy, SQL |
| **Visualization**  | Matplotlib, Seaborn, Folium, Plotly Dash |
| **Machine Learning** | Scikit-learn, XGBoost |
| **Dashboarding**   | Jupyter Notebooks, IBM Watson Studio |

