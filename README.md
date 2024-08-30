# ✈️ Proyecto de Predicción de Satisfacción del Cliente de Aerolíneas

## 🎯 Objetivo del Proyecto

El objetivo de este proyecto es desarrollar un modelo de machine learning para predecir la satisfacción de los clientes de una aerolínea en función de varios factores como el servicio a bordo, el confort del asiento, y los retrasos en los vuelos, etc..

Utilizando datos históricos proporcionados por F5 Airlines, entrenaremos un modelo supervisado de clasificación para identificar qué factores son más importantes para la satisfacción del cliente y crearemos una aplicación que permita predecir la satisfacción para nuevos clientes.

## 📊 Diccionario de Datos

| **Columna**                             | **Tipo de Datos** | **Descripción**                                                                 |
|-----------------------------------------|-------------------|---------------------------------------------------------------------------------|
| Unnamed: 0                              | int64             | Índice de fila que parece no tener un uso particular (puede eliminarse).          |
| id                                      | int64             | Identificador único para cada pasajero.                                           |
| Gender                                  | object            | Género del pasajero (Masculino o Femenino).                                       |
| Customer Type                           | object            | Tipo de cliente: "Loyal Customer" o "disloyal Customer".                          |
| Age                                     | int64             | Edad del pasajero.                                                                |
| Type of Travel                          | object            | Tipo de viaje: "Personal Travel" o "Business travel".                             |
| Class                                   | object            | Clase del asiento del pasajero: "Eco", "Eco Plus", o "Business".                  |
| Flight Distance                         | int64             | Distancia del vuelo en millas.                                                   |
| Inflight wifi service                   | int64             | Nivel de satisfacción con el servicio de wifi a bordo (escala de 1 a 5).           |
| Departure/Arrival time convenient       | int64             | Conveniencia del tiempo de salida/llegada (escala de 1 a 5).                      |
| Ease of Online booking                  | int64             | Facilidad para hacer reservas en línea (escala de 1 a 5).                         |
| Gate location                           | int64             | Satisfacción con la ubicación de la puerta de embarque (escala de 1 a 5).         |
| Food and drink                          | int64             | Satisfacción con la comida y bebida (escala de 1 a 5).                            |
| Online boarding                         | int64             | Satisfacción con el proceso de embarque en línea (escala de 1 a 5).               |
| Seat comfort                            | int64             | Satisfacción con la comodidad del asiento (escala de 1 a 5).                      |
| Inflight entertainment                  | int64             | Satisfacción con el entretenimiento a bordo (escala de 1 a 5).                    |
| On-board service                        | int64             | Satisfacción con el servicio a bordo (escala de 1 a 5).                           |
| Leg room service                        | int64             | Satisfacción con el espacio para las piernas (escala de 1 a 5).                   |
| Baggage handling                        | int64             | Satisfacción con la manipulación del equipaje (escala de 1 a 5).                  |
| Checkin service                         | int64             | Satisfacción con el servicio de check-in (escala de 1 a 5).                       |
| Inflight service                        | int64             | Satisfacción con el servicio en vuelo (escala de 1 a 5).                          |
| Cleanliness                             | int64             | Satisfacción con la limpieza (escala de 1 a 5).                                   |
| Departure Delay in Minutes              | int64             | Minutos de retraso en la salida.                                                 |
| Arrival Delay in Minutes                | float64           | Minutos de retraso en la llegada (tiene algunos valores faltantes).               |
| satisfaction                            | object            | Satisfacción del cliente: "satisfied" o "neutral or dissatisfied".                 |

## 🚀 Instrucciones para la Ejecución

- A definir

## 📁 Estructura del Proyecto

```
├── data
│   └── airline_passenger_satisfaction.csv
├── models
│   ├── arboles_decision.ipynb
│   ├── gradient_boosting.ipynb
│   ├── random_forest.ipynb
│   ├── regresion_lineal_multiple.ipynb
│   ├── regresion_lineal_simple.ipynb
│   ├── regresion_logistica.ipynb
├── notebooks
│   ├── analisis_datos.ipynb
│   └── tratamiento_datos.ipynb
├── README.md
```

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- Scikit-learn
- Streamlit
- Matplotlib/Seaborn

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🙏 Agradecimientos

Agradecemos a todos los miembros del equipo y a nuestros instructores por su apoyo y orientación en el desarrollo de este proyecto.

## ⚠️ Reminder para Aitor

Reflejar el nivel de los objetivos que se propone alcanzar el equipo de alumnos con el desarrollo del proyecto, y motivarlo en base a las circunstancias personales de sus miembros.

Presentar a los miembros del equipo así como los roles que han desempeñado en el desarrollo.
