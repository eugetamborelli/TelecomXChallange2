# 📡 Predicción de Cancelación de Clientes - Análisis y Modelado

## 📖 Introducción
Este proyecto tiene como objetivo analizar y predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones.  
El estudio se basa en un dataset con información demográfica, servicios contratados y datos de facturación.  
A partir de esta información, se aplican modelos de machine learning para identificar los factores más relevantes y proponer estrategias de retención.

## 🎯 Objetivo del Proyecto
- Explorar y procesar los datos para detectar patrones relacionados con la cancelación.
- Aplicar distintos modelos predictivos (Regresión Logística y Random Forest).
- Evaluar el rendimiento de cada modelo mediante métricas como **precisión, recall, F1-score y matriz de confusión**.
- Analizar la importancia de las variables y extraer conclusiones prácticas para la retención de clientes.

## 🖥️ Manual de Usuario
Sigue estos pasos para ejecutar el notebook correctamente:

1. **Clonar o descargar** este repositorio:
   ```bash
   git clone https://github.com/usuario/repositorio.git
Abrir el notebook en Google Colab o Jupyter Notebook.

Subir el dataset limpio (clientes_limpio.csv) en la carpeta raíz o en el entorno de Colab.

Ejecutar las celdas en orden, desde la carga de librerías hasta el análisis final.

Notas importantes:

Si se interrumpe la ejecución, es necesario volver a subir el dataset y ejecutar desde el inicio.

Algunos modelos requieren normalización; el notebook explica cuándo se aplica.

El balanceo de clases con SMOTE es opcional, pero recomendado si se quiere mejorar el recall.

📊 Conclusión Final
🔍 Factores Clave que Influyen en la Cancelación
Cobro Mensual alto → mayor probabilidad de cancelación.

Servicio de Internet (Fiber optic) → más asociado a clientes que cancelan.

Meses de Contrato largos → menor probabilidad de cancelación.

Cobro Total → influencia relevante en combinación con la duración del contrato.

⚙️ Comparativa de Modelos
Regresión Logística: Mejor recall en la clase de cancelación (útil para detectar más clientes en riesgo).

Random Forest: Mejor precisión general, pero menor recall en cancelaciones.

Ambos coinciden en que el precio y el tiempo de contrato son determinantes.

💡 Estrategias Propuestas
Reducir el cobro mensual para clientes en riesgo.

Incentivar el paso de contratos mensuales a anuales o bianuales.

Mejorar la calidad percibida del servicio Fiber optic.

Monitorear clientes con cobro alto y baja antigüedad.

📌 Autora: [María Eugenia Tamborelli]
📅 Fecha: Agosto 2025
