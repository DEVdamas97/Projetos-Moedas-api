# Cotação de Moedas - AwesomeAPI

Este é um projeto simples desenvolvido com **Streamlit** para exibir a cotação de várias moedas em tempo real, utilizando a **API pública AwesomeAPI**. O objetivo do projeto é permitir que o usuário visualize as cotações de moedas como Dólar, Euro, Bitcoin e Libra, e suas variações ao longo do dia.

## Funcionalidades

- **Seleção de moedas**: O usuário pode selecionar entre as seguintes moedas para visualizar a cotação:
  - Dólar → Real (USD-BRL)
  - Euro → Real (EUR-BRL)
  - Bitcoin → Real (BTC-BRL)
  - Libra → Real (GBP-BRL)
  
- **Exibição de dados**:
  - Cotação atual (compra e venda)
  - Alta do dia
  - Baixa do dia
  - Variação da cotação ao longo do dia

## Tecnologias Utilizadas

- **Streamlit**: Framework para criação rápida de interfaces interativas.
- **Requests**: Biblioteca para realizar requisições HTTP e consumir a API.
- **AwesomeAPI**: API gratuita para cotação de moedas.

## Como Executar

### Pré-requisitos

Antes de executar o projeto, certifique-se de ter os seguintes programas instalados em seu computador:

- **Python 3.6+**: O projeto foi desenvolvido para versões mais recentes do Python. Você pode verificar sua versão com o seguinte comando:
  ```bash
  python --version
