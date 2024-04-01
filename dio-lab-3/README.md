# dio-lab-3
O objetivo deste repositório é descrever o passo-a-passo do processo de criação de um serviço de busca em texto automatizada por ia no MIcrosoft Azure. Para mais informações acesse o [LINK](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html).

## Criando serviço de IA

Inicialmente, foi criado o serviço de IA do Microsoft Azure.

<p align="center">
  <img src="./imagens/criando_servico_ia_0.png" width="90%">
</p>

## Criando serviço de busca

Em seguida, foi criado o serviço de busca _Azure AI services_.

<p align="center">
  <img src="./imagens/criando_servico_ia_busca_0.png" width="25%">
</p>

Algumas configurações do serviço:

<p align="center">
  <img src="./imagens/criando_servico_ia_busca_1.png" width="45%">
  <img src="./imagens/criando_servico_ia_busca_2.png" width="45%">
</p>

## Criando serviço de armazenamento

Para armazenar os dados, foi criado um serviço de armazenamento, chamado _Storage account_. Abaixo estão as configurações usadas para cria-lo.

<p align="center">
  <img src="./imagens/criando_storage_0.png" width="45%">
  <img src="./imagens/criando_storage_1.png" width="45%">
  <img src="./imagens/criando_storage_2.png" width="45%">
</p>

### Adicionando arquivos de teste

Os arquivos de teste, fornecidos pela Microsoft, podem ser baixados neste [LINK](https://aka.ms/mslearn-coffee-reviews). A seguir, foram demonstrados os passos para adicionar os arquivos no _container_.

<p align="center">
  <img src="./imagens/adicionando_arquivos_0.png" width="45%">
  <img src="./imagens/adicionando_arquivos_1.png" width="45%">
  <img src="./imagens/adicionando_arquivos_2.png" width="45%">
  <img src="./imagens/adicionando_arquivos_3.png" width="45%">
  <img src="./imagens/adicionando_arquivos_4.png" width="45%">
  <img src="./imagens/adicionando_arquivos_5.png" width="45%">
  <img src="./imagens/adicionando_arquivos_6.png" width="45%">
</p>

### Verificando arquivos

O passo a seguir foca em apenas verificar se os dados estão prontos para uso. Busque na aba _Indexers_.

<p align="center">
  <img src="./imagens/verificando_arquivos_0.png" width="90%">
</p>

## Resultados

No _Search explorer_, para o index **coffe-index**, será possivel realizar algumas buscas. A primeira imagem apresenta uma busca sem filtro, retornando os dados de todos os arquivos de teste. A segunda imagem apresenta uma busca com a palavra chave **Chicago** no contexto de **localizações**, retornando quantos itens foram encontrados. E por último,
na terceira imagem, uma busca por **sentimentos negativos**, informando a mais quantos casos foram encontrados.

<p align="center">
  <img src="./imagens/resultado_0.png" width="45%">
  <img src="./imagens/resultado_1.png" width="45%">
  <img src="./imagens/resultado_2.png" width="45%">
</p>

## Conclusão

Portanto, foi possível realizar a atividade de criar o ambiente de busca em arquivos com serviços de IA, que realizava analizes em uma base de textos não estruturada, que foi fornecida pela Microsoft.
