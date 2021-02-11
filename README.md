# Predict Future Sales

Dados providos pela empresa russa de softwares 1C Company e disponibilizdados para competição no Kaggle pela escola Coursera, para conclusão do curso "How to win a data science competition". Os dados são granulados a nível de vendas diárias, são ao todo 60 lojas e 22170 produtos. Uma timeseries contendo trend e sazonalidades. A lista de lojas e produtos muda ligeiramente a cada mês.

## Objetivo: Predizer o valor bruto de vendas por produtos, por lojas para o próximo período, agregado mensalmente, problema do tipo regressão. 

### Descrição das tabelas

* sales_train.csv - O set train. Histórico de vendas diárias de Janeiro de 2013 até Outubro de 2015.
* test.csv - O set test. Você precisa prever as vendas das lojas e produtos em Novembro de 2015.
* sample_submission.csv - Um exemplo de arquivo de submissão corretamente formatado.
* items.csv - Informações complementares sobre os items/produtos.
* item_categories.csv  - Informações complementares sobre as categorias dos items/produtos.
* shops.csv- Informações complementares sobre as lojas.

### Descrição das labels

* ID - O Id que representa o par loja/produto 
* shop_id - Id da loja
* item_id - Id do item/produto
* item_category_id - Id da categoria do item/produto
* item_cnt_day - Número de produtos vendidos agregados por dia.
* item_price - Preço de venda do produto.
* date - Data em formato dd/mm/yyyy
* date_block_num - Número do mês consecutivo. Janeiro de 2013 é o mês 0, Fevereiro de 2013 é o 1, Outubro de 2015 é o 33.
* item_name - Nome do item/produto.
* shop_name - Nome da loja.
* item_category_name - Nome da categoria do item/produto.

