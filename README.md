# 🏦 Bank-Loan-Report: Análisis Estratégico de Cartera de Préstamos

## El Arsenal del Detective de Datos 🛠️

Este proyecto demuestra un dominio completo del ciclo de vida del análisis de datos, utilizando las siguientes herramientas:

Aplicación en el Proyecto
  * SQL(SSMS): Extracción, transformación y cálculo de métricas complejas (KPIs). Se utilizó para calcular **MTD (Month-to-Date)** y **MoM (Month-over-Month)**, y para la clasificación de rendimiento.

  * Power BI: Utilizado para la visualización de la narrativa de los datos.

  * Análisis de Negocio: Definición de las métricas clave, incluyendo la clasificación de préstamos como "Good Loan" (Pagado/Actual) y "Bad Loan" (Castigado/Charged Off).

## 📊 Estructura del Reporte (Los Paneles de Control)

El Tablero de Mando en Power BI está dividido en tres pestañas principales para servir a diferentes audiencias y propósitos:

1.  Summary: Enfocado en los KPIs de alto nivel y la clasificación de riesgo. Muestra el rendimiento general, el porcentaje de Good Loan / Bad Loan, y el total de fondos.
2.  Overview: Análisis detallado de la segmentación de la cartera por dimensiones clave:
    * Tendencias por Mes
    * Distribución Geográfica (Estado)
    * Propósito del Préstamo (Debt Consolidation, Credit Card, etc.)
    * Antigüedad Laboral
3.  Details: Permite el drill-down a nivel de transacción individual para la auditoría y la gestión detallada de la cartera.

## 💡 Insights Estratégicos)

* Identificación de Riesgo: El análisis de la cartera reveló que los préstamos para 'small business' tenían una tasa de 'Charged Off' X% más alta que el promedio.
* Recomendación Accionable: La recomendación fue evaluar una tasa de interés más alta o criterios de aprobación más estrictos para este segmento de propósito/término.
* Rendimiento en el Tiempo: Se observó una tendencia de crecimiento constante en el volumen de aplicaciones, pero un deterioro en el DTI promedio, sugiriendo un mayor riesgo en las nuevas emisiones.
