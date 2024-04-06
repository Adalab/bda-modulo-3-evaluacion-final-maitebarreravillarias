# bda-modulo-3-evaluacion-final-maitebarreravillarias


Ejercicio realizado como evaluación durante el bootcamp DataAnalist en Adalab

El ejercicio consiste en la limpieza y unión de dos csv de datos de clientes con distinta información
realizado en python 3.9.7 
librerías 

import numpy as np
import pandas as pd

#!pip install scikit-learn
#!pip install seaborn
#!pip install matplotlib

from sklearn.impute import KNNImputer


from sklearn.experimental import enable_iterative_imputer
from sklearn.impute import IterativeImputer

import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.impute import SimpleImputer

from itertools import combinations