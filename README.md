# Challenge-TelecomX 


📊 Análise de Churn - Telecom X

Este projeto foi desenvolvido como parte de um desafio de Data Science para a empresa fictícia Telecom X, especializada em serviços de telecomunicações. O objetivo principal é realizar um processo completo de ETL (Extração, Transformação e Carga) e Análise Exploratória de Dados (EDA) a fim de identificar padrões que possam explicar o alto índice de evasão de clientes (churn).

Com os dados tratados e analisados, a equipe de Data Science poderá, posteriormente, desenvolver modelos preditivos para reduzir a taxa de cancelamento de clientes.

🎯 Objetivos do Projeto

* Realizar a extração dos dados a partir de uma API hospedada em um repositório do GitHub.
* Executar a normalização e transformação dos dados para garantir a qualidade e consistência.
* Aplicar análise exploratória de dados (EDA) para identificar padrões e possíveis causas de evasão.
* Gerar visualizações e insights que possam orientar a tomada de decisão.
* Produzir um relatório detalhado sobre o processo e os principais achados.

🔗 Fonte dos Dados:

Os dados foram obtidos diretamente de um arquivo JSON hospedado no GitHub:
https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json

📂 Estrutura do Projeto
text
telecom-churn-analysis/  
├── data/  
│   ├── TelecomX_Data.json          # Dados brutos da API  
│   └── telecom_clean.csv           # Dados tratados  
├── notebooks/  
│   ├── 1_ETL.ipynb                # Extração, transformação e limpeza  
│   ├── 2_EDA.ipynb                # Análise exploratória  
│   └── 3_Churn_Segmentation.ipynb # Análise de segmentos de risco  
├── outputs/  
│   ├── dashboards/                # Imagens dos dashboards  
│   └── insights/                  # Relatórios em PDF  
└── README.md  

⚙️ Tecnologias e Bibliotecas Utilizadas

* Python 3.x
* Google Colab (para execução e desenvolvimento)
* Pandas — manipulação e tratamento de dados
* NumPy — operações matemáticas e estatísticas
* Matplotlib — visualizações gráficas
* Seaborn — visualizações estatísticas
* Requests — requisições HTTP para extração dos dados via API

🛠️ Como Executar o Projeto

1️⃣ Clone este repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git

2️⃣ Abra o arquivo TelecomX_Churn_Analysis.ipynb diretamente no Google Colab ou em sua IDE preferida.

3️⃣ Instale as dependências necessárias (no caso de execução local):
pip install pandas numpy matplotlib seaborn requests

4️⃣ Execute o notebook célula por célula, acompanhando o processo de ETL e análise exploratória.

📊 Principais Etapas

1. Extração de Dados: consumo do JSON via API.
2. Normalização: estruturação dos dados em formato tabular.
3. Transformação e Limpeza: tratamento de valores nulos, conversão de tipos, renomeação de colunas.
4. Análise Exploratória: visualização de padrões de evasão, correlações e estatísticas descritivas.
5. Conclusões: resumo dos principais achados e recomendações.

📈 Exemplos de Resultados

Análise de Evasão de Clientes (CHURN)
![alt text](<ANÁLISE DE EVASÃO DE CLIENTES (CHURN)-2.png>)
Análise de tendencias e oportunidades  - Fatores do CHURN
![alt text](<ANÁLISE DE TENDÊNCIAS E OPORTUNIDADES-1.png>)
Análise de Correlação - Fatores do CHURN
![alt text](<ANÁLISE DE CORRELAÇÃO - FATORES DO CHURN-1.png>)


📝 Conclusões e Recomendações

Com base na análise exploratória realizada, foram identificados fatores potenciais que influenciam a evasão de clientes na Telecom X. As recomendações iniciais incluem:

1. Monitoramento de clientes com contratos mensais.
2. Oferta de serviços adicionais para aumentar o engajamento.
3. Melhorias nos canais de atendimento e suporte técnico.

🤝 Contribuições

Contribuições são bem-vindas!
Para contribuir:

Faça um fork.
Crie uma nova branch (git checkout -b feature/minha-contribuicao).
Faça suas alterações.
Envie o commit (git commit -m 'Minha contribuição').
Suba a branch (git push origin feature/minha-contribuicao).
Abra um Pull Request.





