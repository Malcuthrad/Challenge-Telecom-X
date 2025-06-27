# Challenge-Telecom-X
Challenge de Analisis de datos con Python Alura LATAM


# 📊 Informe de Análisis de Evasión de Clientes (Churn)

Este repositorio contiene un análisis completo sobre la evasón de clientes realizado en Google Colab utilizando Python. El proyecto incluye la carga, limpieza y normalización de datos, análisis exploratorio, visualización y la generación de un informe final con los hallazgos más relevantes.

## 📃 Resumen del Proyecto

El objetivo principal de este trabajo es entender los patrones de cancelación de clientes (churn) y detectar los factores clave que influyen en su retención o abandono. Los resultados se presentan en un informe profesional listo para ser compartido con clientes o stakeholders.

## 🔍 Flujo de Trabajo

1. **Carga y Preparación de Datos**

   - La base de datos fue cargada en Google Colab utilizando la librería pandas.

   - Se revisaron todas las columnas para detectar datos nulos.

   - Las filas con datos faltantes fueron eliminadas al no aportar valor significativo al análisis global.

   - Los valores binarios (1 y 0) fueron reemplazados por Yes y No para mayor interpretabilidad.

2. **Análisis Exploratorio de Datos (EDA)**

   - Se exploraron las variables relevantes en relación con la variable objetivo Churn.

   - Se generaron gráficos utilizando Plotly para analizar:

      - Tipo de contrato

      - Método de pago

      - Tipo de servicio de internet

      - Antigüedad del cliente (Tenure)

      - Facturación electrónica

      - Variables demográficas: edad, género, pareja, dependientes

3. **Informe Final**

  - Se elaboró un informe detallado con gráficos integrados.

   - El informe está disponible en formato .docx y redactado en español.

## 📂 Archivos Incluidos

- Informe Evasion Clientes TelecomX - FINAL.docx — Informe final de análisis con visualizaciones

- TelecomX_LATAM.ipynb — Notebook de Google Colab con el desarrollo del análisis (por agregar)

- /images — Carpeta con las gráficas utilizadas (por agregar)

## 📊 Librerías y Herramientas

   - Google Colab

   - Python 3.x

   - pandas

   - plotly.express

   - matplotlib (opcional)


## 📌 Principales Conclusiones

- Los clientes con contratos mes a mes, cheque electrónico y facturación sin papel presentan mayores tasas de cancelación.

- Clientes con pareja, dependientes o alta permanencia tienen menor propensión a cancelar.

- Los primeros meses de relación con el cliente son los más críticos para la retención.

## 🚀 Próximos Pasos

- Desarrollar un modelo predictivo de churn mediante técnicas de machine learning.

- Aplicar estrategias de retención personalizadas para cada perfil de riesgo.

## 📩 Contacto

   - Antonio Pérez
   - Email: antonioandresperezs@gmail.com
   - LinkedIn: https://www.linkedin.com/in/antonio-perez-sandoval
   - GitHub: https://github.com/Malcuthrad

Licencia: Este proyecto es de código abierto bajo la licencia MIT.

