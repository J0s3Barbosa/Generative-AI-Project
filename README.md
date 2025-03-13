# Generative AI Project

Este repositório apresenta uma estrutura bem organizada para projetos de IA generativa. Ele fornece uma base sólida para experimentação, desenvolvimento e implantação de modelos de IA generativa, com configurações flexíveis e um conjunto de utilitários essenciais.

## Estrutura do Projeto

```
Generative AI Project Structure

├── project/
│   ├── config/              # Configuração do modelo e registros
│   │   ├── model_config.yaml
│   │   ├── logging.config.yaml
│   │   ├── templates.yaml
│   │   └── __init__.py
│   │
│   ├── src/                 # Código-fonte principal
│   │   ├── config/
│   │   └── __init__.py
│   │
│   ├── data/                # Diretório para armazenamento de dados
│   │   └── ...
│   │
│   ├── examples/            # Exemplos de uso
│   │   ├── basic_completion.py
│   │   ├── chat_session.py
│   │   ├── chain_prompts.py
│   │
│   ├── notebooks/           # Notebooks para análise e testes
│   │   ├── prompt_testing.ipynb
│   │   ├── response_analysis.ipynb
│   │   ├── model_experimentation.ipynb
│   │
│   ├── handlers/            # Manipuladores de erros
│   │   ├── error_handler.py
│   │   └── __init__.py
│   │
│   ├── utils/               # Funções utilitárias
│   │   ├── rate_limiter.py
│   │   ├── cache.py
│   │   ├── token_counter.py
│   │   └── __init__.py
│   │
│   ├── prompts/             # Modelos de prompts
│   │   └── ...
│   │
│   ├── outputs/             # Diretório para saídas geradas
│   │   └── ...
│   │
│   ├── embeddings/          # Representação vetorial
│   │
│   ├── utils.py             # Arquivo de utilitários gerais
│   ├── logger.py            # Configuração de logging
│   ├── __init__.py          # Inicialização do pacote
│   └── README.md            # Documentação do projeto
│
├── requirements.txt         # Dependências do projeto
├── setup.py                 # Configuração para instalação
```

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

