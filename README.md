# Proyecto Taxímetro

Este proyecto implementa un taxímetro en Python que calcula tarifas basadas en el tiempo detenido y el tiempo en movimiento.

## Estructura del proyecto

- `.gitignore`: Archivo que especifica qué archivos o carpetas deben ser ignorados por Git. Actualmente ignora el entorno virtual `.venv`.
- `taximetro.py`: Script principal que contiene la lógica del taxímetro.

## Funcionalidades

### `calculate_fare(seconds_stopped, seconds_moving)`
Esta función calcula la tarifa total en euros basada en el tiempo detenido y el tiempo en movimiento:
- **Tiempo detenido**: 0.02 €/segundo.
- **Tiempo en movimiento**: 0.05 €/segundo.

Ejemplo:
```py
fare = calculate_fare(120, 300)  # Calcula la tarifa para 120 segundos detenido y 300 segundos en movimiento.
print(fare)  # Muestra el total calculado.
```

`taximeter()`

Función principal que maneja y muestra las opciones del taxímetro. Se ejecuta automáticamente al iniciar el script.

