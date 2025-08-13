## Overview

### Project Description
This project explores the application of large language models (LLMs) as an early warning system to identify depression in patients with cardiovascular disease (CVD) through analysis of patient portal messages. By leveraging LLMs, we aim to overcome existing barriers to timely depression diagnosis, potentially transforming mental health screening processes for chronic diseases.

---

### Objectives
- **Simulate Impact**: Prospectively simulate the impact of population mental health screening using LLMs by analyzing patient portal messages.  
- **Measure Accuracy**: Evaluate the accuracy of LLMs in identifying individuals at high risk for depression among patients with CVD.  
- **Assess Time to Diagnosis**: Quantify changes in time to depression diagnosis facilitated by LLMs.  

---

### Study Design
- **Type**: Prospective cohort study  
- **Setting**: Electronic health records from Stanford Health Care  
- **Participants**: Individuals diagnosed with CVD between 2014–2024, subsequently diagnosed with depression  

---

### Main Outcomes
**Accuracy Metrics**:
- **Sensitivity** for completeness in capturing positive cases  
- **Positive Predictive Value (PPV)** for correctness in capturing positive cases  

**Time to Diagnosis**:
- Reduction in time to depression diagnosis

---

### Results
- **Patient Cohort**: 115,156 patients with CVD; 23.1% (26,578) had co-morbid depression  
- **Message Analysis**: 2,314 individuals sent messages between CVD and depression diagnoses  
- **Demographics**: Predominantly aged 65+, non-Hispanic ethnicity, White race, balanced sex distribution  

**Performance**:
- **PPV**: 51.2% [95% CI: 47.5–54.5%] for Llama 3.1 8B  
- **Sensitivity**: 83.6% [81.1–85.9] for Llama 3.1 8B; 71.0% [67.0–75.3] for MedGemma 4B  
- **Detection Time**: LLM detected depression **660 days earlier** than first charted diagnosis  

---

### Conclusion
LLMs demonstrated significant potential in identifying depression earlier than official diagnoses among CVD patients, relying solely on patient messages. This approach, with high sensitivity and comparable PPV to the Patient Health Questionnaire-9, is applicable to various diagnoses, offering a novel use for patient message data.


<img width="472" height="634" alt="image" src="https://github.com/user-attachments/assets/b77f2b75-aceb-42dd-99c4-a91713d04ac2" />
