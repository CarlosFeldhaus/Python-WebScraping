# Web Scraping com Python 

Este projeto realiza **Web Scraping** para coletar dados de Preço cheio e Desconto de produtos em um e-commerce. Utilizando **Python**, as bibliotecas **BeautifulSoup** e **Requests**, o objetivo é automatizar a extração de dados estruturados para análise ou posterior uso.

## Objetivo do Projeto

O objetivo deste projeto é coletar os dados de preço cheio e de preço com desconto de produtos a partir de uma lista de códigos, processá-los e armazená-los de forma organizada. Isso pode ser útil para análise de mercado, monitoramento de preços, coleta de informações para machine learning, entre outros.

## Funcionalidades

- **Extração de Dados**: Coleta informações específicas de páginas web da Loja Principessa.
- **Verificação de Existência**: Detecta quando o produto não está disponível na busca.
- **Armazenamento**: Dados coletados são armazenados em arquivo Excel (.xlsx).
- **Tratamento de Dados**: Limpeza e filtragem dos dados para garantir qualidade.
- **Automatização**: Permite a extração automática a partir de uma lista de códigos.

## Tecnologias Usadas

- **Python**: Linguagem principal do projeto.
- **BeautifulSoup**: Para parseamento e extração de dados HTML.
- **Requests**: Para realizar as requisições HTTP.
- **Pandas**: Para manipulação e armazenamento dos dados.
- **Openpyxl**: Para salvar arquivos Excel.
