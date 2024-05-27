# libreia_drive

# instalar librerías necesarias
!pip install pandas
!pip install yfinance
!pip install pandas-datareader

# Importar librerías

# Pandas
import numpy as np
import pandas as pd

# Otras
import matplotlib.pyplot as plt
import datetime as dt
from random import sample
import seaborn as sns

import pandas_datareader as web # pip install pandas-datareader
import yfinance as yf # pip install yfinance

# Montar Google Drive para acceder a los archivos de la carpeta
from google.colab import drive
drive.mount('/content/drive')

import os
# Modifica la siguiente instrucción si guardaste la carpeta
# en una ubicación diferente a "My Drive"
folder_path ='/content/drive/My Drive'
os.chdir(folder_path) # Change directory
print("Nuevo directorio de trabajo: ")
!pwd

# Revisar los archivos en el nuevo directorio
!ls
