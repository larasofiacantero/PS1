# PS1

Documentos y resolución del Problem Set 1 del curso de Machine Learning (ME-UNLP).

## Índice

- [Descripción del proyecto](#descripción-del-proyecto)
- [Prerrequisitos](#prerrequisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del proyecto](#estructura-del-proyecto)

---

## Descripción del proyecto

Este proyecto tiene como objetivo desarrollar un modelo predictivo para estimar los salarios horarios de los individuos en función de variables como la educación, sexo, género y la cantidad de horas trabajadas.  
Los datos utilizados provienen de la **Gran Encuesta Integrada de Hogares (GEIH) de 2018**, obtenidos a través de técnicas de web scraping, y se filtraron para incluir únicamente:

- Observaciones con ingresos mayores a cero.
- Personas empleadas mayores de 18 años.

---

## Prerrequisitos

Antes de comenzar, asegurate de tener lo siguiente:

- **Python** 3.10 o superior.
- Bibliotecas necesarias (podes instalarlas con el archivo `requirements.txt` en stores):
  - `requests`
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `numpy`
  - `scikit-learn`
  - `math`
  - `nbformat`
  - `joblib`

---

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/PS1.git

2. Dirigite al directorio del proyecto:
   ```bash
   cd PS1

3. Instala las dependencias desde el archivo requirements.txt disponible en scripts
  ```bash 
  pip install -r requirements.txt

---


## Uso

1. Scripts:
Contiene los archivos de Python con los códigos necesarios para desarrollar el trabajo.

2. Documents:
Archivos PDF que contienen las conclusiones y las respuestas a las preguntas planteadas en el trabajo.

3. Views:
Figuras generadas durante el análisis descriptivo, incluidas las figuras utilizadas en los documentos.

4. Stores:
Contiene los datos procesados de la GEIH en formato .csv, obtenidos mediante web scraping.

---

## Estructura del proyecto
En resumen, el repositorio se distribuye así:
PS1/
├── documents/        # Archivos PDF con resultados y conclusiones
├── scripts/          # Código fuente del proyecto
├── stores/           # Datos en formato .csv
├── views/            # Figuras generadas
├── requirements.txt  # Lista de dependencias
└── README.md         # Este archivo

