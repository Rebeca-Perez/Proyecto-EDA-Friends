# Análisis Exploratorio de Datos sobre la Serie *Friends*

Este proyecto realiza un **análisis exploratorio de datos (EDA)** de la serie de televisión *Friends*, utilizando un dataset con información sobre cada episodio: duración, puntuaciones, número de votos, directores, temporada, entre otros.  
El objetivo es identificar patrones y comprobar varias **hipótesis** relacionadas con la popularidad y la valoración de los episodios.


## Objetivos del Proyecto

1. Analizar la relación entre la **duración de los episodios** y el número de votos.  
2. Comparar el **rating** de los episodios **iniciales y finales** de cada temporada.  
3. Identificar las **temporadas con mejor valoración total**.  
4. Examinar qué **directores** tienen episodios más votados y si uno de ellos es Kevin Bright.  
5. Comparar el rating entre **episodios especiales** y los episodios normales.


## Estructura del Proyecto

 - data/
    - friends.csv # Dataset con la información de los episodios
    - friends.jpeg # Fotografía utilizada en la memoria

 - img/ # Gráficos generados por el análisis
    - grafico_h1.png
    - grafico_h2.png
    - grafico_h3.png
    - grafico_h4.png
    - grafico_h5.png

 - pruebas.ipynb # Notebook de pruebas para el análisis
 - Memoria.ipynb # Informe del análisis
 - main.py # Script principal con el código del análisis
 - README.md # Este archivo


## Tecnologías Utilizadas

- **Python 3.12+**
- **Pandas** → Limpieza y manipulación de datos    
- **Matplotlib** y **Seaborn** → Visualización de datos  

Instalación de dependencias:
    pip install pandas; numpy; matplotlib; seaborn


## Hipótesis Evaluadas

Código	Hipótesis:
    H1	Los episodios más largos tienen mayor número de votos.
    H2	Los episodios finales de cada temporada tienen un rating más alto que los primeros.
    H3	Las temporadas con mayor rating están en la mitad de la serie.
    H4	Los directores con más episodios tienden a tener más votos totales.
    H5	Los episodios especiales obtienen un rating diferente al de los episodios normales.

Visualizaciones Incluidas

 - H1: Mediana de votos totales por duración de episodio

 - H2: Rating del primer y último episodio de cada temporada

 - H3: Rating total por temporada

 - H4: Directores con episodios más votados

 - H5: Rating de episodios especiales (Sí/No)


## Resultados y Conclusiones

Los gráficos obtenidos permiten observar patrones claros en la serie Friends:

No existe relación directa entre la duración de los episodios y los votos.

Los episodios finales suelen tener un rating ligeramente superior.

Las temporadas centrales concentran las mejores valoraciones.

Algunos directores destacan por el alto promedio de votos en sus episodios.

Los episodios especiales no presentan diferencias notables en la valoración promedio.


## Autor

Rebeca Pérez
Proyecto académico de análisis de datos (EDA).
Año: 2025


## Licencia

Este proyecto se distribuye bajo la licencia MIT.
Puedes usarlo y modificarlo libremente, citando la fuente original.