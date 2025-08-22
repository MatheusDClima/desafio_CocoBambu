# 📊 Coco Bambu - Vendas & Orçamento

![Capa do Projeto](https://img.shields.io/badge/Power%20BI-FAAB00?logo=powerbi&logoColor=white&style=for-the-badge) 
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white&style=for-the-badge) 
![DAX](https://img.shields.io/badge/DAX-2E77BC?logo=microsoft&logoColor=white&style=for-the-badge) 
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white&style=for-the-badge)

## Tratamentos dos Dados

### 🔹 Lojas
- Divisão por cidade/UF.  
- Padronização de nomes e renomeação de colunas.  

### 🔹 Campos (Itens/Subitens)
- Ajuste de capitalização.  
- Separação de códigos e descrições para facilitar hierarquia.  
- Colunas originais mantidas (ocultas).  

### 🔹 Fato (Vendas/Orçamento)
- Limpeza de linhas em branco.  
- Substituição de nulos por `0`.  
- Ajuste de POS e renomeação.  

### 🔹 Calendário
- Criado em **Power Query (M)**.  
- Permite análises temporais e comparações **YoY (Year over Year)**.  

---

## 🔗 Relacionamentos
- **Lojas** `1 → *` **Fato**  
- **Campos** `1 → *` **Fato**  
- **Calendário** `1 → *` **Fato**  

---

## 📐 Principais Medidas
- **Valor Real** → Soma das vendas consolidadas.  
- **Valor Orçado** → Soma da meta definida.  
- **Var vs Orçamento (R$ / %)** → Diferença absoluta e percentual.  
- **YoY (ano contra ano)** → Comparação com o mesmo período do ano anterior.  
- **Orçamento YoY** → Evolução da meta em relação ao ano anterior.  
- **Meta Atingida %** → Proporção cumprida em relação ao orçamento.  

---

## 🎨 Layout & Gráficos
- **Identidade Visual**: Paleta da marca, fundo branco para KPIs, menu lateral consistente.  
- **Hierarquia**: KPIs no topo (faturamento, orçamento, variação e YoY).  
- **Cores de Sinalização**: Verde = positivo | Vermelho = negativo.  
- **Filtros**: Ocultos em botão expansível.  
- **Visuais Utilizados**:  
  - Gráfico de colunas → Evolução mensal.  
  - Tabela detalhada → Por loja.  
  - Comparativo de desempenho → Por item/produto.  

---

## 📈 Análise de Resultados – **2025**
O grupo atingiu **R$ 13 bi em receita**, superando **105% da meta** e crescendo **+2,45% vs 2024**.

### 🏬 Lojas
- **Destaque**: Formato **Conceito** (145% da meta).  
- **Atenção**: Buffet em queda (83% da meta).  
- **Top Lojas**: Frutos do Mar, Iguatemi BSB, Passeio das Águas.  
- **Piores Desempenhos**:  
  - BSB Shopping (-19,7%)  
  - PLUS (-27,8%)  
  - Sul (-32,1%)  

### 📦 Produtos
- Receita consolidada: **R$ 14 bi (112% da meta)**.  
- **Destaques**: Frete (+42%), Outras Receitas (+37%), Gorjeta (+15%).  
- **Quedas**: Estacionamento (-28%), Eventos (-5%), Bebidas (-2%).  

---

## ✅ Conclusão
O grupo **superou suas metas** em 2025, mas com **desempenho desigual entre formatos e produtos**.  
Há uma clara oportunidade em **fortalecer canais de expansão** (Conceito, Delivery, Frete) e **reavaliar categorias em retração**, como Buffet, Estacionamento e Eventos.  

🚀 O próximo passo é alinhar estratégias de crescimento focadas nos canais de maior tração e mitigar riscos nas unidades em queda.

---

## Visualizar Projeto

<p align="left">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiNDMxZDU4YWUtZGE2MS00MWI5LTlmMGYtY2IyMWIxNzc2MzE0IiwidCI6IjJhMDk4MzBkLWU2YzYtNDFhNi05NzkzLWM4MzVlZWQyNmQyZiJ9" target="_blank">
    <img src="https://img.shields.io/badge/Power%20BI-Execute-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  </a>
</p>
