# Estudo de caso 1:
## Vendas da empresa XYZ Corporation International no período de 2016 a 2019

**Definição do Problema de Negócio**

Você é Analista de Dados na empresa XYZ Corporation International, uma revendedora de automóveis de luxo com sede em São Paulo. A empresa começou sua operação no Brasil em 2016 e atua nos quatro estados da região sudeste, mais os estados do Paraná e Bahia.

Seu  gerente  vai  apresentar  os  resultados  da equipe  comercial  para  o  novo  CEO  da empresa  e  precisa  da  sua  ajuda  para  *construir  um  Dashboard  que  represente  os  dados  de vendas no período de 2016 a 2019*.

Sua fonte de dados é um [arquivo Excel](https://github.com/luizabizoni/power-bi-studies/blob/master/dsa-cap-02/DadosVendaCarros.xlsx) com dados coletados do sistema de vendas e CRM da empresa, com a as seguintes colunas:
Coluna   | Descrição
--- | ---
DataNotaFiscal | Data de emissão da nota fiscal
Fabricante | Fabricante do veículo
Estado | Estado onde foi realizada a venda
PrecoVenda | Preço de venda do veículo
PrecoCusto | Preço de custo do veículo para a empresa
TotalDesconto | Total de Desconto fornecido sobre o preço de venda
CustoEntrega | Custo de entrega do veículo ao proprietário
CustoMaoDeObra | Custo de Mão de Obra (secretária, mecânico, etc...)
NomeCliente | Nome do cliente que comprou o veículo
Modelo | Modelo do veículo
Cor | Cor do veículo
Ano | Ano de fabricação do veículo

Seu gerente precisa das seguintes informações:

- Total de Vendas por Ano
- Custo de Entrega do Veículo Por Fabricante
- Custo de Mão de Obra Por Estado
- Total de Vendas Geral e Matriz de Vendas

Além  disso,  pode  ser  interessante, se  o  CEO  puder  visualizar  o *total  de  vendas  por estado* e se as *vendas estão acima ou abaixo da média*. Seu gerente já sabe que um assunto será abordado pelo CEO durante a apresentação. O CEO está avaliando se *continua ou não com a venda de automóveis da marca Jaguar* e ele gostaria de saber *como evoluíram as vendas de automóveis deste fabricante por ano e por estado*.

## Dashboar construído
[Arquivo Power BI](https://github.com/luizabizoni/power-bi-studies/blob/master/dsa-cap-02/estudo_01.pbix)

**Visão geral**
<center><img src="https://github.com/luizabizoni/power-bi-studies/blob/master/dsa-cap-02/dashboard_estudo_01.PNG" alt ="Dashboard de vendas de empresa fictícia de automóveis" width="800"></center>

**Visão vendas por estado**
<center><img src="https://github.com/luizabizoni/power-bi-studies/blob/master/dsa-cap-02/dashboard_estudo_01_2.PNG" alt ="Dashboard de vendas para estado de SP" width="800"></center>

**Visão vendas Jaguar**
<center><img src="https://github.com/luizabizoni/power-bi-studies/blob/master/dsa-cap-02/dashboard_estudo_01_3.PNG" alt ="Dashboard de vendas Jaguar" width="800"></center>