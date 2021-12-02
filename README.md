## Hello World
# Ana Sofía Argüelles 
## Laboratorio - branch - commits  - pull request - merge - markdown


*bold text*

italicized text

1. GitHub
2. Método de calcular als frecuencias
3. Descargar los nuevos archivos de Series y Episodios

- GitHub
- Método de calcular als frecuencias
- Descargar los nuevos archivos de Series y Episodios

````c++
//
//  main.cpp
//  Composicion Triangulo
//
//  Created by Ana Sofía Argüelles  on 18/11/21.
//

#include <iostream>
#include "Punto.hpp"
#include "Triangulo.hpp"
using namespace std;

//Función recibe un arreglo de objetos y la cantidad de elementos a desplegar
void desplegarArregloTriangulo(Triangulo arr[], int iS){
    for(int indice = 0; indice < iS; indice ++)
        cout << arr[indice].str() << endl;
}

void leerArregloTriangulo(Triangulo arrTriangulos[], int iS){
    int x1,y1,x2,y2,x3,y3;
    Punto pto;
    
    for(int indice = 0; indice < iS; indice ++){
        cout << "Ingresa los 3 vertices del triangulo: ";
        cin >> x1 >> y1 >> x2 >> y2 >> x3 >> y3;
        pto.setX(x1);
        pto.setY(y1);
        arrTriangulos[indice].setVertice1(pto);
        pto.setX(x2);
        pto.setY(y2);
        arrTriangulos[indice].setVertice2(pto);
        pto.setX(x3);
        pto.setY(y3);
        arrTriangulos[indice].setVertice3(pto);
    }
}

````
  
  
----
  
[Markdown](https://www.markdownguide.org/cheat-sheet/)
  
![Foto de playita](playa.jpg)
  
  
  
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

- [x] Proyecto progra
- [ ] Proyecto bloque
- [ ] Examen mate

```` c++
Serie::Serie(std::string _id, std::string _titulo, int _duracion, std::string _genero, double _calificacionPromedio, int _cantEpisodios){
    id = _id;
    titulo = _titulo;
    duracion = _duracion;
    genero = _genero;
    calificacionPromedio = _calificacionPromedio;
    cantEpisodios = _cantEpisodios;
}
````
