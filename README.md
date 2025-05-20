# Pipeline ETL Python - Extração de API Bitcoin com Agno Agente AI, SQL e Streamlit


## 📈 Coleta de Dados do Bitcoin com SQLAlchemy e Coinbase API
Este projeto realiza a extração periódica do valor do Bitcoin a partir da Coinbase API e armazena os dados em um banco de dados PostgreSQL utilizando SQLAlchemy.

🚀 Funcionalidades
Conecta-se à API pública da Coinbase para obter o valor atual do Bitcoin.

Processa os dados e adiciona um timestamp.

Armazena as informações em uma tabela no PostgreSQL.

Executa esse processo a cada 15 segundos.

🧰 Tecnologias utilizadas
Python

SQLAlchemy

PostgreSQL

Requests

dotenv

Coinbase API

🧪 Exemplo de dados armazenados

![imagem](image.png)