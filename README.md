# CaixaBank-Tech-Challange-
Este es uno de los retos clasificatorios que forman parte del hackathon online de CaixaBank Tech. 
________________________________________
Background
Overview: the dataset and challenge
Se emplearán tres datasets: el dataset de training, el dataset de tweets, dataset de test.

Reto:
Desarrollar un modelo predictivo que permita predecir la variable target (si el precio de cierre del IBEX35 será superior o inferior al precio de cierre actual).
Librerias Necesarias
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import classification_report


