# Análise de Dados Desafio Lighthouse - Indicum  
<img width="50" height="50" alt="projetor-de-cinema" src="https://github.com/user-attachments/assets/23428581-ed6e-480e-94c0-9a3bc0c56c5a" />




Este projeto apresenta uma análise completa dos fatores que impulsionam o sucesso cinematográfico, com o objetivo de fornecer recomendações estratégicas baseadas em dados para a próxima grande produção do estúdio PProductions. 
A partir de uma análise exploratória e da construção de um modelo preditivo, este repositório detalha o processo e as conclusões.


## Principais Insights e Conclusões:


A análise revelou uma clara 'receita para o sucesso', destacando que:

•	*Gênero Híbrido é a Chave*: Filmes que mesclam a profundidade do Drama com o apelo comercial da Ação ou Crime têm o maior potencial de sucesso equilibrado.

•	*Popularidade Impulsiona a Receita*: O número de votos (envolvimento do público) é o indicador mais forte de sucesso financeiro, superando até a nota da crítica.

•	*Talento Comprovado Reduz o Risco*: Investir em diretores e atores de renome é uma estratégia sólida para garantir visibilidade e desempenho.

## Estrutura do Projeto:

O repositório está organizado da seguinte forma:

•	/data: Contém o dataset original desafio_imdb.csv.

•	/notebook: Inclui o Jupyter Notebook Análise_Cinematográfica.ipynb com todo o código de limpeza, análise exploratória (EDA) e modelagem.

•	/modelo: Armazena o modelo de previsão treinado e salvo (imdb_rating_predictor.pkl).

•	/relatorio: Contém o relatório final Relatório de Análise Cinematográfica.pdf com os insights e as recomendações de negócio.

•	requirements.txt: Lista de todas as bibliotecas Python necessárias para reproduzir o ambiente e executar o projeto
.
•	README.md: Este arquivo, que serve como guia para o repositório.


### Configuração e Execução:

Siga os passos abaixo para configurar o ambiente e executar a análise no seu computador.

#### Pré-requisitos:

•	Python 3.8 ou superior

•	pip (gestor de pacotes do Python)

##### 1. Clonar o Repositório
   
Primeiro, clone este repositório para a sua máquina local usando o seguinte comando no seu terminal:

git clone <URL-DO-SEU-REPOSITÓRIO-AQUI>

cd <NOME-DO-SEU-REPOSITÓRIO>



##### 2. Criar um Ambiente Virtual (Recomendado)
   
É uma boa prática criar um ambiente virtual para isolar as dependências do projeto e evitar conflitos com outras instalações do Python.

##### Para Windows

python -m venv venv

venv\Scripts\activate

##### Para macOS/Linux

python3 -m venv venv

source venv/bin/activate


##### 3. Instalar as Dependências
   
Com o ambiente virtual ativado, instale todas as bibliotecas necessárias com um único comando:

pip install -r requirements.txt


##### 4. Executar a Análise
   
Para visualizar e reexecutar a análise exploratória e o processo de modelagem, inicie o Jupyter Notebook:

jupyter notebook notebook/Análise_Cinematográfica_treino.ipynb




#### Ferramentas Utilizadas

•	Linguagem: Python 3

•	Bibliotecas Principais:

o	Pandas: para manipulação e análise de dados.

o	Matplotlib & Seaborn: para visualização de dados.

o	Scikit-learn: para a construção do modelo de machine learning (RandomForestRegressor).

o	Jupyter Notebook: como ambiente de desenvolvimento da análise.


### Sobre o Modelo

O modelo preditivo utilizado é um RandomForestRegressor, treinado para prever a nota do IMDB (IMDB_Rating) com base em características-chave do filme, como Meta_score, No_of_Votes e Gross_float. O modelo foi salvo e está disponível no diretório /modelo para ser carregado e utilizado em futuras previsões. 

