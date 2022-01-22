
# Sell2Sam
Algoritmo basado en redes profundas para la clasificacion de texto a NAICS codes 2022 utilizando transformers.
Los datos fueron recolectados por el equipo de GovContracts.

## Uso

Para usar el modelo desde el archivo .h5 es necesario correr el archivo Transformer.ipynb.

Por otro lado puedes usar el API de Hugging face hub.

## Modelo
<b>

<p align="center">
  <img src="sell2sam\Transformer.png" title = "Modelo">
</p>

## Workflow

<p align="center">
  <img src="sell2sam\Workflow.png" title = "Workflow">
</p>

## Ejemplos de predicciones

```
Keyword: Construction
```

Prediccion con top 5 con sell2sam

<p align="center">
  <img src="sell2sam\ejemplo_resultado.png" title = "Reusltados de keyword construction modelo">
</p>

Usando https://www.naics.com/code-search/

<p align="center">
  <img src="sell2sam\naics.png" title = "Reusltados de keyword construction naics.com">
</p>


## Desarrollador
* Jesus Alan Hernandez Galvan