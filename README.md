# 🐾 Dashboard de Vendas - Linha Petshop 🐶🐱

<br><br>
📊 **Visão Geral**
<br><br>
Este projeto apresenta um Dashboard Interativo no Power BI desenvolvido para análise de vendas da linha Petshop da empresa fictícia Melhores Compras. 
A solução permite a visualização e interpretação de dados estratégicos para apoiar a tomada de decisão comercial, explorando insights sobre categorias de produtos, regiões de vendas, ticket médio e lucratividade ao longo dos anos.
<br>
O projeto foi desenvolvido como parte de um desafio de Visualização de Dados (DataViz) proposto no curso de Ciência de Dados da FIAP, utilizando conceitos de Self Service Business Intelligence (SSBI) e Knowledge Discovery in Databases (KDD).

<br><br>
🧹 **Tratamento de Dados**
<br><br>
Para garantir a integridade e a qualidade dos dados antes da análise, foram aplicadas algumas transformações:

Remoção de 21 linhas com erros de entrada: algumas linhas apresentavam dados inconsistentes e foram eliminadas para evitar distorções nas análises. Como o dataset possui mais de 250 mil registros, essa remoção de dados não impactou os resultados das análises.

Substituição de valores NULL por 0

Justificativa: Alguns registros continham valores ausentes, e ao investigar, foi identificado que esses campos representavam ausência de vendas. Para evitar impacto negativo nos cálculos agregados, os valores foram substituídos por 0.

Substituição de valores negativos pela média da coluna correspondente

Justificativa: Valores negativos não faziam sentido para métricas como preço e quantidade vendida. Assim, foram substituídos pela média da respectiva coluna para evitar distorções e manter a coerência nos cálculos.

Esses tratamentos foram aplicados para garantir que os dados refletissem com maior precisão a realidade das vendas e permitissem análises mais confiáveis.

<br><br>
🚀 **Funcionalidades**
<br><br>
✅ Análise de Receita Total e Ticket Médio

✅ Distribuição de Vendas por Região do Brasil

✅ Top 5 Produtos Mais Vendidos

✅ Análise de Lucro Bruto e Margem de Lucro (%) ao longo dos anos

✅ Receita por Categoria de Produto

✅ Tendências de Receita ao longo dos anos, trimestres e meses

✅ Interatividade com filtros dinâmicos para segmentação de dados

<br><br>
📂 **Arquivos no Repositório**
<br><br>
📄 README.md → Descrição do projeto (este arquivo)

📊 dash_petshop.pbix → Arquivo do dashboard desenvolvido no Power BI

📄 analise_dashboard.docx → Documento com a análise descritiva do dashboard

<br><br>
🛠 **Como Executar**
<br><br>
1️⃣ Baixe o arquivo dash_petshop.pbix

2️⃣ Abra o Power BI Desktop

3️⃣ Carregue o arquivo .pbix

4️⃣ Explore os dados e interaja com os gráficos
<br><br>
💡 Observação: O arquivo PBIX foi salvo com os dados carregados para que não seja necessário o upload do arquivo de origem (Excel). 

## 🌐 Acesse o Dashboard Online  
🔗 [Visualizar no Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiMDE1YjEyMjYtZjJmZS00Njk5LWI3YWItYzJkZDIxNGI0OThmIiwidCI6IjExZGJiZmUyLTg5YjgtNDU0OS1iZTEwLWNlYzM2NGU1OTU1MSIsImMiOjR9)
