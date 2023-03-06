# Tópicos Especiais em Computação: Semântica e Recuperação de Informação

Notebooks Colab das atividades práticas da disciplina de Tópicos Especiais em Computação: Semântica e Recuperação de Informação.

## **Preparação**

Para executar os notebooks siga os passos abaixo.
1. Crie a pasta **"Colab Notebooks"** na raiz do seu google drive para receber a pasta do projeto. Outros projetos utilizando Colab Notebooks podem ser criados na mesma pasta.
2. Dentro da pasta **"Colab Notebooks"** crie a pasta **"SRI"** para armazenar e executar os notebooks das atividades práticas da disciplina.
3. Dentro da pasta **"SRI"** crie a pasta **"data"** e coloque o arquivo de dados [**documentos.csv**](https://github.com/osmarbraz/sri/blob/main/data/documentos.csv). Este arquivo é o conjunto de dados utilizados na prática.

## **Execução**
Posteriormente os notebooks podem ser executados em ordem sequencial.

## Notebooks
1. [**Segmentacao_Limpeza_v1.ipynb**](https://github.com/osmarbraz/sri/blob/main/1_Segmentacao_Limpeza_v1.ipynb) - Realiza a limpeza e segmentação dos documentos.
2. [**GerarPOS_v1.ipynb**](https://github.com/osmarbraz/sri/blob/main/2_GerarPOS_v1.ipynb) - Gera as PoSTagging do documento utilizando o spaCy.
3. [**AnaliseDados_v1.ipynb**](https://github.com/osmarbraz/sri/blob/main/3_AnaliseDados_v1.ipynb) - Realiza análises estatísticas dos documentos.
4. [**NER_spaCy_v1.ipynb**](https://github.com/osmarbraz/sri/blob/main/4_NER_spaCy_v1.ipynb) - Realiza reconhecimento de entidades nomeadas em textos.
5. Embeddings
	- 5.1. [**Embeddings_Word2Vec_Gensim_v1.ipynb**](https://github.com/osmarbraz/sri/blob/main/5_1_Embeddings_Word2Vec_Gensim_v1.ipynb) - Examinando embeddings de palavras gerados com Word2Vec.
	- 5.2. [**Embeddings_BERT_Huggingface_v1.ipynb**](https://github.com/osmarbraz/sri/blob/main/5_2_Embeddings_BERT_Huggingface_v1.ipynb) - Examinando embeddings de palavras e sentenças gerados com BERT.

[Apresentação do fluxo de uso dos notebooks.](https://docs.google.com/presentation/d/1W5TRri89JVVyQVGz9IOeQIa9jk186w4c/edit#slide=id.gf4978a6ef2_0_24)

## Conjunto de dados
O conjunto de dados utilizado pelos notebooks é formado por 20 documentos extraído do conjunto de dados CSTNews. 

* [**documentos.csv**](https://github.com/osmarbraz/sri/blob/main/data/documentos.csv)

Clique aqui para acesssar o conjunto de dados completo [**CSTNews**](https://sites.icmc.usp.br/taspardo/sucinto/files/CSTNews%206.0.zip). 

**Referência**
- ALEIXO, Priscila; PARDO, Thiago Alexandre Salgueiro. CSTNews: um córpus de textos jornalísticos anotados segundo a teoria discursiva multidocumento CST (Cross-document Structure Theory. 2008.

## Documentação Google Colaboratory

**Guia Colab Iniciante:**
https://medium.com/machina-sapiens/google-colab-guia-do-iniciante-334d70aad531

**Documentação oficial:**
https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/01.01-Help-And-Documentation.ipynb
 
**Características :**
https://colab.research.google.com/notebooks/basic_features_overview.ipynb