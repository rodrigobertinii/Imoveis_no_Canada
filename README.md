# Análise dos Preços das Casas no Canadá       <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Flag_of_Canada_%28Pantone%29.svg/800px-Flag_of_Canada_%28Pantone%29.svg.png" alt="Bandeira do Canadá" width="50"/>



![image](https://github.com/user-attachments/assets/71e287a6-3069-424e-b409-3ae651882ff6)

## Objetivo

Realizar uma análise exploratória de dados (EDA) e modelagem preditiva dos preços das casas em várias cidades canadenses. Alenm disso, construção de um Dashboard para visulização dos dados.

## Conjunto de Dados

O conjunto de dados pode ser encontrado [aqui](https://www.kaggle.com/datasets/jeremylarcher/canadian-house-prices-for-top-cities) e contém informações sobre:

- **City**: Localização do imóvel
- **Price**: Preço do imóvel
- **Address**: Localização específica do imóvel
- **Number_Beds**: Número de quartos no imóvel
- **Number_Baths**: Número de banheiros no imóvel
- **Province**: Província onde o imóvel está localizado
- **Population**: População da cidade
- **Latitude**: Latitude da localização do imóvel
- **Longitude**: Longitude da localização do imóvel
- **Median_Family_Income**: Renda média da família na cidade

## Análise Exploratório

- **Preços Médios:** O preço médio das casas em Toronto é de $1.235.288,77 CAD.
- **Renda Familiar Média:** A média é próxima de $90.000,00 CAD, com alguns outliers próximos a $130.000,00 CAD.
- **Cidades com Imóveis Mais Caros:** White Rock, Vancouver, Maple Ridge, Caledon, e Abbotsford.

## Limpeza e Visualização

- **Dados Limpos:** Colunas como 'Cidade', 'Endereço' e 'Provinça' foram removidas para facilitar a análise.
- **Correlação:** A análise revelou que o número de quartos e banheiros tem uma forte influência sobre o preço das casas.

## Modelagem Preditiva

- **Modelos:** Foram criados e avaliados modelos de regressão linear com diferentes combinações de variáveis.
- **Modelo Preferido:** O modelo com 'Número de Quartos' e 'Número de Banheiros' teve o melhor desempenho com R² de 20.93% para o treino e 24.07% para o teste.
- **Previsão:** Estimativa para uma casa com 3 quartos e 2 banheiros é de aproximadamente $755.771,20 CAD.

## Conclusão

Os modelos fornecem uma visão inicial dos preços das casas, mas com limitações significativas. O modelo preferido é o de regressão com 'Número de Quartos' e 'Número de Banheiros', apesar de apresentar um ajuste modesto. Melhorias adicionais são necessárias para aumentar a precisão.



