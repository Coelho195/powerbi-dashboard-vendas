# powerbi-dashboard-vendas
Meu primeiro projeto em Power BI. Dashboard de vendas de uma loja fictícia, criado para praticar modelagem de dados, construção de KPIs em DAX e visualizações interativas.

Criei um cenário fictício de uma loja de varejo para simular um ambiente real de análise de dados.

---

## 🛠️ Etapas do Projeto
- *Estudo da Teoria:* conceitos de modelagem de dados.
- *Criação do Cenário:* loja fictícia de varejo (apoio do ChatGPT).
- *Montagem das Planilhas:* separação em tabelas de fato e dimensões.
- *Construção no Power BI:* importação, transformação e criação do dashboard final.

---

## 📌 KPIs Criados
- *Total Vendas:* SUMX(Fato_Vendas, Fato_Vendas[Quantidade] * Fato_Vendas[Valor_Unitário])
- *Total Quantidade:* SUM(Fato_Vendas[Quantidade])
- *Ticket Médio:* [Total Vendas] / [Total de Vendas Realizadas]
- *Total de Vendas Realizadas:* COUNT(Fato_Vendas[ID_Venda])

---

## 📊 Visualizações Utilizadas
- Gráfico de rosca
- Gráfico de colunas agrupadas e linhas
- Gráfico de barras clusterizado
- Hierarquia interativa

---

✍️ Esse foi meu primeiro passo no Power BI. Fico aberta a feedbacks e sugestões!
