# Analítica Diagnóstica 🎓👨‍💻
## _Brecha de género en los ingresos del mercado salarial de Chile_

[![My Skills](https://skillicons.dev/icons?i=py,github)](https://skillicons.dev)

## Descripción
Este proyecto tiene como objetivo desarrollar un análisis diagnóstico basado en los datos provenientes de la Unidad 1 [Analítica descriptiva - Web Scraping][df5], el repositorio cuenta con un notebook de Python que utiliza librerias como _'Pandas'_, _'Matplotlib'_ , _'Seaborn'_ y _'Scipy'_ para realizar calculos estadisticos descriptivos, mientras que para los calculos estadisticos inferenciales se escogieron dos pruebas:
- **Mann-Whitney U**: El objetivo principal de la prueba es determinar si hay diferencias significativas entre las distribuciones de dos grupos, que en nuestro caso sería en los salarios de los hombres y mujeres tanto a nivel nacional y en detalle a nivel regional
- **Test t**: El objetivo principal del test t es evaluar si las diferencias observadas entre las medias de dos grupos son lo suficientemente grandes como para no ser atribuidas al azar.

## Contenido

- **Analítica_Diagnostica.ipynb** : Este notebook se centra en la visualización de datos utilizando gráficos y en los resultados de los test mencionados anteriormente.
- **Ingres.xlsl** : Archivo con nuevos datos para la ayuda de las hipótesis y extraer nuevos datos estadisticos.


## Tecnologías utilizadas

- Jupyter Notebook
- Google Colab
- Spicy
- Seaborn

```sh
!pip install spicy
!pip install seaborn 
```
## Ejecución en Google Colab

Para facilitar la ejecución del análisis, se recomienda utilizar [Google Colab](https://colab.research.google.com/). Colab permite ejecutar código Python en la nube sin necesidad de configuraciones locales, lo que es ideal para trabajar con datos y bibliotecas.

### Instrucciones

1. Abre Google Colab en tu navegador.
2. Crea un nuevo notebook.
3. Copia y pega el código del análisis desde este repositorio en las celdas del notebook.
4. Asegúrate de cargar los archivos CSV necesarios en el entorno de Colab. Puedes hacerlo utilizando la función de carga de archivos o montando tu Google Drive.
5. Ejecuta las celdas para realizar el análisis y visualizar los resultados.

### Ejemplo de Carga de Datos

Puedes usar el siguiente código para cargar los archivos CSV desde tu Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```
>Si no está familiarizado con colab aquí está el link directo al proyecto 
>donde solo tiene que dar click a 'Ejecutar todas las celdas'
>[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tUTq2pOXEGMt89YqudiZsLYtAcxv1kgc?usp=sharing)

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

# Agradecimientos🌷
Queremos agradecer a los siguientes autores por el arduo trabajo en este proyecto:

- **Ignacia Quezada** - [VicQA96][df6]
- **Thiare Águila** - [ThiareAguila][df7]

**2024-S2 ANALÍTICA INFB6100📘!**

   [df5]: <https://github.com/VicQA96/web-scraping>
   [df6]: <https://github.com/VicQA96>
   [df7]: <https://github.com/ThiareAguila>
