# AR-A-TM
Aprendizaje Reforzado - Adicional - Terminos Matematicos
### Definiciones ###
1. ArgMax  
2. Gradiente
3. Probabilidad Condicionada
4. Media Ponderada

### 1. ArgMax ###
Son los argumentos de una funcion que pasados a la misma producen que obtenga su valor maximo.

Por ejemplo, si f(x) es 1-|x| luego f alcanza su valor máximo de 1 solo en el punto x=0. Por lo tanto

![99397a494944b20515578803ab0c651b93887bc8](https://user-images.githubusercontent.com/95035101/201491103-a90c6e31-2324-4d5d-92eb-a2a7e9b16abb.svg)

### 2. Gradiente ###
El vector de gradiente de f en el punto (x0,y0) es perpendicular a la curva de nivel de f que contiene el punto (x0,y0), es decir, la curva de nivel f(x0,y0)=k.

![4tIrxcSxgGzRfW1yQhV5HuVh6i5qUWrYKZpokBZOv4QpFO4jSfjnBXK6vfjzVg_D847_Sk2iRB8Bf0jV-CFyLl03rJjiktWDsOc5U-mMH3wTHNuW5PQTVXaFWn8BBFMK9QCVsoc](https://user-images.githubusercontent.com/95035101/201492083-e275a57d-77ac-476e-8641-f585d3e1878e.jpg)

#### El símbolo ∇ se conoce como "nabla" y representa al vector gradiente ####

### 3. Probabilidad Condicionada ###
La probabilidad condicional de A dado B está definida como:

![d1804505c0de877b843b29d645f394a9615e726b](https://user-images.githubusercontent.com/95035101/201494916-5e76ea63-7378-4344-8579-43a82bd643ca.svg)

Ejemplo: 

P(A) = 0,6   
P(B) = 0,4  
P(A∩B) = 0,18  

![probabilidad-condicional-ejercicios-3](https://user-images.githubusercontent.com/95035101/201494983-7e5279a5-21f1-431a-9a0c-953351256916.jpg)

### 4. Media Ponderada ###
La media Ponderada es un promedio de todos los datos teniendo en cuenta el peso que tiene cada uno de estos datos en el resultado final.

![media-ponderada](https://user-images.githubusercontent.com/95035101/201539866-94cfed3c-4f9e-433d-a491-a809fac73658.jpg)

A cada observación del conjunto de datos (X1,X2,…,XN) unos pesos (p1,p2,…,pN) según la importancia de cada elemento.

![media-ponderada](https://user-images.githubusercontent.com/95035101/201539912-9518d900-efad-494d-ae6c-c1fe9e31b043.jpg)

Cuanto más grande sea el peso de un elemento, más importante se considera que es éste.  

Ejemplo  

La nota final de una asignatura es una media ponderada de las notas que han obtenido los alumnos en los cuatro elementos evaluables que determina el profesor. El responsable de la asignatura otorga un peso de 3 al examen inicial, de 1 al trabajo entregable, 2 al trabajo final y 4 al examen final. Las notas de un alumno han sido las siguientes:  

![ejemplo-notas-datos](https://user-images.githubusercontent.com/95035101/201539956-4a097c2c-59b2-42ad-ab6d-75e116274066.jpg)

Se hace la suma de los productos de las notas por el peso de cada nota y se divide por la suma de los pesos.  

![ejemplo-notas-media-ponderada](https://user-images.githubusercontent.com/95035101/201539992-47d493d6-c25b-4cc3-9afb-2f232153c6ff.jpg)

La nota final del alumno en esta asignatura es de 6,14.






