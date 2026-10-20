# Mapa de competencias — Machine Learning

**Programa v1.0.0 · SETS Framework v1.4.1 · Namespace `ML00–ML14`**

Comprender cómo los modelos aprenden patrones a partir de datos, bajo qué supuestos generalizan, cómo evaluar su utilidad y cómo elegir entre métodos estadísticos y algoritmos de aprendizaje con evidencia.

Este mapa define competencias prioritarias, no agota todos los temas que pueden estudiarse. Enseña preguntas relevantes fuera del índice y relaciónalas con competencias existentes cuando ayude; solo propón un módulo nuevo si el tema es recurrente o estratégicamente central. Fundamento, profundización y especialización son alcances adaptativos, no fases obligatorias.

## Competencias observables

| ID | Competencia | Capacidad observable | Pregunta conceptual central | Evidencia posible |
| --- | --- | --- | --- | --- |
| ML00 | Diagnóstico y definición de tarea | Identificar la pregunta, la unidad de predicción, la señal disponible y las limitaciones de datos. | ¿Qué queremos predecir o descubrir y cómo sabremos si ayuda? | Formulación de tarea, objetivo y criterios de éxito. |
| ML01 | Fundamentos del aprendizaje estadístico | Relacionar datos, hipótesis, función objetivo, entrenamiento y predicción. | ¿Qué aprende realmente un modelo a partir de ejemplos? | Explicación de la relación entre datos, hipótesis y objetivo. |
| ML02 | Datos, variables y calidad | Examinar representatividad, calidad, etiquetas, sesgos, valores ausentes y fuga de información. | ¿Qué información está disponible al aprender y al predecir? | Auditoría de datos y amenazas a la validez. |
| ML03 | Particiones y diseño experimental | Separar entrenamiento, validación y prueba según tiempo, grupos y dependencia entre observaciones. | ¿Qué debe permanecer independiente para medir generalización? | Diseño de particiones defendible y análisis de fuga. |
| ML04 | Regresión y modelos lineales | Comprender predicción numérica, funciones de pérdida, coeficientes y supuestos. | ¿Qué relación aprende un modelo y cómo interpretamos el error? | Baseline lineal y análisis de residuos. |
| ML05 | Clasificación y decisión | Distinguir puntuación, probabilidad, umbral, clase y coste de error. | ¿Cómo se convierte una salida del modelo en una decisión útil? | Matriz de confusión y umbral elegido según costes. |
| ML06 | Árboles, ensembles y métodos basados en instancias | Comparar árboles, random forests, boosting, k-NN y otros métodos según estructura de datos. | ¿Qué patrones capturan estos modelos y qué complejidad introducen? | Comparación con un baseline y errores segmentados. |
| ML07 | Aprendizaje no supervisado | Explorar clustering, reducción de dimensionalidad y estructura sin etiquetas. | ¿Qué significa encontrar estructura cuando no existe una respuesta correcta conocida? | Interpretación prudente de grupos o representaciones. |
| ML08 | Generalización, sesgo-varianza y regularización | Explicar sobreajuste, subajuste, complejidad y mecanismos de control. | ¿Por qué el buen desempeño de entrenamiento no garantiza buen desempeño futuro? | Diagnóstico de curvas de aprendizaje y propuesta de control. |
| ML09 | Métricas, calibración y selección de umbrales | Elegir métricas según distribución, prevalencia y consecuencias de error. | ¿Qué métrica refleja el objetivo y qué oculta? | Comparación de métricas y calibración cuando aplique. |
| ML10 | Selección de modelos e hiperparámetros | Diseñar comparaciones justas y evitar adaptar decisiones al conjunto de prueba. | ¿Cómo comparamos modelos sin engañarnos con el experimento? | Protocolo reproducible de selección y reporte. |
| ML11 | Análisis de errores, explicabilidad y equidad | Inspeccionar fallos por segmento, interpretar modelos con cautela y evaluar impactos desiguales. | ¿Quién recibe los errores y qué explica o no explica el modelo? | Análisis de errores por grupos y limitaciones interpretativas. |
| ML12 | Incertidumbre, desbalance y detección de anomalías | Analizar clases raras, umbrales, incertidumbre y señales fuera de distribución. | ¿Cuándo debe el modelo abstenerse o solicitar revisión? | Política de abstención o revisión basada en evidencia. |
| ML13 | Familias de aprendizaje y puente a Deep Learning | Reconocer cuándo los modelos clásicos son adecuados y cuándo una red neuronal puede aportar valor. | ¿Qué evidencia justifica aumentar la complejidad del modelo? | Comparación razonada de familias con restricciones explícitas. |
| ML14 | Capstone de Machine Learning | Integrar formulación, datos, baseline, evaluación, errores y límites. | ¿El modelo aporta valor frente a una alternativa sencilla? | Informe experimental reproducible con recomendación final. |

## Cómo se aprende

Selecciona las lentes conceptuales según la pregunta y las brechas observadas: origen/problema, mecanismo causal, supuestos y límites, alternativas/trade-offs y transferencia. No conviertas las lentes en cinco pasos obligatorios ni en una escala de dominio.

## Formas de evidencia

La evidencia puede ser una explicación propia, una predicción, un cálculo, un diagrama, una traza, una comparación, un experimento, un análisis de error o una implementación. Una respuesta del tutor, una lectura o una salida copiada no demuestra por sí sola el desempeño del estudiante.

## Criterio de comprensión profunda

Se busca que el estudiante pueda explicar el problema y el mecanismo, declarar supuestos, anticipar consecuencias o fallos, reconocer límites y razonar sobre alternativas. El dominio se decide con las reglas de `sets-framework/core/ASSESSMENT_ENGINE.md`, no por contar módulos completados.
