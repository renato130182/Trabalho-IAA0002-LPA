## Versão do Python
- Python 3.13.2

## Bibliotecas Utilizadas
- pandas
- warnings

## Instruções para Rodar o Projeto

1. Crie um ambiente virtual com o nome `TRBenv`:
    ```bash
    python -m venv TRBenv
    ```

2. Ative o ambiente virtual:
    - No Windows:
      ```bash
      TRBenv\Scripts\activate
      ```
    - No macOS/Linux:
      ```bash
      source TRBenv/bin/activate
      ```

3. Instale as bibliotecas necessárias:
    ```bash
    pip install pandas
    ```

4. Abra o Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

5. No Jupyter Notebook, abra o arquivo `script.ipynb` e execute as células para realizar a análise de dados.

## Descrição do Projeto
Este projeto realiza uma análise exploratória dos preços de carros no Brasil. O conjunto de dados contém informações detalhadas sobre marcas, modelos, tipos de combustível, tamanhos de motor, e preços médios dos carros. O objetivo é limpar e preparar os dados para futuras análises.

## Estrutura do Projeto
- `script.ipynb`: Jupyter Notebook contendo o código de análise de dados.
- `precos_carros_brasil.csv`: Arquivo CSV com os dados de preços de carros no Brasil.
- `requirements.txt`: Arquivo de requisitos para instalar as bibliotecas necessárias.
- `readme.txt`: Este arquivo com instruções para rodar o projeto.