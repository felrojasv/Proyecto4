# Proyecto4
Sección 4.1:

Para esta sección se define la función demulador 16QAM, esta asigna la cantidad de muestras de la señal Rx, la cantidad de bits y los respectivos vectores de emulación. 
Respecto a la función de emulación se definión en dos secciones, las cuales comprenden las funciones seno y coseno, al igual que dos señales Tx las cuales previamente fueron sumadas. 
Cuatro bucles asignan los 4 valores de bits de forma adecuada a cada una de las señales tx, esto se puede observar en la figura adjunta. Una vez definido el modulador se utiliza el código brindado por el Laboratorio 4 para la transmisión de, modulación y desmodulación de la imagen utilizada. 
Por último, se grafica la señales modulada y demodulada para su comparación, acá se aprecia que la diferencia es poco significativa, dado que el código tiene gran captación de los bits. 

![image](https://user-images.githubusercontent.com/85850836/124696552-8ad1b700-dea2-11eb-978b-d0b236755d54.png)

Los resultados obtenidos despues de la modulación son los siguientes:

![1](https://user-images.githubusercontent.com/85850836/125560682-b91edb37-0b97-4ce1-a93a-d846af1103b9.jpg)

Es importante resaltar que el lapso de tiempo ejecutado en la simulación es realmente largo, sin embargo, para garantizar su funcionamiento se utilizó un segmento del vector de bits. 

Sección 4.2:

Al realizar esta parte, se tomó un bloque de código presentado en el Laboratorio 4 para desarrollar la simulación de la señal Tx, al analizar las gráficas obtenidas se puede observar que los resultados teóricos
y experimentales son realmente similares, los promedios son constantes en el tiempo y hay estacionaridad. 

![2](https://user-images.githubusercontent.com/85850836/125560979-f800092b-3f3b-491c-858c-9901859a90a6.png)



Sección 4.3: 

Para poder obtener la densidad espectral de potencia se usó el módulo de scipy respectivo a la transformada de Fourier y con ella transformar la señal Tx.

![3](https://user-images.githubusercontent.com/85850836/125560884-ccc82b78-a847-4eb9-8a22-df77e95e6750.png)
