## 📡 Diagnóstico Preditivo de Evasão de Clientes em Telecom

> **"Prever o churn é só o começo: o desafio é entender o porquê, agir a tempo e fidelizar.”**

## 🚀 Sobre o Projeto

Este repositório conduz uma jornada completa — desde a exploração de dados à implementação e comparação de modelos preditivos — com o objetivo de combater a evasão de clientes em uma operadora de telecom. O enfoque não está apenas em identificar quem vai sair, mas em produzir aprendizados e soluções práticas para retenção.

## 🎯 Objetivos

- Detectar padrões e fatores determinantes para o churn.
- Construir modelos de Machine Learning robustos para previsão da evasão.
- Testar e comparar métodos de normalização, balanceamento (SMOTE) e diferentes algoritmos.
- Apresentar métricas claras para orientar ações na área de retenção.
- Traduzir resultados em recomendações práticas.

## 🧰 Tecnologias e Ferramentas

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn, imbalanced-learn, xgboost
- Jupyter Notebook

## 🏆 Modelos Construídos

- **Regressão Logística + SMOTE**
    - Requer normalização dos dados.
    - Traz interpretabilidade dos coeficientes e clareza nos fatores de risco.
    - Métricas: recall e F1-score superiores, ideal para flagrar clientes em risco.

- **Random Forest + SMOTE**
    - Não precisa de normalização.
    - Captura relações e dependências não-lineares entre as variáveis.
    - Maior precisão geral, fácil adaptação para dados mistos.

- **XGBoost + SMOTE**
    - Boosting eficiente e indicado para tabelas com muitos atributos.
    - Ótimo gerenciamento de outliers e variáveis colineares.
    - Reforça variáveis críticas para o churn, apesar de neste conjunto não superar Logística em recall/F1.

## 📊 Resultados do Comparativo

| Métrica     | Logística | Random Forest | XGBoost |
|-------------|-----------|--------------|---------|
| Acurácia    | 0.7611    | 0.7616       | 0.7588  |
| Precisão    | 0.5287    | 0.5337       | 0.5294  |
| Recall      | 0.6578    | 0.5793       | 0.5615  |
| F1-score    | 0.5862    | 0.5556       | 0.5450  |

- **Regressão Logística** destacou-se no recall e F1-score: identifica mais clientes em risco real de saída.
- **Random Forest/XGBoost** têm desempenho geral semelhante, com ligeira vantagem em precisão.
- Todos os modelos, por meio do SMOTE, respeitaram o equilíbrio das classes durante o treino.

## 🔎 Insights Principais

- 💸 **Planos e cobranças elevadas** aceleram a evasão.
- 📅 **Contratos mensais** representam risco; contratos longos protegem.
- 🤝 **Clientes antigos, com dependentes ou parceiros** mostram maior permanência.
- 📡 **Qualidade percebida** em fibra óptica importa; necessidade de alinhar expectativa e entrega.
- 🔑 **Atendimento e suporte técnico** diferenciam o churn do engajamento.

## 💡 Recomendações Aplicáveis

1. Ofereça planos e benefícios personalizados de acordo com o ciclo de vida do cliente.
2. Aposte em comunicação proativa e canais de ESCUTA (NPS, SAC, acompanhamento digital).
3. Crie programas para amarrar laços familiares e premiar fidelidade.
4. Monitore sinais precoces de insatisfação e aja nos primeiros meses.
5. Invista em qualidade de infraestrutura e disponibilidade de suporte.

## 🏁 Próximos Passos

- Testar ajustes finos em hiperparâmetros e modelos de última geração (LightGBM, CatBoost).
- Explorar variáveis temporais, de engajamento e comportamento de navegação.
- Desenvolver dashboards interativos para uso de equipes de negócio.

## ✍️ Autoria

Desenvolvido por **Andre Mateus Passos**  

🎮 Tecnólogo em Jogos Digitais  
🗄️ Administrador de Banco de Dados  
📊 Entusiasta de Ciência de Dados

> “Clientes querem se sentir únicos. Ciência de dados é a ponte entre tecnologia e experiência personalizada.”

🔗 **Veja o projeto completo:**  
[https://github.com/Edracky/TelecomX-Parte-2](https://github.com/Edracky/TelecomX-Parte-2)


