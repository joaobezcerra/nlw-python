Aplicação Python para geração de barcode

Aplicação desenvolvida usando **Python 3.11.5** durante o evento NLW ministrado pela Rocketseat.

## Frameworks utilizados

- Cerberus 1.3.5
- Flask 3.0.2
- Python-barcode 0.15.1
- Pytest 8.0.0

## Como utilizar?

###### Criar e habilitar o virtualenv

Usar os comandos na raiz do projeto clonado.

Criar ambiente virtual:

    pip install virtualenv

    Windows:
    py -m venv .venv

    Unix/macOS
    python3 -m venv .venv

Habilitar/Ativar ambiente virtual:

    .\.venv\Scripts\activate.bat

Baixar libs (ficam baixadas apenas no ambiente virtual):

    pip install -r requirements.txt

Executar projeto:

    python run.py

Executar testes:

    pytest

### Usando a aplicação

Realizar requisição POST na url *http://localhost:3000/create_tag*

Body Json example:

    {
        "product_code": "123"
    }
