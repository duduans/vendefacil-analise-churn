# Análise de Churn e Retenção de Clientes — VendeFácil

## 📌 O Problema de Negócio
A VendeFácil, SaaS B2B de e-commerce, enfrentava estagnação da base e queda de MRR. A diretoria precisava entender **quais sinais de uso, atraso de pagamento e satisfação estavam mais associados ao cancelamento** de clientes.

## 🎯 Objetivo
Identificar os principais preditores de churn e propor um plano de ação para reduzir a taxa de cancelamento de **21,67% para 14%**.

## 🛠️ Ferramentas e Metodologia
- **Power BI**: Modelagem em star schema (fato_vendas + dimensões) e criação de dashboard executivo com 15 medidas DAX.
- **Excel/Power Query**: Tratamento e padronização dos dados.
- **GitHub**: Versionamento e documentação do projeto.

## 📊 Principais Insights
1.  **Engajamento é Chave**: Clientes com **6 a 20 logins/mês** concentram **62,82%** dos cancelamentos. Baixo uso é o maior preditor de churn.
2.  **Atraso de Pagamento**: Clientes cancelados atrasam **2,2x mais** (4,19 dias vs 1,89 dias dos ativos).
3.  **Plano Básico**: Concentra a maior taxa de churn (**29,65%**), **3x maior** que o Enterprise (9,43%).
4.  **Canal de Aquisição**: Clientes vindos de **Redes Sociais** têm a maior taxa de churn (**32%**).

## 📈 Resultados e Impacto
- **Gestão de 360 clientes** e **3.021 registros** de cliente/mês (2025).
- **Meta**: Redução de churn para **14%**, com retenção projetada de **~14 clientes/semestre**.
- **Dashboard Executivo**: Visão integrada de KPIs (MRR, CSAT, Churn) para tomada de decisão.

## 📂 Estrutura do Repositório
- `data/`: Bases de dados brutas e tratadas.
- `powerbi/`: Arquivo do dashboard (.pbix).
- `docs/`: Relatório final e documentação técnica.

## 👥 Autores e Contribuições

Projeto desenvolvido em grupo na pós-graduação em Análise de Dados e IA (CESAR School).

- **Fernanda Falchetto** 
- **Lucas Ramalho** 
- **Eduardo Jungmann**
- **Marcelo Carvalho**
- **Bruno Passo** 
- **Josimar Torre** 