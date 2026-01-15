# Obesity-Risk-Prediction
Multi-class classification of obesity levels based on eating habits and physical condition

# Development of a Predictive Model for Metabolic Risk Assessment in Intelligent Habit-Tracking Systems

## Project Concept

This research focuses on developing the analytical core for a next-generation mobile tracking application. Unlike conventional solutions, this project transcends static classification of a user's current state. The system is designed as a **dynamic health simulator**, capable of forecasting changes in weight categories resulting from the modification of specific behavioral patterns.

The project establishes the mathematical foundation for a **"Pre-impact Analysis"** feature: users can visualize the quantitative shift in their risk profile when quitting smoking, increasing water intake, or reducing screen time.

## Theoretical Framework and Data

The study is based on a multi-factor analysis of anthropometric and behavioral data. The modeling accounts for the synergy between the following feature groups:

* **Genetic Determinants:** Family history as a baseline modifier of metabolic response.
* **Dietary Patterns:** Structured analysis of nutrient intake (FAVC, FCVC) and hydration regimes (CH2O).
* **Behavioral Triggers:** Monitoring of physical activity (FAF) and sedentary levels (TUE).

## Methodology and Engineering Solutions

A comprehensive data processing pipeline was implemented to ensure high model interpretability:

1. **Correlation Analysis:** Utilizing the ** (Phik)** coefficient allowed for the discovery of hidden non-linear dependencies between lifestyle and obesity risk that are often overlooked by classical methods (Pearson/Spearman).
2. **Hybrid Encoding Strategy:** The application of *Binary*, *Ordinal*, and *One-Hot Encoding* is tailored to the physical nature of each feature, preventing the introduction of mathematical "noise" into the model weights.
3. **Classification Architecture:** A comparative analysis of ensemble algorithms (Random Forest, XGBoost, CatBoost) with a focus on generalization capability and robust performance across diverse user profiles.

## Ethical Compliance and Safety

A core priority of this development is the psychological safety of the user. During hyperparameter tuning, a penalty function was applied to **False Positive** errors (incorrect diagnosis of obesity). This is critical for preventing the onset of eating disorders (ED) in users with a healthy weight. The **Weighted -score** was selected as the primary performance metric to ensure an optimal balance between system sensitivity and clinical reliability.

## Practical Application (Business Value)

The developed algorithm enables the following features within the end-user product:

* **Virtual Modeling:** "How will my health outlook change in 6 months if I switch from driving to walking?"
* **Habit Prioritization:** The system identifies the most critical "detrimental" factor for a specific individual, allowing them to focus their efforts where they will have the most significant impact.
* **Personalized Monitoring:** Dynamic adjustment of tracker goals based on real-time shifts in predicted risk.

---

