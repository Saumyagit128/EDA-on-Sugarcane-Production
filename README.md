# EDA-on-Sugarcane-Production

## Objective
Task 5: Exploratory Data Analysis (EDA)

Extract insights using visual and statistical exploration. 

## Overview

This project analyzes global sugarcane production by exploring key factors like production volume, land usage, and yield per hectare across different countries and continents.

Through comprehensive **Exploratory Data Analysis (EDA)**, we:
- Identify top-producing regions
- Understand relationships between variables
- Visualize the distribution of production


---

## 🧹 Data Cleaning

### 🔧 Data Cleaning Process
Before diving into analysis, the dataset is cleaned to ensure accuracy and usability.

- Remove Unwanted Characters
- Remove Unnecessary Columns
- Rename Columns for Consistency
- Handle Missing Values
- Data Conversion

---

## 🔍 Univariate Analysis

### 🌍 Countries Producing Sugarcane by Continent
- **Africa:** 38
- **Asia:** 25
- **North America:** 22
- **South America:** 11
- **Oceania:** 4
- **Europe:** 2

### 📊 Distribution of Key Variables
- **Production (Tons)**
- **Production per Person (Kg)**
- **Acreage (Hectare)**
- **Yield (Kg/Hectare)**

### 🔍 Observations:
- **Production (Tons):** Highly skewed — Brazil, India, and China dominate.
- **Production per Person (Kg):** Skewed with a few high outliers.
- **Acreage (Hectare):** Less skewed.
- **Yield (Kg/Hectare):** Varies significantly.

### 📦 Outlier Detection
- Boxplots reveal outliers in:
  - **Production (Tons)** (Brazil, India, China)
  - **Yield (Kg/Hectare)** (high-yield countries)

### 🎻 Violin Plot
- Violin plot for **Production (Tons)** reveals skewness and spread.

---

## 🔗 Bivariate Analysis

### 🌾 Highest Acreage (Land Area)
- Brazil, India, China dominate.

### 🚜 Highest Yield per Hectare
- **Guatemala** has the highest yield — indicating efficient farming.

### 👥 Highest Production per Person
- **Paraguay** leads in production relative to population.

### 🔥 Correlation Analysis
| Variables                      | Correlation |
|---------------------------------|-------------|
| Production (Tons) & Acreage     | **0.997**   |
| Production (Tons) & Yield       | **0.132**   |

- ✅ Heatmap visualizes this correlation.

### 📈 Land vs. Production
- Scatter plot confirms that higher acreage → higher production.

### 📉 Yield vs. Production
- Weak correlation — high yield does not always mean higher total production.

---

## 🌍 Continental Analysis

### 🔢 Total Production by Continent:
- **South America:** Highest producer (led by Brazil).
- **Asia:** Second.
- **North America:** Third.

### 🔍 Impact of Number of Countries
- The number of countries in a Continent does not effect production of sugarcane.
- Continents with fewer countries (e.g., South America) can still lead in production due to major producers like Brazil.

### 🌱 Land vs Production by Continent
- Continents with highest lands produces more sugar cane

---

## ✅ Conclusion

This project provides a comprehensive analysis of global sugarcane production, offering insights into:
- Distribution of production
- The role of land usage
- Yield efficiency across countries and continents

By understanding these factors, **agricultural strategies can be improved**, and **resource management in the sugarcane industry can be optimized**.
