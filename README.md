# 📉 Análise Preditiva de Evasão de Clientes (Churn Prediction)

## 💡 Visão Geral do Projeto

Este projeto utiliza **Machine Learning (Regressão Logística)** para prever a probabilidade de um cliente **evadir (Churn)**, permitindo à empresa implementar ações preventivas, reduzir custos de aquisição e personalizar estratégias de retenção.

A precisão na identificação dos clientes de risco permite alocar recursos de forma eficiente, focando a equipe de retenção apenas nos clientes com maior probabilidade de evasão.

---

## ⚙️ Metodologia e Valor de Negócio

| Fase | Técnica | Valor para o Negócio |
| :--- | :--- | :--- |
| **Previsão** | Regressão Logística | Classificação binária do risco de Churn (0 ou 1) e cálculo da **Probabilidade de Evasão**. |
| **Ação Preventiva** | *Scoring* de Risco | Identificação de clientes com alta probabilidade (> 60%), permitindo intervenção direcionada antes da evasão. |
| **Personalização** | **Análise de Coeficientes** | Descobre quais fatores (ex: Suporte, Contrato) têm maior impacto na decisão do cliente. |

---

## ✅ Análise e Estratégias de Redução de Custos

A análise dos coeficientes do modelo revelou os principais *drivers* de evasão:

1.  **Tempo de Contrato (Impacto: -0.59):** É o fator mais forte para a retenção. **Estratégia:** Criar programas de fidelidade e descontos progressivos para incentivar contratos mais longos.
2.  **Uso de Suporte Técnico (Impacto: +0.21):** O alto uso de suporte é um sinal de insatisfação. **Estratégia (Redução de Custos):** Investir em FAQs robustos e chatbots para resolver problemas simples imediatamente, reduzindo a carga do suporte e **melhorando a experiência** (Redução de custo de atendimento).

### 🔔 Exemplo de Ação Preditiva

* **Cenário:** Novo cliente com baixo tempo de contrato, alto valor mensal e alto uso de suporte.
* **Previsão do Modelo:** **Probabilidade de Evasão: 1.00** (Risco Máximo).
* **Ação Imediata:** Ação de Retenção Personalizada (Oferta de Desconto ou Suporte Dedicado) para minimizar o custo da perda do cliente.
