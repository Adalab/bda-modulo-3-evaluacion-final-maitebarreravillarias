# bda-modulo-3-evaluacion-final-maitebarreravillarias


Ejercicio realizado como evaluación durante el bootcamp DataAnalist en Adalab
Módulo 3. Limpieza, transformación de datos, visualización y A/B testing

El ejercicio consiste en la limpieza (homogeneización de nombres de columnas, imputación de nulos, retirada de duplicados, cambio de tipos) y finalmente unión de dos csv de datos de clientes con distinta información.

Visualización de una serie de relaciones entre los datos.

Finalmente, realización A/B testing 



This exercise was completed as an evaluation during the DataAnalyst bootcamp at Adalab, specifically within Module 3, which covers data cleaning, transformation, visualization, and A/B testing.

The exercise involved the following steps:

    Cleaning the data (standardizing column names, handling missing values, removing duplicates, changing data types)
    Merging two CSV files containing customer data with different information
    Visualizing relationships between the data
    Conducting A/B testing

Tools and Libraries

    Python 3.9.7
    Libraries used:
        numpy
        pandas
        scikit-learn
        seaborn
        matplotlib

Installation

bash

pip install scikit-learn
pip install seaborn
pip install matplotlib

Libraries and Modules

python

import numpy as np
import pandas as pd

from sklearn.impute import KNNImputer
from sklearn.experimental import enable_iterative_imputer
from sklearn.impute import IterativeImputer
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.impute import SimpleImputer
from itertools import combinations

Please note that some libraries may need to be installed using pip before running the code.
Execution

The exercise was executed in Python using various data manipulation and visualization techniques. Detailed steps and code snippets can be found in the relevant files within the project directory.
Contact Information

For any questions or inquiries, please contact [Maite Barrera Villarias] at [maitebarreravillarias@gmail.com].

