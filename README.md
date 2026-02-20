# 💻 Data Science - Research Jobs And Salaries in Data Science


Fonte: Kaggle - url: *https://www.kaggle.com/datasets/hummaamqaasim/jobs-in-data*

Descricao do Banco de Dados:
Este conjunto de dados reune informacoes reais sobre empregos na area de ciencia de dados
------------------------------
## Introducao aos conceitos de Analise Exploratoria

# Carregando bibiliotecas
```
import pandas as pd
import numpy as pd

import matplotlib.pyplot as
```

# Libraries
import pandas as pd # Dataframe - Number One tool for Data Analysis
import numpy as np # Numeric Operation

import matplotlib.pyplot as plt 

# Data Visualization

# Step 1 - Loading Database
```
#Step 1 - Loading Database

#df as Dataframe
df = pd.read_csv("jobs_in_data.csv")

### Now all the data is available to analysis
```
Perguntas que  análise inicial responde com poucos comandos:
- quantas linhas (observacoes) e colunas (variaveis) o dataset possui;
- quais tipos de dados de cada variavel;
- se existem valores ausentes (faltantes);
- se ha indicios de dados redundates ou inconsistentes;
- estatisticas basicas dos dados numericos;

Visualização das primeiras e últimas linhas: *df.head(n)* e *df.tail(n)*, *n* é a quantidade de observações que para exibir

Estrutura Geral do Dataframe: *df.inf()*

Estatística Descritiva: *df.describe()*

Obs. Exibição de Resultados:
- *print()* - simple
- *display()* - rich


## Visualização das primeiras e últimas linhas:
```



display(df.head(10))

df.tail(10)
```
## Estrutura geral o Dataframe
```
df.info()
```
## Estatística Descritiva - quantitativa


```
df.describe()

```



## License

[MIT](https://choosealicense.com/licenses/mit/)
