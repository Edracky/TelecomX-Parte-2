# 📡 Detecção Inteligente de Evasão de Clientes em Telecom

> **“Não basta prever a saída. É preciso decifrar por que o cliente pensa em ir embora.”**

## 🚀 Sobre o Projeto

Este repositório traz uma jornada completa: desde a exploração de dados, construção e comparação de modelos preditivos até a extração de insights práticos para retenção de clientes em uma operadora fictícia de telecomunicações. O grande diferencial? Usamos ciência de dados não só para prever o futuro — mas para fundamentar decisões estratégicas de verdade.

## 🎯 Objetivos

- **Mapear padrões de evasão** analisando todo o perfil do cliente
- **Utilizar Machine Learning** para prever quem está prestes a sair
- **Comparar modelos com e sem normalização** e técnicas de balanceamento (SMOTE)
- **Identificar variáveis-chave** que influenciam o churn
- **Traduzir resultados em recomendações objetivas** para reter clientes

## 🧰 Tecnologias & Ferramentas

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn, imbalanced-learn
- Jupyter Notebook

## 🏆 Abordagens Testadas

### 1. **Regressão Logística + SMOTE**
- Ideal para interpretar o papel de cada variável
- Requer normalização (StandardScaler)
- Destaque: **Encargos Mensais, Encargos Totais, Tempo de Serviço** ganham força como motores de churn

### 2. **Random Forest + SMOTE**
- Capta relações não-lineares e interações complexas
- Não exige normalização
- Principais influenciadores: **Tempo de Serviço, Encargos Totais, Tipo de Contrato**

## 🔍 Principais Descobertas

- 💸 **Custo importa (muito):** planos caros e cobranças altas aceleram a evasão.
- 📅 **Contratos curtos** (mensais) sinalizam risco; contratos longos (bienais) são protetores.
- 🤝 **Engajamento e vínculo:** clientes antigos, com dependentes ou parceiros, permanecem mais tempo.
- 📡 **Infraestrutura pesa:** ter fibra óptica é importante, mas expectativas e custos precisam ser geridos.
- 🔑 **Qualidade e suporte:** atributos como segurança online e atendimento técnico retêm clientes.

## 📊 Resultados e Métricas

| Modelo                    | Acurácia | Precisão | Recall  | F1-score |
|---------------------------|:--------:|:--------:|:-------:|:--------:|
| Regressão Logística (SMOTE) | 0.761 | 0.529   | 0.658   | 0.586    |
| Random Forest (SMOTE)     | 0.765    | 0.538    | 0.626   | 0.578    |

- Reg. Logística: melhor para identificar desperdícios (maior recall)
- Random Forest: mais equilibrada, ligeiro ganho em acurácia e precisão global

## 💡 O que fazer com esses insights?

1. **Ajustar planos, taxas e benefícios** conforme o perfil e tempo de casa do cliente.
2. **Investir em comunicação personalizada e relacionamento** — não só descontos.
3. **Atuar rápido nos primeiros sinais de insatisfação** (exemplo: contato proativo para clientes novos).
4. **Valorizar os laços familiares** (programas “indique um amigo” e benefícios para dependentes).
5. **Monitorar a experiência do cliente** constantemente, com NPS, SAC e dados de uso.

## 🐾 Próximos Passos

- Testar modelos de última geração (e.g., XGBoost, LightGBM)
- Explorar dados temporais e dinâmicas de jornada do cliente
- Criar dashboards dinâmicos para acompanhamento em tempo real

## ✍️ Autoria & Contato

Desenvolvido por **Carolini Rufino**  
Data Science Enthusiast | Secretária | Bacharel em Administração

> “Mais do que segurar clientes, queremos criar experiências que façam cada um deles querer ficar.”

Se quiser, personalize com sua identidade visual, inclua logo, badges do GitHub ou links para notebooks!

[1] 
