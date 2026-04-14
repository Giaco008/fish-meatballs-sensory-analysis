# 🐟 Tamarong Fish Meatballs Sensory Analysis  
### Development and Evaluation of Tamarong (Selar crumenophthalmus) Fish Meatballs Infused with Spinach and Moringa  

---

## 📌 Project Overview  
This project presents a comprehensive **sensory evaluation and statistical analysis** of Tamarong (*Selar crumenophthalmus*) fish meatballs infused with **spinach (*Spinacia oleracea L.*)** and **moringa (*Moringa oleifera*)**.  

The study aims to assess consumer acceptability and determine whether significant differences exist among different formulations using **data analysis, visualization, and inferential statistics**.

This analysis was conducted using **Google Colab**, applying Python-based data analysis techniques.

---

## 🎯 Objectives  

### 1. Evaluate Sensory Quality in Terms of:
- Color  
- Aroma  
- Texture  
- Taste  
- Aftertaste  
- Overall Acceptability  

### 2. Statistical Objective:
- Determine whether there is a **significant difference** in sensory attributes across treatments using **ANOVA and post-hoc tests**.

---

## 🛠 Tools & Technologies Used  
- **Google Colab (Python Environment)**  
- **Pandas & NumPy** (data processing)  
- **Matplotlib & Seaborn** (visualization)  
- **SciPy / Statsmodels** (statistical analysis)  

---

## 📊 Data Analysis Workflow  

### 🔹 1. Data Preparation  
- Imported raw sensory evaluation data  
- Cleaned dataset (handled missing values and formatting)  
- Structured data for statistical analysis  

---

### 🔹 2. Descriptive Statistics  
- Computed **mean scores per treatment** for all attributes  
- Compared trends across formulations  

#### 📌 Summary of Mean Scores:
| Treatment | Color | Aroma | Texture | Structure | Mouthfeel | Taste | Aftertaste | Overall |
|----------|------|------|--------|-----------|----------|------|-----------|--------|
| 0 | 7.22 | 6.98 | 6.57 | 6.91 | 6.98 | 7.04 | 6.84 | 7.40 |
| 1 | 6.19 | 6.24 | 6.00 | 6.22 | 6.44 | 6.31 | 6.09 | 6.31 |
| 2 | 6.46 | 6.66 | 6.37 | 6.48 | 6.39 | 6.38 | 6.20 | 6.62 |
| 3 | 6.30 | 6.56 | 6.24 | 6.27 | 6.50 | 6.42 | 6.23 | 6.60 |

👉 **Treatment 0 consistently achieved the highest scores across most attributes.**

---

### 🔹 3. Data Visualization  
The following visual tools were used to explore and present insights:

- 🔥 **Heatmap** – to visualize intensity of sensory attributes  
- 🕸 **Radar Chart** – to compare overall sensory profiles  
- 📊 **Bar Graphs** – to show mean differences  
- 📦 **Boxplots** – to analyze distribution and variability  

---

### 🔹 4. Inferential Statistics  

#### ✅ One-Way ANOVA Results  
ANOVA was used to determine whether differences between treatments are statistically significant.

| Attribute | F-value | p-value | Interpretation |
|----------|--------|--------|----------------|
| Color | 7.85 | 0.000043 | Reject H₀ |
| Aroma | 3.91 | 0.01 | Reject H₀ |
| Texture | 2.64 | 0.05 | Reject H₀ |
| Structure | 3.91 | 0.01 | Reject H₀ |
| Mouthfeel | 2.75 | 0.04 | Reject H₀ |
| Taste | 4.04 | 0.01 | Reject H₀ |
| Aftertaste | 3.88 | 0.01 | Reject H₀ |
| Overall | 11.33 | 0.000000411 | Reject H₀ |

👉 **All attributes showed statistically significant differences between treatments.**

---

### 🔹 5. Post-Hoc Analysis (Tukey HSD)  

To identify which treatments differ:

- Treatment **0 vs 1, 2, 3** showed significant differences in:
  - Color  
  - Taste  
  - Aftertaste  
  - Overall Acceptability  

👉 This indicates that **Treatment 0 is significantly more preferred** compared to others.

---

## 🔍 Key Insights  

- ✅ **Treatment 0 achieved the highest overall acceptability (7.40)**  
- ✅ Significant differences exist across all sensory attributes  
- ✅ Taste, color, and overall acceptability are key drivers of preference  
- ✅ Some attributes (e.g., mouthfeel) showed less variation between treatments  

---

## 📈 Conclusion  

The analysis confirms that incorporating spinach and moringa significantly influences the sensory characteristics of Tamarong fish meatballs.  

Among all formulations, **Treatment 0 consistently performed best**, indicating it is the most acceptable variant for consumers.  

This study demonstrates how **data analytics and statistical methods** can be effectively applied in food product development to guide decision-making.
