
---

## **Project Overview**

The primary goal of this project is to:

1. **Identify patterns** in my personal recovery, sleep, and workout metrics.
2. **Understand how strain and recovery** affect my performance.
3. **Develop actionable insights** to plan workouts more effectively and prevent burnout.

---

## **Methodology**

1. **Data Preprocessing**:
   - Merged datasets from **sleep, physiological, and workout data**.
   - Handled missing data to ensure high-quality clustering results.

2. **K-Means Clustering**:
   - Grouped similar days into **three clusters** to identify different activity patterns.
   - Visualized the clusters to understand trends in **recovery, sleep, and strain**.

3. **Cluster Analysis**:
   - Calculated summary statistics for each cluster to distinguish **balanced days, intense workout days, and high-stress days**.

---

## **Results**

The analysis revealed three types of days:

### **Cluster 0: Balanced Days (Recovery Days)**
- **High REM and deep sleep** with moderate strain.
- **Optimal for recovery** and essential for maintaining long-term performance.

### **Cluster 1: High Activity Days**
- **High strain and heart rate**, indicating intense workouts.
- Requires **adequate recovery** afterward to avoid fatigue.

### **Cluster 2: High Stress Days (Low Recovery)**
- **Poor sleep quality** and high heart rate.
- Signals the need for **rest or reduced activity** to prevent burnout.

---

## **Next Steps**

1. **Dashboard Development**: Create a **dashboard** to monitor my recovery and performance in real-time.
2. **Performance Prediction Model**: Use machine learning to forecast performance based on **sleep, strain, and recovery metrics**.

---

## **Notes**

This is a **personal project** intended for my own use. The data, code, and insights are **not intended for public use or collaboration**. If you’re interested in a similar project, I recommend gathering your own physiological data and applying similar techniques.

---

## **How to Run the Project Locally**

### 1. Clone the Repository (For Personal Use Only)
```bash
git clone https://github.com/your-username/whoop-cluster-analysis.git
cd whoop-cluster-analysis
