# dio-azure-atividade-0
Trabalhando com Machine Learning na prática no Azure ML.

O foco deste trabalho é treinar um modelo de regressão usando o serviço de computação em núvem do Azure Machine Learning. O conjunto de dados utilizado está presente em [LINK](https://aka.ms/bike-rentals).

## Acessando ambiente

Inicialmente, no menu de criação de recursos, busque pelo serviço Azure Machine Learning.
<p align="center">
  <img src="./imagens/azure_machine_learning.png" width="150">
</p>

Em seguida, a após criar uma instância, acesse o ambiente de trabalho criado.

<p align="center">
  <img src="./imagens/acessando_ambiente_criado.png" width="350">
</p>

Após acessar o ambiente, selecione a opção de entrar no Azure Machine Learning Studio.

<p align="center">
  <img src="./imagens/acessando_ambiente.png" width="350">
</p>

## Criando trabalho

Para criar um trabalho de aprendizado de máquina, foi utilizado o ML automatizado, que se encontra na barra lateral esquerda.

<p align="center">
  <img src="./imagens/ml_automatizado.png" width="350">
</p>

Posteriormente, crie um novo trabalho.

<p align="center">
  <img src="./imagens/criando_novo_trabalho.png" width="350">
</p>

Defina o nome do trabalho, do experimento e dê uma breve descrição.

<p align="center">
  <img src="./imagens/configuracoes_basicas.png" width="350">
</p>

Defina a tarefa como Regressão e adicione o conjunto de dados

<p align="center">
  <img src="./imagens/tipo_de_tarefa.png" width="500">
  <img src="./imagens/criando_dataset_1.png" width="500">
  <img src="./imagens/criando_dataset_2.png" width="500">
  <img src="./imagens/criando_dataset_3.png" width="500">
  <img src="./imagens/criando_dataset_4.png" width="500">
</p>

Configure as opções de realização da tarefa de treinamento, como variàvel a ser predita, tipo de modelo, limites e configuração de validação e teste.

<p align="center">
  <img src="./imagens/configurando_tarefa_0.png" width="500">
  <img src="./imagens/configurando_tarefa_1.png" width="500">
  <img src="./imagens/configurando_tarefa_2.png" width="500">
</p>

Determine a opção de computação da tarefa, envie o trabalho para ser realizado e aguarde ele ser realizado.

<p align="center">
  <img src="./imagens/computacao.png" width="500">
  <img src="./imagens/enviando_trabalho.png" width="500">
  <img src="./imagens/aguardar_trabalho.png" width="500">
</p>

## Verificando encerramento do trabalho

Para verificar o estado do trabalho, acesse a aba "jobs" na barra lateral esquerda.

<p align="center">
  <img src="./imagens/aba_jobs.png" width="250">
</p>

Quando ele estiver encerrado, seu status estará como Concluído em verde.

<p align="center">
  <img src="./imagens/trabalho_concluido.png" width="500">
</p>

## Avaliando modelos

Para avaliar os modelos, acesse o trabalho, clique na aba Modelos + trabalhos filho e clique na aba Métricas. Além disso, é possível avaliar as métricas do treinamento e comparar os modelos.

<p align="center">
  <img src="./imagens/acessando_trabalho.png" width="500">
  <img src="./imagens/selecionando_modelos_v2.png" width="500">
  <img src="./imagens/verificando_metricas.png" width="500">
</p>

## Conclusão

Portanto, foi possível treinar três modelos de regressão para predizer o custo de alguguel de biclicletas e de acordo com a métrica _NormalizedRootMeanSquaredError_ o modelo combinado _VotingEnsemble_ apresentou o menor erro.
