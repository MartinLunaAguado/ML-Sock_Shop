
# Análisis de Anomalías en Microservicios 


Este repositorio contiene dos notebooks desarrollados para practicar el uso de ML, enfocados en la detección y análisis de anomalías en sistemas de microservicios utilizando diversos enfoques, demostrando la eficacia de BARO en particular.

## Contenido

### 1. work1_f.ipynb

Descripción: Análisis centrado exclusivamente en el microservicio SockShop (servicio carts) con diferentes tipos de fallo: CPU hog, memory leak, packet loss y packet delay.

Objetivo: Clasificación de clases anómalas y limpieza de datos para posteriores etapas de detección de anomalías.

### 2. work2.ipynb

Descripción: Extensión del análisis anterior incluyendo múltiples servicios (carts, catalogue, orders, payment, user) y distintos tipos de fallos.

Objetivo: Unificación y etiquetado automático de clases anómalas en un entorno más amplio, representativo del sistema completo.

Librerías utilizadas
pandas, numpy, matplotlib

scikit-learn

baro: para detección de anomalías y análisis de causa raíz

## Cómo usar
Asegúrate de tener instaladas las dependencias.

Ejecuta work1_f.ipynb o work2.ipynb según el alcance del análisis.

Los datos deben estar organizados por carpetas siguiendo la estructura esperada (carts_cpu/1/new_data.csv, etc.).