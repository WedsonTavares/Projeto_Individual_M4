# Relatório de Progresso Diário


Este repositório contém um script em Python que analisa e visualiza o progresso diário de trabalho. O código é capaz de calcular métricas como o total de horas trabalhadas, média diária de horas trabalhadas, total de bugs corrigidos, média diária de bugs corrigidos, total de tarefas concluídas e média diária de tarefas concluídas.

Além disso, o script utiliza as bibliotecas Pandas, NumPy, Matplotlib e Seaborn para criar gráficos de barras que mostram o total de horas trabalhadas, total de bugs corrigidos e total de tarefas concluídas por dia da semana. Também são apresentados gráficos de barras para a média diária de horas trabalhadas, média diária de bugs corrigidos e média diária de tarefas concluídas.

Os dados de progresso diário são representados em um dicionário, onde cada chave representa uma coluna do DataFrame. O relatório de progresso diário é exibido no console com as métricas calculadas.
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

Gráficos de barras mostram o total de horas trabalhadas, total de bugs corrigidos e total de tarefas concluídas por dia da semana.
Gráficos de barras também exibem as médias diárias de horas trabalhadas, bugs corrigidos e tarefas concluídas separadamente.
Relatório de Progresso Diário:
O código gera um relatório em formato de texto, exibindo as métricas calculadas e os totais de horas trabalhadas, bugs corrigidos e tarefas concluídas.

Como Utilizar o Código:
Instale as bibliotecas necessárias:
Para executar o código, é necessário ter o Python instalado em seu sistema, juntamente com as bibliotecas Pandas, NumPy, Matplotlib e Seaborn. Caso não tenha essas bibliotecas instaladas, você pode instalá-las utilizando o pip:

Ferramentas utilizadas: 
[Pandas](https://pandas.pydata.org/)     [NumPy](https://numpy.org/)     [Matplotlib](https://matplotlib.org/)     [Seaborn](https://seaborn.pydata.org/)


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

