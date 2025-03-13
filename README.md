# Generative AI Project

Este repositório apresenta uma estrutura bem organizada para projetos de IA generativa. Ele fornece uma base sólida para experimentação, desenvolvimento e implantação de modelos de IA generativa, com configurações flexíveis e um conjunto de utilitários essenciais.

## Estrutura do Projeto

```
Generative AI Project Structure
│── config
│── data
│── docs
│── notebooks
│── src
│── test
│── .env.example
│── .gitignore
│── docker-compose-dev.yml
│── docker-compose-local.yml
│── Dockerfile
│── README.md
│── requirements.txt
│── run.sh
│── setup.py
``` 

projeto estruturado para desenvolvimento de IA generativa, com uso de Docker, scripts de configuração e requisitos em Python. 

## Requisitos
Antes de começar, instale as dependências necessárias:

```sh
pip install -r requirements.txt
```

## Como Usar

1. **Configuração do Modelo**
   - Altere os arquivos de configuração em `config/` para ajustar os parâmetros do modelo.
   
2. **Testes e Experimentação**
   - Use os notebooks em `notebooks/` para testar e analisar respostas do modelo.
   
3. **Execução de Exemplos**
   - Rode os scripts em `examples/` para interagir com o modelo de IA generativa.

```sh
python examples/basic_completion.py
```

