# Recomendations
A recommendation algorithm that uses bigraphs formed by client-product interaction and meta heuristics to generate product recommendations.


This repository has 3 files here is a brief explanation of each one:
## Recomendador.ipynb
This file has the main recomendation system functionalities along with some accuracy tests, in order for the file to work **you have to compile the files in the src folder** which contain a cluster algorithm written in C++ , there are no extra libraries to download simply run g++: 
```
g++ -o ARMPB src/*.cpp
```

## Analise Inicial.ipynb
This file contains the first exploratory analysis of the database which gave me informations that I used to adapt the clustering algorith in order to get a better result.

## Agrupador_python.ipynb
This file is a prototype of a clustering algorith based on graphs created in python, it was used as a basis for learnign the c++ algorithm.
