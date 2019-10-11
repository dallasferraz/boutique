# boutique
Análise de dados de 2015 a 2017 de uma boutique em Power BI (informações descaracterizadas por razões éticas).

Após transformar em CSV os dados que estavam anteriormente armazenados em DBF, fiz um tratamento de outliers, valores faltantes e padronização de grafia dos itens preenchidos, além de descaracerizar os nomes dos produtos, clientes e vendedores. Esta etapa foi processada em RStudio.

Com isso, foi possível transformar e montar visuais no Power BI, como pode ser visto clicando na imagem abaixo:

[![PowerBI](https://raw.githubusercontent.com/dallasferraz/boutique/master/print.png)](https://app.powerbi.com/view?r=eyJrIjoiMDBmMDJhNGUtODYzYi00Yjc3LWFhZTUtNGI3MDFhZjRkZjQ2IiwidCI6ImUyZjc3ZDAwLTAxNjMtNGNmNi05MmIwLTQ4NGJhZmY5ZGY3ZCJ9)

Com base nos visuais gráficos montados a partir dos dados tratados, o próprio Power BI dispõe uma ferramenta, o quick insights, que busca correlações entre os dados. As informações fornecidas de 2015 a 2017 permitiram que a gerente da boutique obtivesse informações que a auxiliaram a melhor planejar promoções de produtos, barganha de lotes de compras, criar um sistema de fidelidade para os melhores clientes e também entender melhor ao longo dos meses quais os pontos críticos. Eis os pontos principais obtidos a partir deste dataset e deste relatório:

* Dezembro é o mês com o maior número de vendas no cartão
* Todas as vendas em cheque foram feitas para o Cliente 39
* Vendedor C foi o que mais vendeu para o Cliente 39
* Todas as vendas registradas no período ocorreram apenas para clientes de uma única cidade
* Julho e fevereiro são os meses em que os clientes mais parcelam no cartão
* O valor do desconto é sempre proporcional ao valor dos pagamentos feito em espécie
* Vendedor C foi o cliente que mais finalizou vendas no cartão
