## HelloWorld_Grupo2_TC1033
# Irving Yael Agramón Leal
## Laboratorio - commits - pull-request - merge - markdown

**bold text**
*italicized text*

1. Github
2. Método de calcular las frecuencias
3. Descargar los nuevos archivos de Series y Episodios

- Github
- Método de calcular las frecuencias
- Descargar los nuevos archivos de Series y Episodios

```` c++
#include <iostream>
#include "Serie.h"
#include "Episodio.h"
#include "Series.h"

using namespace std;

void leeDatosEpisodio(string &_titulo, int &_temporada, double &_calificacion){
    cout << "Ingrese el título: " << endl;
    cin >> _titulo;
    cout << "Ingrese la temporada: " << endl;
    cin >> _temporada;
    cout << "Ingrese la calificación: " << endl;
    cin >> _calificacion;
}

void leeDatosSerie(string &_id, string &_titulo, int &_duracion, string &_genero, double &_calificacionPromedio, int &_cantEpisodios){
    cout << "Ingrese el Id: " << endl;
    cin >> _id;
    cout << "Ingrese el título: " << endl;
    cin >> _titulo;
    cout << "Ingrese la duración: " << endl;
    cin >> _duracion;
    cout << "Ingrese el genero: " << endl;
    cin >> _genero;
    cout << "Ingrese la calificación promedio: " << endl;
    cin >> _calificacionPromedio;
    cout << "Ingrese la cantidad de episodios: " << endl;
    cin >> _cantEpisodios;
}
````

[markdownguide.org](https://www.markdownguide.org/cheat-sheet/)

![Montañas Odle (Italia)](paisaje.jpg)

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

- [x] Episodios
- [ ] Serie
- [ ] Series
