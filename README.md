
<h1 align="center"> Análise de dados e NLP - modelagem de tópicos </h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/LucasPereiraMiranda/topic-modeling">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/LucasPereiraMiranda/topic-modeling">
  
  <a href="https://github.com/LucasPereiraMiranda/topic-modeling/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/LucasPereiraMiranda/topic-modeling">
  </a>

  <a href="https://github.com/LucasPereiraMiranda/topic-modeling/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/LucasPereiraMiranda/topic-modeling">
  </a>

  <a href="https://github.com/LucasPereiraMiranda/topic-modeling/issues-pr/">
    <img alt="Repository Pull Request" src="https://img.shields.io/github/issues-pr/LucasPereiraMiranda/topic-modeling">
  </a>

  <a href="https://github.com/LucasPereiraMiranda/nlw-01-ecoleta/issues">
    <img alt="GitHub license" src="https://img.shields.io/github/license/LucasPereiraMiranda/topic-modeling">
  </a>
</p>

<p align="justify"> Repositório para o trabalho final da disciplina (CSI-001) Análise de Mídias Sociais - UFOP. O presente trabalho visa inferir tópicos em mensagens de mídias
sociais utilizando modelos LDA e realizar análises a partir desses tópicos.
</p>

## Objetivos
```
  - [x] Iniciar o Projeto
  - [x] Criar rotinas para pre-processamento das mensagens
  - [x] Definir se será aplicada uma estratégia de Stemming
  - [x] Definir o número de topicos que serão gerados
  - [x] Avaliar os tópicos gerados
```

## Techs

A análise está sendo realizada com as seguintes tecnologias

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)


## Como fazer a análise?

Instale as dependências necessárias no seu ambiente python3 (ou virtualenv)

- requiriments.txt possui as dependências básicas necessárias para o projeto

```shell
  pip3 install -r requirements.txt
```

Para processar os posts e comentarios é necessário ter o arquivo da coleta
indicado em data/.gitkepp (os arquivo resultantes da coleta não estão presentes no repositório, apenas os processados)


## Como criar um ambiente virtual (virtualenv) para o projeto? (opcional)

- Com o python3 já instalado em seu computador, execute:

```shell
  pip3 install virtualenv
```

- Crie um novo ambiente virtual executando:

```shell
  virtualenv venv # venv é o nome do seu ambiente virtual isolado
```

- Ative o seu ambiente virtual executando:

```shell
  source /venv/bin/activate # Linux ou Mac
```
```powershell
  venv\Scripts\activate # Windows
```

- Instale as dependências ao seu ambiente virtual executando:

```shell
  pip3 install -r requirements.txt
```

## Licença
[MIT](https://choosealicense.com/licenses/mit/)