# Guion de sustentación — Avance 3

**Apertura:** Nuestro proyecto VetHuella Huila estudia la inasistencia a citas veterinarias de 2025 usando un conjunto de datos sintéticos y Power BI.

**Preparación:** Iniciamos con 1.512 registros y eliminamos 12 duplicados. Así obtuvimos 1.500 citas consistentes.

**Modelo:** Organizamos una tabla de hechos, Fact_Citas, y cuatro dimensiones: servicio, paciente, canal y fecha. Creamos medidas DAX y visualizaciones interactivas.

**Resultado principal:** Registramos 1.017 citas atendidas y 189 no asistidas. La tasa se calcula dividiendo 189 entre 1.017 más 189, lo que da 15,67 %. No incluimos las canceladas ni las reprogramadas en ese denominador.

**Servicios:** Consulta general concentra 77 ausencias, seguida de vacunación con 45, control preventivo con 30, desparasitación con 22 y seguimiento clínico con 15. Es una comparación de cantidades absolutas, no de tasas por servicio.

**Propuesta:** Recomendamos evaluar recordatorios, facilitar confirmaciones y monitorear el indicador cada mes. Son propuestas, no acciones implementadas.

**Cierre:** El proyecto demuestra cómo la limpieza, el modelo dimensional y el dashboard convierten datos en información útil para decisiones. Sus conclusiones son descriptivas y están limitadas al conjunto sintético estudiado.
