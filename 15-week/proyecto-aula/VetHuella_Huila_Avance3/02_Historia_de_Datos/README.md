# Historia de Datos — VetHuella Huila

## ¿Qué nos dicen las citas veterinarias de 2025?

### 1. Contexto del problema

La programación de citas es fundamental para la prestación de servicios veterinarios. Sin embargo, cuando los pacientes no asisten a las citas programadas, se pueden presentar dificultades en la organización de la agenda y el aprovechamiento de los espacios de atención.

VetHuella Huila busca comprender este comportamiento utilizando herramientas de inteligencia de negocios.

Para ello, se analizaron 1.500 registros de citas veterinarias correspondientes al año 2025.

### 2. Primera pregunta: ¿qué ocurrió con las citas?

Los registros presentan la siguiente distribución:

| Estado | Cantidad | Porcentaje del total |
|---|---:|---:|
| Atendida | 1.017 | 67,80 % |
| No asistió | 189 | 12,60 % |
| Cancelada con anticipación | 172 | 11,47 % |
| Reprogramada | 122 | 8,13 % |
| **Total** | **1.500** | **100 %** |

La mayoría de las citas fueron atendidas, pero también se identificaron 189 inasistencias.

### 3. Segunda pregunta: ¿cuál es la tasa de inasistencia?

Para este proyecto se definió la tasa de inasistencia sobre las citas atendidas y no asistidas.

**Fórmula:**

Tasa de inasistencia = Citas no asistidas / (Citas atendidas + Citas no asistidas) × 100

**Cálculo:**

189 / (1.017 + 189) × 100 = **15,67 %**

Esto significa que aproximadamente 16 de cada 100 citas elegibles terminaron en inasistencia.

Las citas canceladas anticipadamente y las reprogramadas no se incluyen en el denominador de este indicador.

### 4. Tercera pregunta: ¿qué servicios concentran las inasistencias?

| Servicio | Inasistencias | Participación |
|---|---:|---:|
| Consulta general | 77 | 40,74 % |
| Vacunación | 45 | 23,81 % |
| Control preventivo | 30 | 15,87 % |
| Desparasitación | 22 | 11,64 % |
| Seguimiento clínico | 15 | 7,94 % |
| **Total** | **189** | **100 %** |

Consulta general concentra el mayor número absoluto de inasistencias.

Este resultado sugiere que el servicio debe ser considerado prioritario para analizar posibles mejoras en la confirmación de citas.

Sin embargo, para determinar si tiene una tasa de inasistencia mayor que otros servicios, es necesario comparar las ausencias con el total de citas elegibles de cada servicio.

### 5. Cuarta pregunta: ¿cómo ayuda el dashboard?

El dashboard desarrollado en Power BI permite visualizar:

- Indicadores generales de las citas.
- Distribución por estado.
- Inasistencias por servicio.
- Evolución mensual.
- Comparación por canal de reserva.
- Filtros interactivos por servicio, canal, especie y AñoMes.

Estas herramientas facilitan explorar segmentos específicos y observar cambios en los indicadores.

### 6. Interpretación para el negocio

Los resultados permiten identificar oportunidades para mejorar la gestión de citas mediante estrategias de comunicación y seguimiento.

Se recomienda priorizar el análisis de los servicios que concentran más inasistencias y evaluar mecanismos de recordatorio y confirmación.

### 7. Mensaje principal

**La inteligencia de negocios permite pasar de contar citas a comprender su comportamiento y proponer acciones basadas en datos.**

### 8. Limitaciones

Los datos utilizados son sintéticos y corresponden al año 2025.

Los resultados son descriptivos y no demuestran por sí solos las causas de la inasistencia.
