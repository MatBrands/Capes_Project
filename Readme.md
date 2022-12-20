# Capes_Project
![python](https://img.shields.io/pypi/pyversions/Conda)
![conda](https://img.shields.io/conda/v/conda-forge/python)
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

- Instituição: Universidade Estadual de Santa Cruz
- Curso: Ciência da Computação
- Projeto: Implementação de banco de dados automatizado para armazenamento de dados públicos
- Orientador: Francisco Bruno Souza Oliveira
- Bolsistas: Matheus Miranda Brandão(Fapesb) e Eric Soares Silva (CNPq)

Neste projeto a partir dos dados de trabalhos de conclusão de programa de pós-graduação stricto sensu (teses e dissertação) fornecidos pela CAPES será desenvolvido um agrupador que a partir da análise de palavras-chave, título ou resumo será identificado a área de conhecimento aplicada.

Utilizando o Python será feita a tratativa desses dados, agrupando-os a partir da frequência das palavras nos trabalhas das áreas de avaliação. Inicialmente será desenvolvida utilizando os dados dos anos 2013~2016 e posteriormente expandindo o seu período...

Conteúdo:
- Recomendações
- Integrantes
- Instalação
- Base de dados
- Organização
- Contribuições

## Recomendações
- Cada desenvolvedor terá sua branch para ficar a vontade para inserir novas funcionalidades ao projeto.
- Ao desenvolver uma nova funcionalidade o dev deverá solicitar o Pull Request comentando o que foi feito.
- Em relação aos commits será utilizado um padrão
    - Novas features. Ex: git commit -m "Create: Readme"
    - Updates. Ex: git commit -m "Update: Readme"
    - Remoção. Ex: git commit -m "Removed: Readme"

## Integrantes
Projeto desenvolvido pelos Devs:

- [Matheus Miranda Brandão](https://github.com/MatBrands)
- [Eric Soares Silva](https://github.com/Ericsx2)

## Instalação
No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://conda.io/). Portanto para prosseguir necessita-se de sua [instalação](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Instalar dependências
```sh
cd utils/
conda env create environment.yml
```

- Ativar
```sh
conda activate cluster_capes_venv
```

- Desativar
```sh
conda deactivate
```

## Base de dados
Por conta do tamanho das bases segue os comandos para download.

```sh
wget https://dadosabertos.capes.gov.br/dataset/4b0780eb-5ba4-48d4-8d6a-0b77c56f2fd7/resource/49155638-ffc6-4782-a3ca-489bb4345324/download/br-capes-btd-2013a2016-2017-12-01_2013.csv
```

### 2014
```sh
wget https://dadosabertos.capes.gov.br/dataset/4b0780eb-5ba4-48d4-8d6a-0b77c56f2fd7/resource/bf1a79a5-ac49-44e8-b4a5-eca30fb48174/download/br-capes-btd-2013a2016-2017-12-01_2014.csv
```

### 2015
```sh
wget https://dadosabertos.capes.gov.br/dataset/4b0780eb-5ba4-48d4-8d6a-0b77c56f2fd7/resource/e4e2325f-6638-42b3-b801-03c418970a9e/download/br-capes-btd-2013a2016-2017-12-01_2015.csv
```

### 2016
```sh
wget https://dadosabertos.capes.gov.br/dataset/4b0780eb-5ba4-48d4-8d6a-0b77c56f2fd7/resource/7403d9ac-0e71-4539-bc44-8d7aa7b8f452/download/br-capes-btd-2013a2016-2017-12-01_2016.csv
```

### 2017
```sh
wget https://dadosabertos.capes.gov.br/dataset/36d1c92c-f9e0-4da1-a4f0-633e6ebefe03/resource/902bd63b-137f-4090-89e9-cab94f12c41d/download/br-capes-btd-2017a2020-2021-12-03_2017.csv
```

### 2018
```sh
wget https://dadosabertos.capes.gov.br/dataset/36d1c92c-f9e0-4da1-a4f0-633e6ebefe03/resource/638668a6-07da-4c7e-8aab-9044ae3cc753/download/br-capes-btd-2017a2020-2021-12-03_2018.csv
```

### 2019
```sh
wget https://dadosabertos.capes.gov.br/dataset/36d1c92c-f9e0-4da1-a4f0-633e6ebefe03/resource/8f4f2bce-2744-460a-8f14-f1648c7a16df/download/br-capes-btd-2017a2020-2021-12-03_2019.csv
```

### 2020
```sh
wget https://dadosabertos.capes.gov.br/dataset/36d1c92c-f9e0-4da1-a4f0-633e6ebefe03/resource/e37df31a-f250-4405-8b21-ca7e5c7c1696/download/br-capes-btd-2017a2020-2021-12-03_2020.csv
```

## Organização

## Contribuições