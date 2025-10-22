# Proyecto-4-Bootcamp

•	Objetivo: Análisis de patrones de compra de clientes de la plataforma Instacart

•	Librerías usadas: pandas, numpy, matplotlib/seaborn, scipy.stats y/o statsmodels

•	Preprocesamiento:

  o	Filtrado por fechas/condiciones de negocio.

  o	Limpieza básica (duplicados, manejo de nulos con dropna/fillna).

  o	Creación de columnas derivadas: event_date, event_hour, flags binarias, agregados por usuario.

  o	Uso de .groupby() / pivot_table para agregados por usuario/evento/grupo.

•	Análisis exploratorio (EDA):

  o	Conteos totales de eventos y usuarios únicos; eventos promedio por usuario.

  o	Distribuciones temporales (por día/hora) y visualizaciones (barplots, histogramas, heatmaps).

  o	Identificación de eventos clave y construcción de embudo: usuarios únicos por etapa y tasas de conversión entre pasos.

•	Experimentación / tests:

  o	Agrupación por variante/exp_id y conteo de usuarios por grupo.

  o	Tests de proporciones (z-test / proportions_ztest) para comparar conversiones entre variantes; generación de p-values y decisión con alpha (usualmente 0.05).

  o	Tabla resumen con resultados de tests por evento/medida.

•	Output y conclusiones:

  o	Tablas y gráficos que sintetizan usuarios por evento, conversion rates por etapa y por grupo experimental.
