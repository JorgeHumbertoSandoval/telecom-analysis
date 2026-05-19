# Telecom Analysis

## Objetivo
Analizar datos de clientes de ConnectaTel para identificar patrones de uso, segmentar usuarios y generar insights accionables para el negocio.

---

## Datasets utilizados

### users_latam.csv
Información de clientes:
- Edad
- Ciudad
- Fecha de registro
- Tipo de plan

### usage.csv
Registro de uso de servicios:
- Cantidad de llamadas
- Duración de llamadas
- Cantidad de mensajes

### plans.csv
Información de planes:
- Precio
- Minutos incluidos
- GB incluidos
- Costos extra

---

## Herramientas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Etapas del análisis

### 1. Limpieza y validación de datos
- Corrección de edades inválidas
- Tratamiento de fechas incorrectas
- Revisión de valores nulos
- Estandarización de datos categóricos

### 2. Análisis exploratorio
- Resúmenes estadísticos
- Distribución de variables
- Comparación entre planes

### 3. Visualización de datos
- Histogramas
- Boxplots
- Segmentación visual de clientes

### 4. Detección de outliers
- Método IQR
- Evaluación de valores extremos
- Decisiones de conservación o tratamiento

### 5. Segmentación de clientes
- Segmentación por edad
- Segmentación por nivel de uso
- Identificación de clientes potencialmente más valiosos

### 6. Insights de negocio
- Patrones de comportamiento
- Diferencias entre planes
- Recomendaciones comerciales

---

## Principales hallazgos
- El plan Básico concentra la mayoría de usuarios.
- Los usuarios adultos representan el segmento predominante.
- El segmento de uso medio es el más frecuente.
- Existen usuarios con consumo extremo en minutos de llamada.
- Se identificó una oportunidad para crear un plan intermedio.

---

## Cómo ejecutar el proyecto

### Opción 1: Google Colab
1. Descargar el notebook `.ipynb`
2. Abrir Google Colab
3. Subir el notebook
4. Ejecutar las celdas en orden

### Opción 2: Jupyter Notebook
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
