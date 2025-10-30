
# Análise de Vendas de Produtos Fitness

## Contexto

Essa análise foi desenvolvida a partir de uma **base de dados fictícia** contendo informações de **vendas de produtos fitness**.  
O objetivo é identificar padrões e oportunidades de melhoria a partir de dados sobre **produtos, fornecedores, estados, fretes, e status de pedidos**.

---

## Objetivo da Análise

Explorar os dados para responder às seguintes perguntas:

1. Qual é o **comportamento geral das vendas**?
2. Quais são os **fornecedores e regiões com melhor desempenho**?
3. Quais **categorias e produtos mais contribuem** para o faturamento total?
4. Existem **custos elevados ou ineficiências** relacionados ao frete?
5. Há **oportunidades de otimização** com base no status das vendas (ex: cancelamentos)?
    

---

## Estrutura de Análise

A análise foi conduzida de forma exploratória, utilizando o **Microsoft Excel**, com:

- **Tabelas dinâmicas** para agregações por fornecedor, categoria e região;
    
- **Fórmulas** para cálculos de médias, percentuais e proporções;
    
- **Visualizações** para destacar métricas de desempenho e evolução temporal.


## Principais Métricas Calculadas

| Métrica                              | Valor / Insight            | Interpretação                                                 |
| ------------------------------------ | -------------------------- | ------------------------------------------------------------- |
| Valor médio de compra                | **R$ 219,32**              | Indica o ticket médio por pedido.                             |
| Quantidade média de itens por compra | **3 itens**                | Mostra o volume médio de produtos por transação.              |
| Percentual médio de frete            | **≈10%** do total          | Representa o custo médio de frete sobre o valor da compra.    |
| % de pedidos cancelados              | **~10% do total em valor** | Pode indicar problema de logística, comunicação ou pagamento. |


##  Análise Geral

###  Volume e Distribuição das Vendas

- O **frete representa cerca de 10%** do valor total das compras — um percentual considerado razoável, mas que merece atenção em fornecedores com fretes muito acima da média.
    
- A **média de 3 itens por compra** mostra que os clientes tendem a comprar pacotes pequenos, o que pode indicar um comportamento de reposição frequente (não compras grandes ocasionais).
    
- O **valor médio por compra (R$ 219,32)** pode servir de benchmark para campanhas promocionais e estratégias de fidelização.
    

---

###  Fornecedores

- Há **múltiplos fornecedores repetidos** na base, o que indica recorrência de compras e permite medir frequência e desempenho.
    
- Na análise o **Fornecedor 9** apresenta bom desempenho de custo-benefício: **maior volume de compras e frete proporcionalmente menor**.
    
- Já o **Fornecedor 6** tem **frete alto em relação ao valor da compra**, o que pode indicar necessidade de renegociação ou substituição.
    

**Insight acionável:** renegociar fretes com o fornecedor 6 ou priorizar compras com fornecedores que apresentam menor custo logístico por pedido.

---

###  Produtos e Categorias

- O produto **“Whey Hidrolisado”** representa **3,5% do total das vendas**, sendo o **produto com maior participação individual**.
    
- A categoria **“Proteínas”** domina as vendas com **≈ 39,99% do total**, seguida por outras 6 categorias que, somadas, **representam mais de 80% do faturamento**.
    

**Insights acionáveis:**

1. Investir em **campanhas de marketing voltadas para as categorias líderes**, como “Proteínas”, reforçando o produto de maior saída.
    
2. Paralelamente, promover **ações de incentivo para as categorias com menor participação**, avaliando o impacto após campanhas.
    
3. Manter um **controle de estoque focado nas 7 categorias mais relevantes**, já que elas respondem pela maior parte da receita.
    

---

###  Análise Temporal

- A análise das **datas das vendas** permite acompanhar a evolução do faturamento, número de pedidos e valor médio ao longo dos meses.
    
- Com base na contagem das **notas fiscais**, é possível observar **picos ou quedas sazonais** e ajustar a previsão de estoque e campanhas promocionais.
    

**Insight acionável:** desenvolver um **painel mensal de acompanhamento** para medir tendências e definir metas trimestrais baseadas na evolução do ticket médio.

---

###  Regiões e Estados

- As regiões **Rio Grande do Sul, Sergipe e Tocantins** apresentam **maiores volumes de vendas** e **fretes proporcionais mais baixos** — ótimo indicativo logístico.
    
- Em contrapartida, regiões com **menor volume de vendas e frete alto** podem estar sendo impactadas por distância geográfica ou baixa densidade de pedidos.
    

**Insight acionável:** concentrar campanhas e estoques em regiões com melhor relação **venda x custo logístico**, enquanto busca alternativas de transporte para otimizar o frete em regiões menos rentáveis.

---

###  Status das Vendas

- Quase **10% do valor total está em pedidos cancelados**, o que exige atenção.
    
- O cruzamento entre **status e fornecedor** pode indicar quais parceiros estão contribuindo para o alto índice de cancelamento.
    

**Insight acionável:**

1. Investigar causas dos cancelamentos (estoque, erro de processamento, atraso de entrega).
2. Criar um **indicador de taxa de cancelamento por fornecedor** para monitorar desempenho.
3. Reavaliar fornecedores com alta taxa de cancelamento ou reembolso.




##  Próximos Passos

- Montar um **dashboard dinâmico** no Excel ou Power BI com os principais indicadores:
    
    - Receita total
    - Frete médio
    - Ticket médio
    - % cancelamentos
    - Vendas por categoria / região
        
- Repetir a análise mensalmente para acompanhar evolução e identificar tendências.
- Integrar futuramente com dados reais de clientes ou e-commerce para análises preditivas.
    

---

##  Ferramentas Utilizadas

- **Microsoft Excel**
    
    - Tabelas dinâmicas
    - Funções de agregação (SOMASES, MÉDIASES, CONT.SES)
    - Gráficos dinâmicos
    - Análise percentual e rankings
        

---

## Impacto Esperado

Com base nas análises, é possível:

- Reduzir custos logísticos via renegociação de frete;
- Aumentar faturamento com foco em categorias mais lucrativas;
- Minimizar cancelamentos através de monitoramento de fornecedores;
- Melhorar decisões estratégicas com base em dados reais e mensuráveis.
