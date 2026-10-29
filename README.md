# Análise dos Preços de Aluguel em São Paulo

## 1. Identificação do projeto

**Projeto:** Análise dos Preços de Aluguel em São Paulo
**Candidato:** [CLOVIS LORENA CAVALCANTI PEDROSO NETO]
**Programa:** SYNAPTA — Laboratório de Dados e IA
**Opção escolhida:** Opção 1 — Preços de aluguel em São Paulo.

## 2. Objetivo

O objetivo deste projeto é analisar os preços dos aluguéis de imóveis em São Paulo, identificando padrões e possíveis relações entre o valor do aluguel e características como área, quantidade de quartos e distrito.

## 3. Fonte dos dados

O conjunto de dados foi obtido no Kaggle:

[https://www.kaggle.com/datasets/renatosn/sao-paulo-housing-prices/data](https://www.kaggle.com/datasets/renatosn/sao-paulo-housing-prices/data)

Para executar o projeto, baixe o arquivo `data.csv` e coloque-o no local indicado nas instruções do projeto.

## 4. Colunas utilizadas

- `address`: endereço do imóvel.
- `district`: distrito onde o imóvel está localizado.
- `area`: área do imóvel em metros quadrados.
- `bedrooms`: quantidade de quartos.
- `garage`: quantidade de vagas de garagem.
- `type`: tipo do imóvel.
- `rent`: valor anunciado do aluguel.
- `total`: valor total registrado no conjunto de dados.

## 5. Ferramentas utilizadas

- Python: linguagem de programação.
- Google Colab: ambiente de execução do notebook.
- Pandas: organização, limpeza e análise dos dados.
- Matplotlib: criação dos gráficos.

## 6. Etapas realizadas

1. Carregamento e exploração inicial dos dados.
2. Verificação de valores ausentes, duplicados e inconsistências.
3. Preparação e limpeza dos registros conforme os critérios definidos.
4. Cálculo da média e da mediana dos aluguéis.
5. Comparação dos preços por área, quantidade de quartos e distrito.
6. Criação de gráficos para facilitar a interpretação dos resultados.
7. Elaboração das conclusões e identificação das limitações da análise.

## 7. Resultados e principais conclusões

O aluguel médio dos imóveis analisados foi de R$ 3.393,29, enquanto a mediana foi de R$ 2.500,00.

A correlação entre área e aluguel foi de aproximadamente 0,67, indicando uma relação positiva entre essas variáveis.

Os imóveis com três quartos apresentaram aluguel médio de R$ 4.795,90, enquanto os imóveis com um quarto apresentaram média de R$ 2.157,49.

Entre os distritos com pelo menos 30 registros, Jardim Leonor apresentou o maior aluguel médio, de R$ 7.414,00. Taboão apresentou o menor, de R$ 1.493,42.

Os resultados indicam diferenças nos preços conforme as características dos imóveis e sua localização.

## 8. Limitações da análise

Os dados não incluem todos os fatores que podem influenciar o preço do aluguel, como o estado de conservação, a idade do imóvel e a proximidade do transporte público.

A quantidade de registros varia entre os distritos, e os preços anunciados podem ser diferentes dos valores finais negociados.

Além disso, os critérios adotados para a limpeza podem influenciar os resultados encontrados.

## 9. Como executar o projeto

1. Baixe o arquivo `data.csv` na página do Kaggle.
2. Faça o uploud do arquivo `analise_alugueis.ipynb` no Google Colab.
3. Disponibilize o arquivo `data.csv` na 
4. No menu lateral esquerdo, procure o ícone de pasta 📁.
Clique nele para abrir o painel de arquivos.
Procure o botão de enviar arquivo (ícone de upload) e envie seu `data.csv`
5. Execute as células do notebook em ordem para reproduzir a análise.
## 10. Declaração de uso de inteligência artificial
Foi utilizada inteligência artificial, por meio do ChatGPT, como apoio ao aprendizado de Python, à elaboração e revisão de comandos e em duvidas como funciona a postagem no github. Os resultados foram conferidos no Google Colab.
