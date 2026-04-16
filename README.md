# NYC Aviation Delay Analysis (2024)

Analysis of 1M+ flight records to identify why NYC airport systems (JFK, LGA, EWR) fail under pressure — and when those failures peak.

---

## Overview

This project analyzes over 1 million flight records to uncover the key drivers behind delays and cancellations across New York City’s major airports.

The goal was to separate controllable operational inefficiencies from external factors like weather, and identify patterns that impact system reliability at scale.

---

## Key Findings

### 1. Technical Issues Dominate Delays
EWR and LGA show significantly higher technical delays compared to weather-related disruptions  
Technical failures were observed to be up to 12x more frequent than weather delays  

---

### 2. The NYC "Cancellation Gap"
NYC airports exhibit higher cancellation rates than the national average  
This occurs despite having similar average delay durations, indicating systemic inefficiencies rather than isolated disruptions  

---

### 3. The "Late Night Collapse" (9 PM – 3 AM)
System-wide delays peak during late-night hours  
This suggests airports struggle to recover from accumulated daytime operational stress, leading to cascading failures overnight  

---

### 4. Airport-Specific Performance Differences
- **LGA**: Highest concentration of technical delays  
- **EWR**: Elevated cancellations and operational instability  
- **JFK**: More balanced performance across delay types  

---

### 5. Volume ≠ Delays
Increased flight volume does not directly correlate with higher delays  
Mid-month periods show elevated delays despite stable traffic levels, suggesting internal operational factors  

---

### 6. Weekly Operational Patterns
- **Monday**: Highest system fault rates  
- **Wednesday**: Lowest delay frequency  

---

## Dashboard Visuals

### 📊 Geographic Distribution of Operational Delays
![Geographic Distribution of Operational Delays](images/delay_distribution.png)

---

### 📉 Late Night Delay Spike (9 PM – 3 AM)
![Late Night Spike](images/late_night_spike.png)

---

### 📍 Airport Performance Comparison
![Airport Comparison](images/airport_comparison.png)

---

### 📈 Volume vs Delay Scatter Plot
![Volume vs Delay](images/volume_vs_delay.png)

---

## Tools & Methods

- **SQL**
  - Data consolidation using UNION ALL across multiple datasets  
  - Aggregations and joins across 1M+ records  
  - Data cleaning and transformation for consistency  

- **Power BI**
  - Interactive dashboards and data modeling  
  - Scatter plots to identify non-linear failure patterns  
  - DAX for calculated metrics and KPIs  

---

## Business Impact

This analysis shows that reducing delays in NYC airports is less about limiting traffic and more about improving operational efficiency.

Key opportunities include:
- Optimizing maintenance scheduling  
- Improving late-night recovery operations  
- Implementing predictive maintenance models  

These changes could significantly reduce cancellations and improve overall system reliability.
