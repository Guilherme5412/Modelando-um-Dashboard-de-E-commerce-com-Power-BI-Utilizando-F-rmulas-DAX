Projeto de Modelagem Dimensional com Financial Sample

Descrição

Este projeto utiliza a tabela de amostra financeira (Financial Sample) para criar um modelo dimensional baseado em um esquema estrela. O objetivo é organizar os dados em tabelas dimensão e fato, facilitando a análise e visualização no Power BI.

Estrutura do Modelo
Financials_origem: Cópia da tabela original usada como backup (oculta).
D_Produtos: Contém informações agregadas sobre os produtos (médias, valores máximos e mínimos).
D_Produtos_Detalhes: Detalhes sobre preço de venda, unidades vendidas e bandas de desconto.
D_Descontos: Relaciona os produtos com as bandas e taxas de desconto.
D_Calendário: Gerada com a função DAX CALENDAR(), inclui datas para análises temporais.
F_Vendas: Tabela fato que reúne dados de vendas como unidades vendidas, preço, lucro, e relaciona com as dimensões.
Funcionalidades
Utilização de funções DAX para criação de colunas e medidas.
Modelo de dados estruturado em um esquema estrela para otimizar a análise.

Como Usar
Clone o repositório:
git clone https://github.com/Guilherme5412/Modelando-um-Dashboard-de-E-commerce-com-Power-BI-Utilizando-F-rmulas-DAX

Abra o arquivo .pbix no Power BI para explorar o modelo e as visualizações.

