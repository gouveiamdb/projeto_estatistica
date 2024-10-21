![alt text](image.png)
# Análise Estatística e Séries Temporais de Vendas de Jogos (Midea Física)

Este projeto tem como objetivo realizar uma análise estatística básica, explorar a distribuição das variáveis numéricas e categóricas, e realizar uma análise de séries temporais utilizando dados de vendas de jogos. Também inclui a visualização de correlações entre variáveis e a análise de outliers.

## Estrutura do Projeto

### 1. **Análise Exploratória de Dados (EDA)**
   - Verificação de valores ausentes e tratamento dos mesmos.
   - Cálculo das estatísticas descritivas básicas para as variáveis numéricas: 
     - **Média**, **mediana**, **mínimo**, **máximo** e **desvio padrão**.
   - Análise da distribuição dos dados categóricos e numéricos.
   - Transformação de categorias específicas (por exemplo, limitar os publishers a um top 10 e agregar o restante como "outros").

### 2. **Visualização de Dados**
   - Gráficos para a distribuição de variáveis numéricas e categóricas.
   - Gráficos de barras, boxplots e histogramas foram utilizados para visualizar os dados.

### 3. **Correlação entre Variáveis**
   - Matriz de correlação das variáveis numéricas.
   - Cálculo e visualização de correlação entre as vendas nas regiões (América do Norte, Europa, Japão, Resto do Mundo) e as vendas globais.

### 4. **Análise de Séries Temporais**
   - Série temporal construída com base nas vendas anuais.
   - Visualização da tendência de vendas ao longo do tempo.
   - Decomposição das séries temporais em componentes de tendência, sazonalidade e ruído.
   - Testes de hipóteses sobre as correlações identificadas.

### 5. **Detecção de Outliers**
   - Identificação de outliers nas vendas e análise de impacto.
   - Sugestão sobre remoção ou manutenção de dados anômalos, dependendo do contexto.

## Estrutura dos Arquivos

- `pj_estat_analise.ipynb`: Contém o código-fonte e as análises executadas.
- `vgsales.csv`: Arquivo CSV contendo os dados de vendas de jogos.
- `README.md`: Este arquivo de documentação.

## Bibliotecas Utilizadas

Este projeto utiliza as seguintes bibliotecas Python:

- **pandas**: Manipulação e análise de dados.
- **numpy**: Suporte a arrays e operações numéricas.
- **matplotlib**: Visualização de dados.
- **seaborn**: Gráficos estatísticos.
- **statsmodels**: Análise de séries temporais e modelos estatísticos.

## Instruções para Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

2. Instale as dependências necessárias:
    ```bash
    pip install 

3. Execute o Jupyter Notebook `pj_estat_analise.ipynb` para visualizar as análises e gráficos.

## Conclusões

1. Correlação: As vendas na América do Norte têm a maior correlação com as vendas globais, seguida pela Europa. Já o Japão possui uma correlação mais baixa.

2. Séries Temporais: Observou-se um aumento nas vendas de jogos entre os anos de 2005 e 2010, seguido por uma queda gradual.

3. Outliers: Alguns outliers foram identificados nas vendas de jogos muito populares. Esses dados foram mantidos por sua relevância.

## Melhorias Futuras

- Realizar previsões de vendas futuras usando modelos de séries temporais avançados (ARIMA, Holt-Winters).
- Implementar uma análise mais profunda de outliers usando métodos robustos.
- Explorar modelos de machine learning para prever as vendas com base nas características dos jogos.

## Autores:

- **Olga Osorio Aburto**  
  [GitHub](http://github.com/olgaosorio/) | [LinkedIn](http://linkedin.com/in/olga-osorio-aburto/)

- **Michael Florentino**  
  [GitHub](https://github.com/Michaelgsf) | [LinkedIn](https://www.linkedin.com/in/michaelgsf)

- **Matheus Gouveia**  
  [GitHub](https://github.com/gouveiamdb) | [LinkedIn](https://www.linkedin.com/in/matheus-gouveia-387a19258/)

- **Murilo Silva**  
  [GitHub](https://github.com/usuario3) | [LinkedIn](https://www.linkedin.com/in/murilo-silva-bb2741a1)

- **Marcos Carvalho**
  [GitHub](https://github.com/MarcosFN2014) | [LinkedIn](https://www.linkedin.com/in/marcos-carvalho-8173a2241/)