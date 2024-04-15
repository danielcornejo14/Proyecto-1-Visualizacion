# Proyecto-1-Visualizacion

Presetancion de preanalisisd de los casos de covid-19 en costa rica

## dependencies

- readxl
- ggplot2
- plotly

## Compilacion

1. correr `jupyter nbconvert -- to html --no-input covid_cases.ipynb` para generar el html
2. agregar `<script src="https://cdn.plot.ly/plotly-2.30.0.min.js" charset="utf-8"></script>` en el head del html generado
3. abrir el html generado en un navegador