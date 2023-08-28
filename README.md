# Santander Bootcamp 2023 - Ciência de Dados com Python

## Desafio Explorando IA Generativa em um Pipeline de ETL com Python

Construido um ETL (Extract, Transformer and Load para tratamento de informações de clientes e envio de mensagens personalizadas atraves OpenAI.

## Tecnologias Utilizadas
* Python (Biblioteca Panda)
* OpenAI
* Google Colab

### Descrevendo a Atividade ETL em Python:

**1º** 
Foi feito a importação da planilha SBC2023.csv, contendo UserID com 5 usuário para testes, no Google Colab.

**2º** 
Na etapa "Extract", foi tratado a importação das bibliotecas pandas, requests e json. 
Para tratar e coletar as informações da planilha.

**3º**
Na etapa "Transform", foi utilizado a API do OpenAI GPT-3.5-turbo para criar mensagens personalizadas para os 5 usuários.

    **OBS**: Nesta etapa me deparei com um problema de crédito, devido a conta tipo free da OpenAI. Portanto a Mensagem foi atribuída para apenas 3 usuários.

**4º**
Na etapa "Load", foi atualizado a lista de "news" de cada usuário na API com a nova mensagem gerada.


## 🔗 Links
* Para Acesso ao meu trabalho:

    [![Google Colab](https://img.shields.io/badge/Google%20Colab%20-%20?labelColor=rgb&color=%23FF8000)](https://colab.research.google.com/drive/1arxlS0hsi3MbQRU0rlASwiGs5yFa4_o2#scrollTo=YefWfYBoZMN2)

* Documentação da API (Swagger)

    [![Swagger UI](https://img.shields.io/badge/Swagger_UI-ty?labelColor=rgb&color=%2332CD32
    )](https://sdw-2023-prd.up.railway.app/swagger-ui/index.html#/)


* Para contato pessoal

    [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramon-sieia-59b536b6/)

  ## Referência

 - [Google colab](https://colab.google)
 - [GitHub DIO](https://github.com/digitalinnovationone/santander-dev-week-2023-api)
 - [Readme.so](https://readme.so/pt)

  
