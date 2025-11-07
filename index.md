---
title: "DSC 180A – Methodology Assignment 4, Task 2"
description: "Created by Aditya Surapaneni"
---

# *Aditya Surapaneni*

**Email:** assurapaneni@ucsd.edu  

*Section **B19**:* From Data to Dispatch – Optimizing SDG&E Field Services  
*Mentor:* Phi Nguyen

---

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic covered in my domain (From Data to Dispatch - Optimizing SDG&E Field Services) this quarter was the idea of work crews “gaming the system”. It was fascinating to uncover how discrepancies between planned vs. actual times on site can reveal behavioral or process-related inefficiencies in field operations. This concept highlights how data isn’t just about performance; it can also expose subtle human or procedural factors that impact accuracy/accountability. Identifying, understanding, and addressing this behavior could lead to more reliable scheduling, reporting, and overall productivity improvements.

---

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For the Quarter 2 Project, I would like to explore the development of a machine learning model that can automatically flag jobs likely to be “gamed” by crews. This model could learn patterns from historical data, such as timing anomalies, scheduling inconsistencies, or other operational metrics. However, such a project would require labeled data distinguishing “gamed” versus “non-gamed” operations, which currently isn’t being collected. Establishing a reliable process for labeling this data would be an important first step toward building an intelligent detection system.

---

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
In our Quarter 1 Project, we used a simple rule-based definition of “gaming the system,” flagging operations where actual time on site was zero but planned time on site was greater than zero. While this approach effectively identifies obvious cases, it may miss more subtle forms of gaming or data inconsistencies. A more advanced approach would involve collecting/labeling data for confirmed “gamed” vs. “non-gamed” jobs, and using that data to train a predictive model. This would allow for more nuanced, data-driven detection rather than relying solely on rigid thresholds.

---

**What other techniques would you be interested in using in your project?**  
In the Quarter 2 Project, I’d like to incorporate techniques such as anomaly detection, clustering, and natural language processing (NLP) to better understand work order patterns. For instance, anomaly detection could help identify unusual time or scheduling behaviors automatically, while clustering could group similar job types to analyze performance consistency. Predictive modeling or time series analysis could also be valuable for forecasting workload or detecting scheduling inefficiencies. These approaches would deepen insight into operational performance while helping optimize SDG&E’s field service planning.
