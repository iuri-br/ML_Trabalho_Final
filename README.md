# ML_Trabalho_Final
Trabalho final da disciplina de Machine Learning - Pós-graduação em Data Science na Faesa, pelos alunos Iúri Brandão e Júlio Scopel.

## Importante!

Nesse repositório há dois _Notebooks_ Jupyter, sendo que no arquivo mais recente foram realizados tratamentos dos dados (_feature engineering_), de modo a *trazer os valores zerados de insulina e glicose, dentre outros, para perto da realidade*.

## Instruções

1. Pesquise e selecione uma coleção (https://archive.ics.uci.edu/ , https://www.kaggle.com/ , outra fonte de sua escolha desde que coloque a referência);
2. Selecione três modelos de aprendizagem de máquina para aplicar a coleção;
3. Explique o funcionamento dos modelos selecionados;
4. Compare os resultados obtidos por cada modelo e destaque as nuances de cada um, utilize gráficos para comparação das métricas e comente os resultados;
5. A entrega deverá ser feita através da publicação no Github em modo público do Notebook gerado;
6. Todos componentes dos grupos deverão enviar o trabalho no AVA no formato PDF gerado a partir do Notebook;
7. O trabalho pode ser realizado em grupos de até 3 pessoas;
8. Não serão aceitos trabalhos idênticos;
9. Coloque todas as referências externas utilizadas para confecção do trabalho.

## Descrição

O objetivo do trabalho é avaliar o Dataset *diabetes.csv*, disponível em https://www.kaggle.com/uciml/pima-indians-diabetes-database, realizando análise exploratória e executando o aprendizado de máquina (_machine learning_) utilizando três modelos de aprendizagem, que serão discutidos ao longo do desenvolvimento do trabalho.

## Passos / Desenvolvimento do _Notebook_ Jupyter

1. Carregamento dos dados;
2. Análise exploratória;
3. Tratamento dos dados;
4. Definição dos modelos de aprendizagem;
5. Utilização dos modelos;
6. Discussão dos resultados.

## Atributos do _Dataset_ (descrição obtida no site fonte do arquivo)
1. Number of times pregnant
2. Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. Diastolic blood pressure (mm Hg)
4. Triceps skin fold thickness (mm)
5. 2-Hour serum insulin (mu U/ml)
6. Body mass index (weight in kg/(height in m)^2)
7. Diabetes pedigree function
8. Age (years)
9. Class variable (0 or 1)

## Resultado

O resultado das análises consta no final dos _Notebooks_ Jupyter presente nesse repositório.
*Importante frisar a diferença obtida nos resultados sem e com a _feature engineering_, de modo com que os preditores e seus fatores de importância estejam mais próximos da realidade - compare os _Notebooks_ e perceba a diferença*. Compare, por exemplo, o gráfico de importância das variáveis e veja como é importante o tratamento de dados zerados, bem como o entendimento do significado de cada preditor.

## Informações Complementares:
- https://www.endocrino.org.br/10-coisas-que-voce-precisa-saber-sobre-diabetes/
- https://www.vooo.pro/insights/um-tutorial-completo-sobre-a-modelagem-baseada-em-tree-arvore-do-zero-em-r-python/
- https://medium.com/machina-sapiens/o-algoritmo-da-floresta-aleat%C3%B3ria-3545f6babdf8
- https://www.vooo.pro/insights/6-passos-faceis-para-aprender-o-algoritmo-naive-bayes-com-o-codigo-em-python/
- https://www.dezyre.com/article/top-10-machine-learning-algorithms/202



