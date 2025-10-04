# Project: Exports and Employment in Korea’s Entertainment & Media Industry

## 📋 Project Overview

This project analyzes the relationship between **exports** and **domestic employment** in Korea’s Entertainment & Media (E&M) industry.  
Using firm-level panel data from 2014–2022, the study investigates whether firms that export more also generate more jobs.  

The project was divided into key phases:

1. **Data Collection & Panel Construction**  
2. **Variable Definition (Exports, Employment, Controls)**  
3. **Econometric Modeling (OLS, FE, RE)**  
4. **Hausman Test for Model Selection**  
5. **Interpretation & Policy Implications**

---

## 📊 Data Sources

- **Survey on Business Activities (2014–2022), Statistics Korea**  
  - Firm-level panel dataset  
  - Variables: employment (regular & temporary workers), exports, imports, revenue, assets, labor costs, investment in tangible assets, trademarks, industry wages  
  - Structure: unbalanced panel

---

## ⚙️ Technologies Used

- **Software:** Stata  
- **Econometric Methods:** Pooled OLS, Fixed Effects (FE), Random Effects (RE)  
- **Tests:** Hausman test for model specification  
- **Error Handling:** Clustered standard errors at firm level  
- **Data Processing:** Log transformation of variables, handling of unbalanced panel data  

---

## 🚀 Methodology

### 1. **Data Preparation**
- Constructed firm-level panel dataset (2014–2022).  
- Defined dependent variable: log of regular employment.  
- Main regressor: log of exports.  
- Control variables: revenue, assets, investment in tangible assets, imports, trademarks, industry-year wages.  

### 2. **Econometric Modeling**
- Compared **Pooled OLS**, **Fixed Effects (FE)**, and **Random Effects (RE)**.  
- Estimated export–employment relationship with clustered standard errors.  

### 3. **Hausman Test**
- Conducted Hausman test to decide between FE and RE.  
- Results rejected RE consistency, supporting FE as the preferred model.  

---

## 📈 Results & Key Findings

- **Positive Export–Employment Link:** Exports positively associated with firm employment.  
- **Coefficient Range:** 0.006–0.016 for log exports across models.  
- **Robust Evidence:** FE estimates remained positive and significant, even after controlling for unobserved heterogeneity.  
- **Policy Implication:** Export promotion in creative industries can enhance domestic job creation.  

---

## ✅ Insights & Recommendations

- **Policy Leverage:** Expand export support programs targeting small and medium-sized E&M firms.  
- **Employment Strategy:** Utilize creative industries as drivers of both trade and jobs.  
- **Further Research:** Examine causal mechanisms and potential spillovers into adjacent sectors (e.g., gaming, digital content).  

---

## 📚 Resources

- Statistics Korea, *Survey on Business Activities* (2014–2022)  
- Panel data econometrics: Baltagi (2008), Wooldridge (2010)  
- OECD & UNESCO reports on creative and cultural industries  

---

## 🎯 Conclusion

This study finds that **exports significantly contribute to domestic employment** in Korea’s Entertainment & Media industry.  
Through panel econometric methods in Stata, the project provides robust evidence that export growth in creative industries supports job creation, offering valuable insights for both policymakers and industry leaders.
