# 🍷 Análisis Profundo de la Producción Vitivinícola: Descubriendo los Secretos de la Calidad y la Rentabilidad 🚀

Este proyecto se sumerge en el fascinante mundo de la producción de vino, utilizando un conjunto de datos simulados para desentrañar los factores que definen la excelencia y la viabilidad económica de cada lote. Desde la cepa hasta la copa, seguimos el viaje del vino a través de un análisis de datos exhaustivo y la aplicación de técnicas de modelado predictivo.

## Marco del Proyecto y Contexto Académico 📝

Este trabajo representa el proyecto final desarrollado como parte del curso de **Data Science en Coderhouse**. El desarrollo se estructuró en dos etapas principales:

1.  **Pre-entrega:** Enfocada en la comprensión inicial de los datos, la limpieza, el análisis exploratorio (EDA) y la formulación de hipótesis preliminares. Esta fase sentó las bases para un análisis más profundo.
2.  **Entrega Final:** Culminó con la ingeniería de características adicionales, la validación de hipótesis, el desarrollo y evaluación de modelos de machine learning para predicción, y la consolidación de conclusiones y recomendaciones.

## ¿De qué va el Proyecto? 🍇➡️📊

Imagina poder anticipar la calidad de un vino antes incluso de que termine su crianza, o entender exactamente qué decisiones de producción tienen el mayor impacto en el puntaje final y en el precio de mercado. Este proyecto aborda precisamente eso:

*   **Exploramos** un dataset detallado con más de 2000 lotes de vino, cubriendo variables desde la cosecha, tipo de uva, región, y clima, hasta los intrincados detalles del proceso de fermentación, tipo de barrica, tiempos de crianza, costos y características físico-químicas.
*   **Buscamos** identificar los *drivers* clave que influyen en el `Puntaje_Calidad` y, por ende, en la `Categoria_Calidad` de los vinos (Standard, Premium, Super Premium).
*   **Analizamos** cómo estas decisiones impactan la estructura de costos y el `Precio_Mercado_x_Botella`, buscando el equilibrio perfecto para la rentabilidad.

## El Viaje Analítico: Pasos Clave 🗺️

Nuestro recorrido a través de los datos siguió una metodología estructurada y un diseño cuidadoso para extraer insights valiosos:

1.  **Inspección Inicial Detallada:** Un primer vistazo para entender la forma, tipos de datos, y estadísticas básicas de nuestro universo de vinos.
2.  **Limpieza de Datos:** ¡Fundamental! Preparamos los datos para el análisis, manejando valores nulos de forma estratégica para no perder información valiosa (imputación con medianas, creación de categorías 'Desconocido').
3.  **Análisis Exploratorio de Datos (EDA) Profundo:**
    *   Visualizamos distribuciones de variables clave (calidad, alcohol, costos, tiempos de crianza).
    *   Descubrimos relaciones ocultas entre la calidad y factores como el tiempo en barrica o la temperatura de fermentación mediante gráficos reveladores (scatter plots, box plots).
    *   Analizamos costos, precios y volúmenes de producción.
    *   Construimos una matriz de correlación para entender las interdependencias numéricas.
4.  **Ingeniería de Características (Feature Engineering):** ¡No nos quedamos en la superficie! Creamos nuevas métricas como `Margen_Bruto_x_Botella` y `Duracion_Proceso_Total_Dias` para enriquecer el análisis y obtener perspectivas únicas. Incluso categorizamos bodegas por su rendimiento promedio.
5.  **Validación de Hipótesis:** Formulamos preguntas de negocio (ej: "¿El tiempo en barrica realmente mejora la calidad?") y usamos el EDA para encontrar respuestas basadas en evidencia.
6.  **Modelado Predictivo con Machine Learning:**
    *   Nos aventuramos a predecir la `Categoria_Calidad` de un vino.
    *   Preparamos los datos (codificación, escalado) y probamos varios algoritmos de clasificación supervisada (Regresión Logística, Random Forest).
    *   Evaluamos rigurosamente nuestros modelos para entender su precisión y qué características consideran más importantes. **¿Logramos predecir la excelencia? ¡Los resultados te sorprenderán!**

## Diseño y Storytelling 🎨📜

Más allá de los números, nos enfocamos en contar una historia con los datos. La presentación de los hallazgos se diseñó para ser:

*   **Visual e Intuitiva:** Priorizando gráficos claros y mensajes concisos.
*   **Orientada a Insights Accionables:** Transformando datos en recomendaciones prácticas.
*   **Narrativa:** Guiando al lector (o espectador) a través del proceso de descubrimiento, desde el dato crudo hasta la conclusión estratégica.

## ¿Quieres Saber Más? 🤔

Este proyecto no solo revela patrones en la producción de vino, sino que también sienta las bases para tomar decisiones más inteligentes y basadas en datos en la industria vitivinícola.

➡️ **¡Explora el notebook para descubrir los resultados detallados, las visualizaciones clave y las conclusiones de nuestro modelo predictivo!** ¿Qué factores resultaron ser los verdaderos game-changers? ¿Cuán preciso puede ser un modelo al catar digitalmente un vino?

## 📊 Presentación de Resultados

Para una visión general de nuestro viaje analítico, los hallazgos clave y las conclusiones del proyecto, puedes consultar nuestra presentación:

➡️ **[Ver la Presentación en PDF (Análisis de Vino)](Descubriendo-los-Secretos-de-un-Vino-Excepcional.pdf)**

---
