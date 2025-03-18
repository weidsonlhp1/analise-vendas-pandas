# analise-vendas-pandas
projeto de análise de vendas usando python, pandas, matplotlib, numpy
import pandas as pd 
import numpy as np 
import matplotlib.pyplot as plt 
import seaborn as sns
df = pd.read_csv('Gas.csv', sep=';')
del df['Unnamed: 0']
# pesquisa feita de 2004 a 2019
df['ANO'].unique()
# comparação entre GASOLINA COMUM e ETANOL HIDRATADO
df['PRODUTO'].unique()
# Quantidade de registros existem de cada tipo de gasolina.
df['PRODUTO'].value_counts()
