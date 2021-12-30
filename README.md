# Reconhecimento de Sinais Estáticos da ASL com o uso de CNN

## Sobre
 Este repositório contém a implementação de CNNs para o reconhecimento de sinais estáticos da ASl.

Projeto desenvolvido como Trabalho de Conclusão de Curso, na Universidade do Estado do Amazonas - UEA.

Orientadora: [Profa. Dra. Elloá B. Guedes](https://github.com/elloa)

Aluna: [Nayara da Silva Cerdeira da Costa](https://github.com/nayaracerdeira)

## Conteúdo
<!--ts-->
   * [Sobre](#sobre)
   * [Tabela de Conteudo](#tabela-de-conteúdos)
   * [Como usar](#como-usar)
      * [Pré-requisitos](#pré-requisitos)
      * [Dataset utilizado](#dataset-utilizado)
      * [Executando o projeto](#executando-o-projeto)
   * [Tecnologias](#computer-tecnologias)

  
<!--te-->

---

## Como usar
É necessário a linguagem [Python3+](https://www.python.org/), e as seguintes Bibliotecas:

### Pré-requisitos

* [Tensorflow](https://www.tensorflow.org/)
* [Matplotlib](https://matplotlib.org/)
* [Keras](https://keras.io/)
* [Scikit-Learn](https://scikit-learn.org/stable/)

É recomendado a instalação da distribuição [Anaconda](https://www.anaconda.com/products/individual), pois ela já possui muitos pacotes e biblioteca, ou o uso do [Google Colab](https://colab.research.google.com/) que disponibiliza o uso da GPU.

### Dataset utilizado

O dataset utilizado está disponivel na literatura:
* [STATIC HAND GESTURE ASL DATASET](https://ieee-dataport.org/open-access/static-hand-gesture-asl-dataset)
* [MU HandImages ASL](https://www.massey.ac.nz/~albarcza/gesture_dataset2012.html)

Estrutura do Conjunto de Dados:
```
|-- partition
|   |-- partition-1
|       |-- train # train images ~70%
|           |-- A
|              |-- 0.jpg
|              |-- 1.jpg
|              |-- ...
|           |-- ...
|       |-- test # test images ~20%
|           |-- A
|              |-- 0.jpg
|              |-- 1.jpg
|              |-- ...
|           |-- ...
|       |-- val # test images ~10%
|           |-- A
|              |-- 0.jpg
|              |-- 1.jpg
|              |-- ...
|           |-- ...
|    |--...
```
### Executando o projeto

No Colab Notebook, execute na primeira célula os seguintes comandos:
```
from google.colab import drive
drive.mount(‘/content/gdrive’)
```
```
%cd gdrive/My Drive/project_folder
! git clone https://github.com/NayaraCerdeira/asl_recognition-CNN.git
! git pull

```

Exemplo de Imagens do Dataset:

![base_dados](https://drive.google.com/file/d/12V17Rlhc0e8dgUIn2Hs3xgxwjSJzSxiU/view?usp=sharing)





