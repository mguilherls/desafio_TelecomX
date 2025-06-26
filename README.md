# 📉 TelecomX - Análise de Churn

Projeto de análise de dados com foco na evasão de clientes (churn) da empresa fictícia **Telecom X**. Este desafio propõe identificar os fatores que influenciam o cancelamento de planos e sugerir ações estratégicas para reduzir a taxa de churn.

## 🎯 Objetivo

Identificar padrões de cancelamento com base no perfil do cliente, tipo de contrato, método de pagamento e comportamento de custo. A análise visa fornecer insights acionáveis para retenção de clientes.

## 🧰 Tecnologias e Ferramentas

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## 🛠️ Etapas do Projeto

1. **Importação e Tratamento da Base**  
   - Leitura da base em formato JSON  
   - Normalização, limpeza e padronização das variáveis  
   - Criação da variável `Contas_Diarias` (custo diário por cliente)

2. **Análise Exploratória (EDA)**  
   - Estatísticas descritivas  
   - Distribuição por gênero, idade e tipo de serviço  
   - Frequência de churn por contrato e forma de pagamento  
   - Comportamento de custo por tempo de contrato

3. **Geração de Gráficos**  
   - Gráficos de barras e linhas para visualização comparativa entre clientes com e sem churn

4. **Conclusões e Recomendações**  
   - Custo elevado e contratos mensais estão fortemente associados ao churn  
   - "Electronic check" se mostrou o método de pagamento com maior incidência de cancelamentos  
   - Recomendação de revisão de preços, estímulo a contratos mais longos e melhorias no onboarding

## 📊 Resultados Visuais

O notebook inclui seções dedicadas a gráficos com análise visual para:

- Gênero vs Churn  
- Senioridade vs Churn  
- Tipo de contrato vs Churn  
- Método de pagamento vs Churn  
- Custo diário médio ao longo do tempo

## ✅ Conclusão

A análise conclui que o **preço percebido elevado**, aliado à **baixa fidelização (contratos mensais)** e ao **método de pagamento mais flexível**, são os principais fatores associados à evasão. Estratégias de retenção devem focar em custo-benefício, fidelização e acompanhamento nos primeiros meses.

---

> Projeto desenvolvido por **Matheus Silva** como parte do um challenger do curso de Data Science da Alura.  
> Contribuições, sugestões e feedbacks são bem-vindos!
