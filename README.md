## Aplicação Prática de Criptografia de Dados Sensíveis 🔐

Este projeto tem como objetivo demonstrar a aplicação de criptografia em dados sensíveis, como informações pessoais (ex: nome, CPF) e dados bancários (ex: número de conta bancária). A aplicação utiliza a biblioteca **cryptography** para realizar a criptografia e descriptografia de arquivos CSV. Este projeto é uma aplicação prática desenvolvida como parte do módulo de segurança da informação do curso de pós-graduação em Engenharia e Arquitetura de Dados.

### O que ele faz:
- Permite a geração de uma **chave de criptografia** para proteger os dados.
- **Criptografa e descriptografa** arquivos CSV contendo dados sensíveis.
- Permite que a chave de criptografia seja fornecida para **descriptografar** os dados corretamente.

### Funcionalidades

- **🔑 Gerar chave de criptografia**: Gera e salva uma chave de criptografia para ser usada na criptografia/descriptografia dos dados.
- **🔒 Criptografar dados**: Criptografa uma base de dados em formato CSV, protegendo as colunas sensíveis.
- **🔓 Descriptografar dados**: Descriptografa uma base de dados criptografada, usando a chave gerada.

### Tipos de Dados

- **Nome**: Informação pessoal (Criticidade média)
- **CPF**: Informação sensível (Criticidade alta)
- **Dados Bancários**: Informação altamente sensível (Criticidade alta)

### 🔧 Ferramentas Utilizadas

- **Python**: Linguagem de programação utilizada.
- **Cryptography**: Biblioteca para criptografar e descriptografar os dados.
- **ipywidgets**: Interface gráfica para interação no Jupyter Notebook.
- **pandas**: Manipulação de dados em CSV.

