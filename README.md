## $\textcolor{purple}{\text{Brillo_de_Cafeidas}}$

En este proyecto se utiliza una red neuronal $\text{LSTM}$ para predecir el brillo de Cefeidas clásicas observadas por [ASAS-SN](https://asas-sn.osu.edu/variables) (All-Sky Automated Survey for Supernovae) [Shappee et al. (2014)](https://ui.adsabs.harvard.edu/abs/2014ApJ...788...48S/abstract), especialmente en $ASASSN-V J125312.38-675751.3$, una estrella variable de tipo $\text{DCEP}$ con un período de $3.40136$ días. 

El objetivo es modelar la curva de luz para anticipar variaciones de brillo, utilizando datos de $ASASSN-V J125312.38-675751.3$ [Jayasinghe et al. (2018a)](https://ui.adsabs.harvard.edu/abs/2018MNRAS.477.3145J/abstract) con $517$ observaciones, reducidas a $506$ tras filtrar magnitudes entre $13.3$ y $15.6$, y a $502$ tras aplicar suavizado.
