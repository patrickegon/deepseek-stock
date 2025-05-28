[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# DeepSeek: Análise de Impacto Tecnológico e Mercadológico

## **Sumário**
<!--ts-->
* [Introdução do Projeto](#intro)
* [Contexto: DeepSeek](#contexto)
* [Resumo Executivo](#resumo)
* [1. Introdução ao DeepSeek](#introducao)
* [2. Tecnologia e Inovações](#tecnologia)
* [3. Impacto no Mercado](#impacto)
* [4. Caso de Uso: FinRL-DeepSeek](#caso-uso)
* [5. Ecossistema Open-Source](#ecossistema)
* [6. Conclusão](#conclusao)
* [Referências](#referencias)
* [Contato](#contato)
<!--te-->

---

<a name="intro"></a>
## **Introdução do Projeto**
Aplicação dos conhecimentos do Módulo 3 (Séries Temporais) do Bootcamp de Data Science Aplicada da Alura.  
**Principais técnicas utilizadas**:
- Estatística descritiva
- Análise exploratória de dados
- Modelos de previsão (StatsModels e Prophet)

📊 **Notebook Completo**:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/vqrca/bootcamp_alura_projeto_3/blob/main/Notebooks/Projeto_3_Valquiria_Alencar.ipynb)  
> *Recomendado: Visualização otimizada no Google Colab*

---

<a name="contexto"></a>
## **🧠 Contexto: DeepSeek - A Revolução da IA Aberta**
Startup chinesa fundada em **julho de 2023** (Hangzhou) que lançou modelos de IA com:
- Custo computacional 90% menor que concorrentes
- Consumo energético drasticamente reduzido
- Modelo inicial: **DeepSeek-R1** (jan/2025)
- Modelo avançado: **DeepSeek-V3** (671B parâmetros)

> *Fontes: [Wikipedia](https://en.wikipedia.org/wiki/DeepSeek), [PBS](https://------------------)*

---

<a name="resumo"></a>
## **📌 Resumo Executivo**
| Área               | Destaque                                                                 |
|--------------------|--------------------------------------------------------------------------|
| **Fundação**       | Julho/2023 por Liang Wenfeng (Hangzhou)                                  |
| **Modelo R1**      | Desempenho comparável ao GPT-4 com custo computacional 10x menor         |
| **Modelo V3**      | 671B parâmetros, ativação de 37B/token via MoE                           |
| **Custo Treino**   | US$ 6 mi (vs. US$ 100 mi do GPT-4)                                       |
| **Eficiência**     | 10% do consumo energético de modelos equivalentes                        |
| **Impacto**        | Queda de US$ 593 bi na capitalização da NVIDIA (jan/2025)                |

---

<a name="introducao"></a>
## **1. 🚀 Introdução ao DeepSeek**
- **Fundação**: Julho/2023 em Hangzhou
- **Liderança**: Liang Wenfeng
- **Filosofia**: 
  - Modelos *open-weight* 
  - Democratização de IA avançada
  - Foco em eficiência energética
- **Reconhecimento**:  
  > *"Um presente para a indústria global de IA"* - **Jensen Huang** (CEO da NVIDIA)

---

<a name="tecnologia"></a>
## **2. ⚙️ Tecnologia e Inovações**
### **Arquitetura MoE (Mixture-of-Experts)**
- Ativação dinâmica de especialistas (37B/token)
- Redução de 85% no uso de GPUs
- Balanceamento de carga inteligente

### **Multi-head Latent Attention (MLA)**
- Processamento paralelo otimizado
- Redução de perdas computacionais

### **Sustentabilidade**
| Métrica               | DeepSeek-V3 | Concorrentes |
|-----------------------|-------------|--------------|
| Custo Treinamento     | US$ 6 mi    | US$ 100 mi   |
| Consumo Energético    | 10%         | 100%         |
| Margem Operacional    | 545%        | 20-40%       |

---

<a name="impacto"></a>
## **3. 📉 Impacto no Mercado**
### **Efeito na NVIDIA**
- Queda diária recorde: **US$ 593 bi** (jan/2025)
- Recuperação posterior: **+43%** em 2026
- *Fonte: [Financial Times](https://www.ft.com)*

### **Reações da Indústria**
> *"Como alcançaram custos tão baixos?"*  
> **Demis Hassabis** (DeepMind) - *The Australian*

### **Disrupção**
- Redefinição de expectativas de custo em IA
- Aceleração de modelos *open-source*
- Pressão competitiva em big techs

---

<a name="caso-uso"></a>
## **4. 📊 Caso de Uso: FinRL-DeepSeek**
**Objetivo**: Trading algorítmico no **Nasdaq-100** usando:
- DeepSeek-V3 (base)
- Deep Reinforcement Learning (FinRL)

**Resultados (2019-2023)**:
| Métrica          | DeepSeek-V3 | Benchmarks |
|------------------|-------------|------------|
| Information Ratio| **2.1**     | 0.8-1.4    |
| CVaR (95%)       | **-1.2%**   | -2.5%      |

**Repositório**:  
[FinRL-DeepSeek](https://github.com/benstaf/FinRL_DeepSeek)

---

<a name="ecossistema"></a>
## **5. 🌐 Ecossistema Open-Source**
| Projeto                           | Repositório                           |
|-----------------------------------|---------------------------------------|
| DeepSeek-V3 (MoE + MLA)           | [github.com/deepseek-ai/DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3) |
| Sistema de Arquivos 3FS           | [github.com/deepseek-ai/3FS](https://github.com/deepseek-ai/3FS) |
| Integrações & Ferramentas         | [github.com/Zodoge/Awesome-DeepSeek-Integration](https://github.com/Zodoge/Awesome-DeepSeek-Integration) |

---

<a name="conclusao"></a>
## **6. 📌 Conclusão**
- **Disrupção comprovada**: IA de alto desempenho com baixo custo
- **Modelo sustentável**: Eficiência energética revolucionária
- **Democratização**: Ecossistema open-source robusto
- **Impacto financeiro**: Reconfiguração do mercado de chips e IA

> *"DeepSeek redefiniu o possível na economia de IA" - Nature (2025)*

---

<a name="referencias"></a>
## **📚 Referências**
1. [DeepSeek AI - Wikipedia](https://en.wikipedia.org/wiki/DeepSeek)
2. The Economist: *"DeepSeek: The Quiet Giant Leading China's AI Race"* (Jan/2025)
3. NYT: *"How Chinese A.I. Start-Up DeepSeek Is Competing With Giants"* (Jan/2025)
4. [DeepSeek-V3 Technical Paper](https://github.com/deepseek-ai/DeepSeek-V3)
5. Financial Times: *"DeepSeek’s success will undermine the US-China tech war"* (Feb/2025)
6. *[Full references list in notebook]*

---

<a name="contato"></a>
## **👤 Contato**
**Patrick Santos**  
[![Medium](https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white)](-----------)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](-----------)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=researchgate&logoColor=white)](-----------)
[![Lattes](https://img.shields.io/badge/Lattes-1E5D8C?style=flat&logo=google-scholar&logoColor=white)](--------)
