NUMPY
BIBLIOTECA CENTRAL, POIS OUTRAS BIBLIOTECAS UTILIZANDO BIBLIOTECAS DO NUMPY

ARRAY ESTRUTURA DE GRADES QUE ARMAZENA DADOS SENDO O OBJETO PRINCIPAL DO NUMPY

CADA DIMENSÃO DE UM ARRAY PODE TER VARIAS DIMENSÕES POREM SO UM TIPO DE DADOS

import numpy as np

np.zeros() #TODOS OS ELEMENTOS DO ARRAY ZERO e ele recebe uma tupla tendo que escrever com () a dimensão

np.arange() #Números ate a onde voce quiser -1

np.random.random() #Numeros aleatorios

np.random é um modulo da numpy

-----------------------------------------
array são mais rapidos do que listas 

ARRAY Podem ser 3D

VETOR É UM TIPO DE ARRAY

-------------------------------------
TIPOS DE DADOS DE UM ARRAY NUMPY
INT62
INT32
FLOAT64
FLOAT32

PODEMOS UTILIZAR DISSO PARA ECONOMIZAR MEMORIA NA HORA DE ALOCAR

USANDO O dtype = np.o tipo que queremos utilizar no array

hierarquia
float adicionado em um array de int transforma em float

inteiro em um array de boleanos transformara em inteiro

consigo manipular um int para boleano e o que é 0 fica false e o restante true

-------------------------------------

PARA SELECIONAR SOMENTE UMA COLUNA INTEIRA EU USO ":", E O INDEX

para fatiar (slicing) um array de 2 dimensão
coloco [linhha:coluna, linha:coluna] que ele se encontra

eixo(axis tenho 0(vertical) e o 1(horizontal))

