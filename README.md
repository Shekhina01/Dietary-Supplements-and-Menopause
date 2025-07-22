# 🌱 Survival Modelling of Menopause Onset Using Dietary Supplement Intake

This project explores the impact of dietary supplement intake and lifestyle factors on the timing of menopause using **Cox Proportional Hazards** and **Gradient Boosting Machine** models.

The analysis is based on 3,566 women from the **UK Women's Cohort Study**, using high-dimensional dietary and health data. The study aims to identify modifiable lifestyle predictors of early or delayed menopause — a factor linked to several chronic diseases.

---

## 🎯 Objectives
- Evaluate the relationship between supplement use and menopause onset
- Build statistical models for time-to-event prediction
- Compare Cox PH and GBM model performance
- Translate results into public health insight

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `report/dissertation_supplements_menopause.pdf` | Full dissertation document |
| `scripts/survival_model_analysis.R` | R code (Cox model, GBM, preprocessing) |
| `data/simulated_menopause_data.csv` | (Optional) fake dataset for demonstration |

---

## 🧠 Methodology

- **Data Source**: UK Women's Cohort Study (UKWCS)
- **Target Variable**: Age at natural menopause
- **Models**:
  - Cox Proportional Hazards Model
  - Gradient Boosting Machine (GBM)
- **Tools**: R, `survival`, `gbm`, `tidyverse`, `survminer`
- **Evaluation Metrics**: Concordance Index (C-index), calibration, residual analysis

---

## 📈 Results Snapshot

- Women consuming **supplements with phytoestrogens** experienced slightly later menopause
- **Higher BMI and smoking** predicted earlier menopause
- GBM outperformed Cox PH model in predictive accuracy

---

## 📬 Author

**Shekhina Mary Jebaraj**  
MSc Data Science, University of Leeds  
📍 Leeds, UK  
📧 shekhinamaryjebaraj@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/shekhinamaryjebaraj)

---

## 📘 Citation

> Jebaraj, S.M. (2025). *The Role of Dietary Supplements in Modulating Menopause Onset*, University of Leeds MSc Dissertation.
