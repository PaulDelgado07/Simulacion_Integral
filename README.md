# Simulación DES: Infraestructura de API de Machine Learning

## Descripción
Adaptación de un modelo base de Simulación de Eventos Discretos (DES) para evaluar 
la latencia y la gestión de recursos de una API de Machine Learning en producción, 
utilizando Teoría de Colas y políticas de inventario de recursos computacionales.

## Objetivo
Adaptar un modelo base de simulación de eventos discretos (DES) para evaluar la 
latencia y la gestión de recursos de una API de Machine Learning en producción, 
utilizando Teoría de Colas y políticas de inventario de recursos computacionales.

## Parámetros Operativos
| Parámetro | Valor |
|---|---|
| Tasa de llegadas (λ) | 30 peticiones/minuto |
| Tasa de servicio (μ) | 10 imágenes/minuto |
| Servidores (c) | 4 Nodos GPU |
| Stock inicial | 500 créditos de nube |
| Punto de reorden (s) | 50 créditos |
| Cantidad de recarga (Q) | 400 créditos |
| Lead Time | Media de 2 minutos |
| Tiempo de simulación | 60 minutos |
| Réplicas | 30 |

## Tecnologías utilizadas
- Python 3
- SimPy
- NumPy
- Pandas
- Matplotlib
- SciPy

## Cómo ejecutar
1. Abrir el archivo `.ipynb` en Google Colab o Jupyter Notebook
2. Instalar dependencias si es necesario:
```bash
pip install simpy numpy pandas matplotlib scipy
```
3. Ejecutar todas las celdas en orden de arriba hacia abajo

## Autor
Paul Delgado — Universidad de Guayaquil  
Facultad de Ciencias Matemáticas y Físicas  
Modelamiento y Simulación — Paralelo 6-2
