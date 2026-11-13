# Guion de Sustentación — VetHuella Huila

## Avance 3 — Inteligencia de Negocios 2026-B

### 1. Presentación del proyecto

Buenos días.

El proyecto que presentamos se llama VetHuella Huila y tiene como objetivo analizar la inasistencia a citas veterinarias mediante herramientas de inteligencia de negocios.

La finalidad es identificar patrones en los registros de atención y formular recomendaciones que puedan contribuir a mejorar la gestión de las citas.

### 2. Problema identificado

Una de las dificultades que pueden presentarse en los servicios veterinarios es que los propietarios programen citas y posteriormente no asistan.

Esta situación puede afectar la organización de la agenda y el aprovechamiento de los espacios disponibles.

Por esta razón, planteamos analizar los datos de citas veterinarias correspondientes al año 2025.

### 3. Preparación de los datos

En la primera fase trabajamos con un conjunto de datos sintéticos que contenía 1.512 registros.

Utilizamos Power Query para realizar el proceso de extracción, transformación y limpieza.

Durante este procedimiento identificamos y eliminamos 12 registros duplicados.

Como resultado, obtuvimos una base limpia de 1.500 citas.

Este proceso fue importante porque los indicadores deben calcularse sobre información consistente.

### 4. Construcción del modelo estrella

Después de limpiar los datos, desarrollamos un modelo dimensional en Power BI.

La tabla principal es `Fact_Citas`, que contiene los registros de las citas.

También construimos cuatro dimensiones:

- `Dim_Servicio`.
- `Dim_Paciente`.
- `Dim_Canal`.
- `Dim_Fecha`.

Estas dimensiones permiten analizar las citas desde diferentes perspectivas y facilitan el funcionamiento de los filtros.

### 5. Construcción de indicadores DAX

Utilizamos medidas DAX para calcular los principales indicadores.

Por ejemplo, el total de citas se obtiene mediante `COUNTROWS(Fact_Citas)`.

Para las citas no asistidas utilizamos una medida que filtra los registros correspondientes al estado de inasistencia.

La tasa de inasistencia se calcula dividiendo las citas no asistidas entre la suma de las citas atendidas y las no asistidas.

El resultado fue del 15,67 %.

### 6. Resultados del dashboard

El dashboard presenta 1.500 citas analizadas.

De estas, 1.017 fueron atendidas, 189 registraron inasistencia, 172 fueron canceladas anticipadamente y 122 fueron reprogramadas.

La tasa de inasistencia fue del 15,67 %, considerando como elegibles las citas atendidas y no asistidas.

### 7. Análisis por servicio

Al analizar las inasistencias por servicio encontramos que consulta general registró 77 ausencias.

Le siguen vacunación con 45, control preventivo con 30, desparasitación con 22 y seguimiento clínico con 15.

Esto nos permite identificar dónde se concentra el mayor número de inasistencias.

Sin embargo, para determinar cuál servicio tiene mayor riesgo de inasistencia, también debemos comparar las ausencias con el volumen de citas elegibles de cada servicio.

### 8. Importancia del dashboard interactivo

El dashboard permite aplicar filtros por servicio, canal, especie y periodo.

Esto significa que no estamos limitados a observar únicamente el resultado general.

Podemos explorar diferentes segmentos y analizar cómo cambian los indicadores.

### 9. Recomendaciones

A partir de los resultados proponemos implementar recordatorios anticipados, facilitar la confirmación de citas y monitorear periódicamente la tasa de inasistencia.

También recomendamos utilizar el dashboard como herramienta de seguimiento para evaluar posibles mejoras.

Estas son propuestas de negocio y no acciones que ya se hayan implementado.

### 10. Conclusión

Como conclusión, el proyecto permitió integrar las principales etapas de inteligencia de negocios.

Partimos de una problemática, preparamos los datos, construimos un modelo estrella, desarrollamos indicadores DAX y presentamos los resultados mediante un dashboard interactivo.

El hallazgo principal fue una tasa de inasistencia del 15,67 %.

Con esta información formulamos recomendaciones para mejorar la gestión de citas veterinarias.

Muchas gracias.
