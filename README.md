# Análise de Cancelamentos

## Descrição
Este notebook realiza uma análise detalhada dos cancelamentos de clientes, identificando padrões e possíveis causas. Utiliza a biblioteca `pandas` para manipulação de dados e `plotly` para visualização gráfica. O objetivo é entender os motivos dos cancelamentos e sugerir estratégias para reduzi-los.

## Requisitos
Antes de executar o notebook, instale as dependências necessárias:
```sh
pip install pandas numpy openpyxl nbformat ipykernel plotly
```

## Estrutura da Análise
1. **Importação da Base de Dados** – Carregamento do arquivo `cancelamentos_sample.csv`.
2. **Visualização Inicial** – Limpeza e ajustes na base de dados.
3. **Correção de Problemas** – Remoção de valores nulos e colunas irrelevantes.
4. **Análise de Cancelamentos** – Identificação do percentual de clientes que cancelaram.
5. **Análise de Causas** – Uso de gráficos para correlacionar variáveis com os cancelamentos.
6. **Propostas de Solução** – Estratégias para reduzir a taxa de cancelamento.

## Como Usar
1. Certifique-se de que o arquivo `cancelamentos_sample.csv` está na mesma pasta do notebook.
2. Abra o notebook com:
   ```sh
   jupyter notebook Analise_Cancelamentos.ipynb
   ```
3. Execute as células passo a passo para acompanhar a análise.

## Resultados Esperados
- Identificação de padrões nos cancelamentos.
- Sugestões para mitigar os cancelamentos.
- Visualização clara dos dados através de gráficos interativos.

## Autor
Criado por Diogo Benedetti.

