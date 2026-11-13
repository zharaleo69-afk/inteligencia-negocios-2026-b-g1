# VetHuella Huila — Avance 3

**Asignatura:** Inteligencia de Negocios 2026-B  
**Periodo analizado:** 2025  
**Datos:** sintéticos

## Introducción

VetHuella Huila analiza la inasistencia a citas veterinarias durante 2025 mediante inteligencia de negocios. El conjunto de datos es sintético y sus resultados corresponden a un ejercicio académico, no a estadísticas oficiales de una clínica.

## Objetivo

Interpretar indicadores de atención e inasistencia para identificar patrones descriptivos y proponer acciones de mejora en la gestión de citas.

## Metodología

Avance 0: definición del problema, objetivos e indicadores. Avance 1: integración y depuración de datos en Power Query; de 1.512 registros se eliminaron 12 duplicados y se conservaron 1.500. Avance 2: modelo estrella con Fact_Citas, Dim_Servicio, Dim_Paciente, Dim_Canal y Dim_Fecha; medidas DAX y dashboard interactivo. Avance 3: interpretación de resultados y recomendaciones.

## Indicadores principales

Total de citas: 1.500. Atendidas: 1.017. No asistidas: 189. Canceladas anticipadamente: 172. Reprogramadas: 122. Comprobación de totales: 1.017 + 189 + 172 + 122 = 1.500. La tasa de inasistencia es 189 / (1.017 + 189) × 100 = 15,67 %. El denominador excluye cancelaciones anticipadas y reprogramaciones.

## Hallazgos

Consulta general presenta 77 inasistencias; vacunación, 45; control preventivo, 30; desparasitación, 22; y seguimiento clínico, 15. La suma es 189. Consulta general representa 40,74 % de las inasistencias, pero esta concentración absoluta no demuestra una mayor tasa de riesgo sin comparar con el número de citas elegibles por servicio. El dashboard también permite segmentar por canal, especie y AñoMes.

## Interpretación para el negocio

Aproximadamente 16 de cada 100 citas elegibles terminaron en inasistencia. La organización puede priorizar el seguimiento de las citas, evaluar el uso de recordatorios y analizar diferencias entre segmentos. Los resultados son descriptivos y no prueban causalidad.

## Recomendaciones

1. Evaluar recordatorios previos por WhatsApp o llamada. 2. Facilitar confirmación, cancelación y reprogramación anticipadas. 3. Revisar indicadores mensualmente. 4. Comparar las tasas por servicio y canal, considerando denominadores equivalentes. 5. Medir el efecto de cualquier intervención antes de concluir que funciona.

## Limitaciones

Los datos son sintéticos. No se dispone de evidencia de implementación de las recomendaciones ni de un experimento que mida sus efectos. Las cifras por canal, especie o mes deben leerse directamente en Power BI antes de afirmar hallazgos específicos. Las capturas del dashboard final deben añadirse a la carpeta de evidencias.

## Conclusiones

El proceso de limpieza, modelado dimensional y visualización permitió transformar registros de citas en indicadores útiles. La tasa de inasistencia de 15,67 % ofrece una línea base; consulta general concentra 77 de las 189 ausencias. El valor del proyecto reside en apoyar decisiones basadas en datos, sujetas a validación y seguimiento.
