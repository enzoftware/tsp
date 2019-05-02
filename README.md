<img src="https://showme0-9071.kxcdn.com/files/67452/pictures/thumbs/229680/first_thumb1337998020.jpg" height="250px"/>

## Traveling Salesman Problem : Backtracking 

La generacion del archivo ```outfile.csv``` se hace por medio de python, solo por motivos didacticos. En futuras implementaciones se automitazara este proceso.

Para generar el archivo corra e ingrese el nombre del ```DISTRITO``` del que desea obtener la ruta:

```
python3 read_file.py
Ingresa el distrito : SURCO
```


Esto generara el archivo con el cual trabajara la solucion.

Esta solucion esta desarrollada con Javascript, por lo tanto es requisito tener instalado NodeJS.

Para poder empezar el proyecto se de correr los siguientes comandos : 
```
npm install
npm start
```

### Analisis: 

Al ser backtracking se probaran todas las posibles combinaciones para resolver el algoritmo, cabe resaltar que no es el metodo mas eficiente para resolver este problema.

Se llamara al metodo ```tsp_backtrack()``` n! veces, siendo n el numero de ciudades por recorrer.
