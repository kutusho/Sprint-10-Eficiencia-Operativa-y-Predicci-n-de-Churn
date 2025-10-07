# Sprint 10 – Análisis de Eficiencia y Predicción de Churn

## 📄 Descripción
Proyecto correspondiente al **Sprint 10 del Bootcamp de Data Analytics – TripleTen**, enfocado en el análisis de eficiencia de servicios y predicción de churn (pérdida de clientes).  
El objetivo fue identificar los factores que determinan la deserción de usuarios y evaluar la eficiencia operativa de una empresa de telecomunicaciones, utilizando análisis estadístico, cohortes y visualizaciones.

---

## 🎯 Objetivo
Determinar qué factores influyen en la cancelación de clientes y cómo optimizar la eficiencia de los operadores y el servicio al cliente, con el fin de **reducir el churn** y **mejorar la retención**.

---

## 🧩 Contexto del caso
Una empresa de telecomunicaciones observa una **tasa creciente de cancelaciones**.  
Se analizaron datos de contratos, servicios, pagos y clientes para detectar patrones de comportamiento y correlaciones que expliquen la pérdida de usuarios.

---

## 🧠 Metodología

1. **Exploración y limpieza de datos**
   - Eliminación de duplicados y valores nulos.  
   - Estandarización de tipos de datos (fechas, categorías).  
   - Creación de variables derivadas: duración del contrato, tipo de pago, servicio total.

2. **Análisis descriptivo**
   - Distribución de clientes por tipo de contrato y método de pago.  
   - Comparación de variables entre clientes activos y cancelados.  

3. **Cálculo de métricas**
   - **Churn Rate** = clientes cancelados / clientes totales.  
   - **Average Tenure (meses)** y **Monthly Charges promedio**.  
   - Segmentación por tipo de servicio (Internet, Teléfono, Streaming, etc.).  

4. **Visualización**
   - Histogramas, boxplots y gráficos de barras comparando clientes churned vs. activos.  
   - Correlaciones entre monto mensual, duración del contrato y probabilidad de churn.  

5. **Insights clave**
   - Identificación de variables críticas: `contract_type`, `tenure`, `monthly_charges`, `payment_method`.  
   - Creación de cohortes por antigüedad para analizar retención temporal.

---

## 📊 Resultados principales

- **Tasa de churn total:** 26.5 %  
- Los clientes con **contrato mensual** presentan **el doble de probabilidad** de cancelar que los de contrato anual.  
- Los usuarios con cargos mensuales mayores a **$80 USD** tienen una tasa de churn del 35 %.  
- **Pagos automáticos** y contratos prolongados reducen el churn significativamente.  
- Las cohortes más recientes muestran **mejor retención**, indicando mejoras en la atención al cliente.  

---

## 📈 Conclusiones
El análisis evidencia que los factores económicos y contractuales son determinantes en la retención.  
Reducir precios en segmentos sensibles y promover contratos anuales puede **disminuir el churn** en más del 10 %.  
El proyecto demuestra la importancia de los datos en la toma de decisiones operativas.

---

## 🧰 Herramientas y tecnologías
- **Lenguaje:** Python  
- **Librerías:** pandas · numpy · matplotlib · seaborn · scipy  
- **Análisis:** churn rate, cohortes, correlaciones, segmentación  
- **Visualización:** heatmaps, histogramas, comparativas de contratos  
- **Control de versiones:** Git · GitHub  

---

