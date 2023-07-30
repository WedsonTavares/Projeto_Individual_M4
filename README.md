**Relatório de Progresso Diário**


Este repositório contém um código em Python que cria um relatório de progresso diário baseado em dados de horas trabalhadas, bugs corrigidos e tarefas concluídas em diferentes dias da semana. O código utiliza as bibliotecas Pandas, NumPy, Matplotlib e Seaborn para análise de dados e visualização.

Funcionamento do Código
O código realiza as seguintes etapas:

Importação das bibliotecas necessárias:

pandas: para manipulação de dados em formato tabular.
numpy: para cálculos numéricos.
matplotlib: para criação de gráficos.
seaborn: para aprimoramento das visualizações gráficas.
Definição dos dados:
Os dados de horas trabalhadas, bugs corrigidos e tarefas concluídas são fornecidos em um dicionário chamado data, onde cada chave representa uma coluna do DataFrame.

Criação do DataFrame:
O DataFrame df é criado a partir dos dados fornecidos no dicionário data. Ele é usado para armazenar e manipular os dados de forma tabular.

Cálculo de Métricas:
O código calcula diversas métricas de desempenho com base nos dados fornecidos:

Total de horas trabalhadas: soma as horas trabalhadas em todos os dias da semana.
Média diária de horas trabalhadas: calcula a média das horas trabalhadas por dia.
Total de bugs corrigidos: soma o número de bugs corrigidos em todos os dias da semana.
Média diária de bugs corrigidos: calcula a média do número de bugs corrigidos por dia.
Total de tarefas concluídas: soma o número de tarefas concluídas em todos os dias da semana.
Média diária de tarefas concluídas: calcula a média do número de tarefas concluídas por dia.
Visualizações Gráficas:
O código cria diversas visualizações gráficas utilizando Seaborn e Matplotlib para mostrar os dados de maneira mais intuitiva:

Gráficos de barras mostram o total de horas trabalhadas, total de bugs corrigidos e total de tarefas concluídas por dia da semana.
Gráficos de barras também exibem as médias diárias de horas trabalhadas, bugs corrigidos e tarefas concluídas separadamente.
Relatório de Progresso Diário:
O código gera um relatório em formato de texto, exibindo as métricas calculadas e os totais de horas trabalhadas, bugs corrigidos e tarefas concluídas.

Como Utilizar o Código
Instale as bibliotecas necessárias:
Para executar o código, é necessário ter o Python instalado em seu sistema, juntamente com as bibliotecas Pandas, NumPy, Matplotlib e Seaborn. Caso não tenha essas bibliotecas instaladas, você pode instalá-las utilizando o pip:

Ferramentas utilizadas: 
[![Pandas](data:image/png;base64,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)](https://pandas.pydata.org/) [![NumPy](images/numpy_icon.png)](https://numpy.org/) [![Matplotlib](images/matplotlib_icon.png)](https://matplotlib.org/) [![Seaborn](images/seaborn_icon.png)](https://seaborn.pydata.org/)


Copy code
pip install pandas numpy matplotlib seaborn
Execute o código:
Copie o código fornecido no arquivo relatorio_progresso_diario.py e execute-o em seu ambiente Python.

Visualize o Relatório:
O código irá gerar as visualizações gráficas e exibirá o relatório de progresso diário com as métricas calculadas diretamente no terminal.

Contribuições
Contribuições para melhorias e novas funcionalidades são bem-vindas! Sinta-se à vontade para abrir um Pull Request para discutir suas ideias e sugestões.

Contato
- LinkedIn: [Wedson Tavares](https://www.linkedin.com/in/wedson-tavares-0a7961261/)

