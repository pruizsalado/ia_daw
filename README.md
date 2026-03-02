# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- Empresa/sector (real o ficticia): Plataforma de streaming tipo Netflix.
- Problema a resolver: Alta tasa de cancelación de suscripciones (churn) y dificultad para personalizar recomendaciones de forma precisa.
- Objetivo de negocio (rentabilidad): Reducir cancelaciones y aumentar el tiempo de visualización para incrementar ingresos recurrentes.
  
## 2) Big Data: recogida masiva de datos
Describe por qué es Big Data (volumen, velocidad, variedad).
- Fuente 1: Historial de visualización (qué contenido ve cada usuario).
- Fuente 2: Interacciones (búsquedas, clics, tiempo de reproducción, abandono).
- Fuente 3: Datos de perfil (edad, país, tipo de suscripción, dispositivo).
- Volumen/velocidad (estimación):
  500 millones de eventos diarios.
  Procesamiento en tiempo real o casi real (<1 segundo).
- Formatos (texto, eventos, series temporales, imágenes, etc.):
- Eventos (logs JSON)
- Series temporales (tiempo de reproducción)
- Texto (búsquedas)
- Datos estructurados (perfiles en base de datos)

## 3) Tratamiento/análisis: pipeline de datos
Explica el flujo de forma ordenada:
- Ingesta (captura/eventos): Recogida automática de eventos de usuario mediante APIs y sistemas de tracking en la app/web.
- Limpieza/normalización: Eliminación de duplicados, tratamiento de valores nulos, unificación de formatos de fecha/hora.
- Almacenamiento (data lake/warehouse):
- Data Lake para datos en bruto (logs).
- Data Warehouse para análisis estructurado.
- Preparación de variables (features):
- Tiempo medio de visualización.
- Número de contenidos vistos por semana.
- Géneros preferidos.
- Frecuencia de uso.
- Análisis/BI (opcional): Dashboards con herramientas tipo Power BI o Tableau para analizar patrones de consumo.

## 4) IA aplicada: modelo y decisión
- Tipo de IA/técnica (clasificación, predicción, recomendación, anomalías, NLP...):
- Sistema de recomendación (filtrado colaborativo + modelos de clasificación).
- Modelo predictivo de churn (clasificación binaria).
- Entrada del modelo (qué datos usa): Historial de consumo, frecuencia de uso, interacción con recomendaciones, datos demográficos.
- Salida del modelo (qué produce):
- Lista personalizada de contenidos recomendados.
- Probabilidad de que el usuario cancele su suscripción.
- Decisión que habilita (qué hace la empresa con esa salida):
- Mostrar recomendaciones personalizadas.
- Enviar ofertas o promociones a usuarios con alta probabilidad de cancelación.

## 5) Rentabilidad: KPIs antes/después (mínimo 3)
KPI 1 (ingresos/coste/eficiencia):
- Antes:
- Después:
- Por qué mejora la rentabilidad:

KPI 2:
- Antes:
- Después:
- Por qué mejora la rentabilidad:

KPI 3:
- Antes:
- Después:
- Por qué mejora la rentabilidad:

## 6) Diagrama del pipeline (ASCII o Mermaid)
(Pega aquí el diagrama)

## 7) Riesgos y mitigación
Riesgo 1:
- Mitigación 1:

Riesgo 2:
- Mitigación 2:

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy):
- Importancia futura (3–5 años):
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo):
- Conclusión razonada:

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial):
- IA/técnica/modelo (enlace oficial):
