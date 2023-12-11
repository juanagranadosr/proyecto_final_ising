# proyecto_final_ising
En el siguiente repositorio se encuentra dos archivos de código para la simulación de una cadena de Markov y del Modelo de Ising en 2D. La optimización del código y su algoritmo fue tomado de https://jakevdp.github.io/blog/2017/12/11/live-coding-cython-ising-model/.

# Archivos
- En las carpetas `./beta020`, `./beta044` y `./beta090` contienen las figuras obtenidas para los valores de $\beta$ de $0.20, 0.44$ y $0.90$, respectivamente. El nombre de cada imagen hace referencua al número de iteración en el que se guardó (ej. `020image100.jpg` hace referencia al paso $100$ del $\beta=0.2$). Se tienen además dos `.gif` que muestran la evolucion temporal cada $1000$ iteraciones y una gráfica de energia total del sistema en función de las iteraciones.
- En el cuaderno de Jupyter `Markov_Chains.ipynb` está documentado el código para simular una cadena de Markov de longitud a escoger.
- En el cuaderno de Jupyter `Ising_Model.ipynb` está documentado el código para simular el Modelo de Ising en un grid de $N\times N$, las visualizaciones y las instrucciones para replicar las gráficas obtenidas en el informe del proyecto final del curso de Probabilidad de Honores.
