# Applied Multivariate Analysis – Business Case Studies

Este repositorio reúne una serie de **casos de estudio aplicados** desarrollados en la materia  
**Aplicación de Métodos Multivariados en Ciencia de Datos (MA2003B)**.  
Cada caso aborda un problema real de negocio y aplica una metodología estadística distinta para su análisis e interpretación.

---

## 1. Información del Equipo

| Nombre                         | Matrícula |
|-------------------------------|-----------|
| Adrián Tavera Aquino          | A01659113 |
| Daniela Robles Estrada        | A01659074 |
| Elian Alejandro López de Alba | A01659582 |

---

## 2. Tabla Resumen de Casos

| Caso | Metodología                 | Problema de Negocio                                   | Carpeta                        |
|-----:|----------------------------|------------------------------------------------------|--------------------------------|
| 01   | Análisis Factorial          | Identificar dimensiones clave de satisfacción B2B   | `case-01-factor-analysis/`     |
| 02   | Análisis Discriminante      | Clasificar riesgo crediticio (default / no default) | `case-02-discriminant-analysis/` |
| 03   | Análisis de Clusters        | Segmentar clientes para marketing diferenciado      | `case-03-cluster-analysis/`    |

---

## 3. Comparación Metodológica

| Aspecto                     | Factor Analysis                     | Discriminant Analysis                  | Cluster Analysis                       |
|-----------------------------|-------------------------------------|----------------------------------------|----------------------------------------|
| Tipo de aprendizaje         | No supervisado                      | Supervisado                            | No supervisado                         |
| Objetivo principal          | Reducir dimensionalidad             | Clasificar observaciones               | Segmentar observaciones                |
| Variable objetivo           | No                                  | Sí                                     | No                                     |
| Output principal            | Factores latentes                   | Clases predichas                       | Grupos o segmentos                     |
| Decisión de negocio         | Priorizar dimensiones clave         | Aceptar / rechazar clientes            | Diseñar estrategias por segmento       |
| Nivel de interpretabilidad  | Medio–Alto                          | Alto                                   | Medio                                  |

---

## 4. Lecciones Aprendidas

- **Importancia del preprocesamiento:**  
  La estandarización y limpieza de datos fue crítica en los tres casos para evitar sesgos y distorsiones en los resultados.

- **No existe una sola “mejor” técnica:**  
  Cada método responde a un tipo distinto de pregunta. El análisis factorial ayuda a entender *por qué* ocurren los fenómenos, el discriminante permite *predecir*, y el clustering sirve para *descubrir patrones ocultos*.

- **Interpretación > Métrica:**  
  Aunque modelos como LDA o K-Means puedan mostrar métricas altas, su valor real está en que los resultados sean comprensibles y útiles para la toma de decisiones de negocio.

- **Traducción a negocio es clave:**  
  El mayor reto no fue técnico, sino convertir resultados estadísticos (factores, coeficientes, clusters) en recomendaciones claras y accionables.

---

## Contexto Académico

Repositorio desarrollado como parte de la materia  
**Aplicación de Métodos Multivariados en Ciencia de Datos (MA2003B)**  
Tecnológico de Monterrey
```

---
