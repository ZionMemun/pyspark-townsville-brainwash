# pyspark-townsville-brainwash-Project

## 📂 Dataset
The project integrates four main datasets:
- **Reference Data** – device-to-household mapping (device ID, DMA, household ID, etc.)
- **Daily Program Data** – program metadata (title, genre, air date/time, duration)
- **Program Viewing Data** – mapping between devices and viewed programs
- **Demographic Data** – household demographics (size, age, income, vehicles, etc.)

## 🧩 Part 1 – Brainwash Detection
Mojo Jojo has tampered with TV data to brainwash the citizens of Townsville.  
Tasks:
- Flag malicious program airings that meet ≥ 4 of 7 predefined suspicious conditions
- Label entire titles as malicious if > 40% of their airings are flagged
- Display the **top 20 malicious titles** ranked by percentage of malicious records

## 🧩 Part 2 – Un-brainwashing
Help the Powerpuff Girls reverse the brainwashing effects.  
Tasks:
- Identify the **top 5 genres, DMAs, and programs** with the highest viewership
- Compute a **wealth score** per DMA (normalized average of net worth and income)
- Assign the **top 11 unique genres** to the 10 wealthiest DMAs (without duplication)

## ⚙️ Tools and Environment
- **Language**: Python 3.9+  
- **Framework**: Apache Spark (PySpark, Spark 3+)  
- **Platform**: Databricks  

