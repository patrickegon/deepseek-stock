[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# DeepSeek: Technological and Market Impact Analysis

## **Table of Contents**
<!--ts-->
* [Project Introduction](#intro)
* [Context: DeepSeek](#contexto)
* [Executive Summary](#resumo)
* [1. Introduction to DeepSeek](#introducao)
* [2. Technology and Innovations](#tecnologia)
* [3. Market Impact](#impacto)
* [4. Use Case: FinRL-DeepSeek](#caso-uso)
* [5. Open-Source Ecosystem](#ecossistema)
* [6. Conclusion](#conclusao)
* [References](#referencias)
* [Contact](#contato)
<!--te-->

---

<a name="intro"></a>
## **Project Introduction**
📈 Big Tech Stock Market Analysis (2010–2025)

This project aims to perform a comprehensive analysis and predictive modeling based on the historical stock data of five major technology companies: Apple (AAPL), Amazon (AMZN), Google (GOOGL), Microsoft (MSFT), and NVIDIA (NVDA). 
By utilizing a range of statistical modeling and machine learning techniques, the analysis seeks to uncover market behavior patterns, forecast future trends, and provide valuable insights into the impact of big tech stocks on financial market dynamics.

The dataset spans 15 years of daily data (from 01/01/2010 to 01/05/2025) and includes:

- Opening, closing, high, and low prices for each stock
- Daily trading volume for each company
- Relevant indicators for temporal analysis and inter-company comparisons

**Main Techniques Used**:
🎯 Project Objectives

The main goal is to explore and predict stock movements using various time series modeling and ML techniques:

- Exploratory Data Analysis (EDA): Investigating market behavior
- Trend Visualization: Graphical representations of market fluctuations
- Future Price Forecasting using:
    - ARIMA/SARIMAX: Classical time series models
    - Prophet (Meta): Seasonal forecasting
    - LSTM/Transformers: Deep learning models
    - Multivariate Regression: Inter-company prediction models

🛠️ Libraries Used
- pandas, numpy: Data manipulation
- matplotlib, seaborn: Visualization
- plotly: Interactive plotting
- statsmodels: Time series modeling
- scikit-learn: ML pipelines
- prophet: Time series forecasting

📊 **Complete Notebook**:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/patrickegon/deepseek-stock/notebook)  

---

<a name="contexto"></a>
## **🧠 Context: DeepSeek - The Revolution of Open AI**
Chinese startup founded in July 2023 in Hangzhou that launched AI models with:
- 90% lower computational costs than competitors
- Drastically reduced energy consumption
- Initial model: DeepSeek-R1 (Jan 2025)
- Advanced model: DeepSeek-V3 (671B parameters)
- Open Source code and scientific article


> *Sources: [Wikipedia](https://en.wikipedia.org/wiki/DeepSeek), [PBS](https://------------------)*

---

<a name="resumo"></a>
## **📌 Executive Summary**
| Area               | Highlight                                                                 |
|--------------------|--------------------------------------------------------------------------|
| **Foundation**     | July 2023 by Liang Wenfeng (Hangzhou)                                    |
| **R1 Model**       | GPT-4 comparable performance at 10x lower computational cost             |
| **V3 Model**       | 671B parameters, 37B/token activation via MoE                           |
| **Training Cost**  | $6M (vs. GPT-4's $100M)                                                 |
| **Energy Eff.**    | 10% of competitors' energy consumption                                  |
| **Market Impact**  | $593B NVIDIA market cap drop (Jan 2025)                                 |

---

<a name="introducao"></a>
## **1. 🚀 Introduction to DeepSeek**
- **Foundation**: July 2023, Hangzhou
- **Leadership**: Liang Wenfeng
- **Philosophy**: 
  - *Open-weight* models 
  - Democratization of advanced AI
  - Energy efficiency focus
- **Recognition**:  
  > *"A gift to the global AI industry"* - **Jensen Huang** (NVIDIA CEO)

---

<a name="tecnologia"></a>
## **2. ⚙️ Technology and Innovations**
### **Mixture-of-Experts (MoE) Architecture**
- Dynamic expert activation (37B/token)
- 85% GPU usage reduction
- Intelligent load balancing

### **Multi-head Latent Attention (MLA)**
- Optimized parallel processing
- Reduced computational overhead

### **Sustainability**
| Metric               | DeepSeek-V3 | Competitors |
|-----------------------|-------------|--------------|
| Training Cost         | $6M         | $100M        |
| Energy Consumption    | 10%         | 100%         |
| Operating Margin      | 545%        | 20-40%       |

---

<a name="impacto"></a>
## **3. 📉 Market Impact**
### **Effect on NVIDIA**
- Record single-day drop: **$593B** (Jan 2025)
- Subsequent recovery: **+43%** in 2026
- *Source: [Financial Times](https://www.ft.com)*

### **Industry Reactions**
> *"How did they achieve such low costs?"*  
> **Demis Hassabis** (DeepMind) - *The Australian*

### **Disruption**
- Redefining AI cost expectations
- Accelerating open-source models
- Competitive pressure on big tech

---

<a name="caso-uso"></a>
## **4. 📊 Use Case: FinRL-DeepSeek**
**Objective**: Algorithmic trading on **Nasdaq-100** using:
- DeepSeek-V3 (base)
- Deep Reinforcement Learning (FinRL)

**Results (2019-2023)**:
| Metric          | DeepSeek-V3 | Benchmarks |
|------------------|-------------|------------|
| Information Ratio| **2.1**     | 0.8-1.4    |
| CVaR (95%)       | **-1.2%**   | -2.5%      |

**Repository**:  
[FinRL-DeepSeek](https://github.com/benstaf/FinRL_DeepSeek)

---

<a name="ecossistema"></a>
## **5. 🌐 Open-Source Ecosystem**
| Project                           | Repository                           |
|-----------------------------------|---------------------------------------|
| DeepSeek-V3 (MoE + MLA)           | [github.com/deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) |
| 3FS File System           | [github.com/deepseek-ai/3FS](https://github.com/deepseek-ai/3FS) |
| Integrations & Tools         | [github.com/Zodoge/Awesome-DeepSeek-Integration](https://github.com/Zodoge/Awesome-DeepSeek-Integration) |

---

<a name="conclusao"></a>
## **6. 📌 Conclusion**
- **Proven disruption**: High-performance AI at low cost
- **Sustainable model**: Revolutionary energy efficiency
- **Democratization**: Robust open-source ecosystem
- **Financial impact**: Chip market reconfiguration

> *"DeepSeek redefined what's possible in AI economics" - Nature (2025)*

---

<a name="referencias"></a>
## **📚 References**
1. [DeepSeek AI - Wikipedia](https://en.wikipedia.org/wiki/DeepSeek)
2. The Economist: *"DeepSeek: The Quiet Giant Leading China's AI Race"* (Jan 2025)
3. NYT: *"How Chinese A.I. Start-Up DeepSeek Is Competing With Giants"* (Jan 2025)
4. [DeepSeek-V3 Technical Paper](https://github.com/deepseek-ai/DeepSeek-V3)
5. Financial Times: *"DeepSeek's success will undermine the US-China tech war"* (Feb 2025)
6. *[Full references list in notebook]*

---

<a name="contato"></a>
## **👤 Contact**
**Patrick Santos**  
[![Medium](https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white)](-----------)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](-----------)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=researchgate&logoColor=white)](-----------)
[![Lattes](https://img.shields.io/badge/Lattes-1E5D8C?style=flat&logo=google-scholar&logoColor=white)](--------)
