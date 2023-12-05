# AlgorytmyPython

Celem tego projektu jest znalezienie jak najlepszego rozwiązania gry / puzzli CORRAL lub inaczej nazywane CAVE - puzzle za pomocą algorytmu genetycznego. Cel gry jest bardzo prosty jest nim narysowanie pojedynczej zamkniętej pętli wzdłuż linii siatki, która się nie przecina. Pętla musi obejmować wszystkie liczby. Liczby w siatce wskazują, ile komórek wewnątrz pętli można zawrzeć poziomo i pionowo, włączając samą komórkę. W projekcie porównywane będą czasy działania na danych o różnej wielkości.

#Algorytm genetyczny
# Importujemy wszytskie potrzebne nam biblioteki
import numpy as np
import random
import time
import pygad
import math
