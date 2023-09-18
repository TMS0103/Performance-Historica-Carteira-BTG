# Análise da Carteira Recomendada de Dividendos do BTG Pactual

## Descrição do Projeto

Este projeto tem como objetivo realizar uma análise dos dados de uma carteira recomendada de dividendos fornecida pelo Banco BTG Pactual. A análise visa fornecer insights sobre o desempenho histórico da carteira e compará=lo com o Índice Ibovespa. Para isso serão analisados 4 períodos diferentes: 30 dias, 1 ano, 5 anos e, por fim, 10 anos.

## Contexto

O BTG Pactual é uma das principais instituições financeiras do Brasil, conhecida por sua expertise em investimentos e análises de mercado. A carteira recomendada de dividendos do BTG Pactual se dispõe principalmente a gerar valor aos acionista com foco na distribuição de dividendos. Uma características das carteiras de dividendos que é fundamental pontuar é que as empresas selecionadas normalmente se apresentam como maduras e estáveis, muitas vezes de setores tradicionais, que têm histórico de distribuição de dividendos consistentes ao longo do tempo. Essas empresas costumam ter um histórico sólido de geração de fluxo de caixa.

## Objetivos

Os principais objetivos deste projeto são:

1. Coletar e processar os dados da carteira recomendada de dividendos do BTG Pactual e do índice Ibovespa.

2. Realizar o a inspeção e tratamento dos dados das bases extraídas do Yahoo Finance.

3. Realizar a normalização dos ativos da carteira e do índice Ibovespa no respectivo período de análise.

4. Avaliar a volatilidade da carteira e compará-la com índices Ibovespa.

5. Verificar os retornos da carteira e do índice.
   
6. Avaliar a correlação entre a carteira e o índice no período analisado.

8. No caso dos períodos de 5 anos e 10 anos, verificar o retorno médio anual tanto do índice quanto da carteira e compará-los.
   
10. Por fim, com as análises feitas, tirar insights conclusivos sobre a carteira recomendada pelo BTG.

## Ferramentas e Tecnologias Utilizadas

Este projeto utiliza as seguintes ferramentas e tecnologias:

- Linguagem de programação: Python
- Bibliotecas Python: Pandas, Pandas-Datareader Matplotlib, datatime, yfinance
- Jupyter Notebook para análises 
- Fontes dos dados da carteira: https://content.btgpactual.com/research/carteiras-recomendadas/carteira-recomendada/64f1b161b87dc34e4fa95f0b/Dividendos-Setembro-23

## Conclusões

- Como esperado pela hipótese, a carteira superou em quase 2x o Índice Ibovespa durante os períodos analisados.


- Outra inferência que pode ser posta é que vale a pena investir em empresas consolidadas gera bons retornos ao longo dos anos por meio da valorização, tendo em vista que os períodos de 5 anos e 10 anos tiveram um retorno médio anual acima dos 20%. Em comparação, o retorno do período de um ano foi de 14,20%.


- Das empresas comtempladas pela carteira, em 3 de 4 comparações de normalização, a empresa Petrobrás (Petr4) ficou como a empresa com melhor rentabilidade. O único período analisado que esteve abaixo foi no de 30 dias, em que a Vale à superou. Entretanto, nos maiores períodos de análise, se mostrou como a empresa mais rentável.


- Portanto, pode-se inferir que para uma carteira de longo prazo, visando empresas estáveis e consolidadas, a Petrobrás é a principal opção (com base nessa carteira recomendada pelo BTG).


*  Todas as conclusões foram tomadas com base no dia 14 de setembro de 2023

## Autor

- Thiago Magalhães de Souza(https://github.com/TMS0103/) - Economista e entusiasta por Análise de Dados
