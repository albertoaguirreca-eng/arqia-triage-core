# ARQIA Triage Core

Prototipo de análisis y triaje psicosocial basado en simulación con datos sintéticos, desarrollado en el marco de la formación en Inteligencia Artificial aplicada (**Estud-IA** — EAFIT / Alcaldía de Medellín).

## 1. Problema y Enfoque
Las organizaciones suelen apoyarse en mediciones estáticas o respuestas genéricas que llegan tarde frente al desgaste y el *burnout*. **ARQIA Triage Core** plantea un enfoque estructurado para modelar señales de riesgo psicosocial y sostenibilidad psicofísica (ISP) a partir de variables como carga laboral, autonomía, soporte social y recuperación.

## 2. Regla de Confidencialidad y Datos Sintéticos
* **Confidencialidad por diseño:** Los datos clínicos sensibles no se suben a repositorios públicos.
* **Simulación controlada:** Para probar la lógica, los umbrales y la detección de alertas tempranas sin comprometer información real, el prototipo trabaja con datasets sintéticos estructurados (`data/triaje_simulado_arqia.csv`).

## 3. Camino Técnico y Validación ("Dato mata relato")
Más allá del código, el núcleo del proyecto está en la trazabilidad de las decisiones:
1. **Definición de la tarea y el error costoso:** Detectar perfiles en riesgo crítico evitando falsos negativos que dejen pasar alertas tempranas de *burnout*.
2. **Limpieza y estructuración:** Organización de variables numéricas estandarizadas y trazables en `Pandas` y `NumPy`.
3. **Baseline interpretable antes de escalar:** Partir de reglas y ponderaciones claras y auditables antes de introducir modelos neuronales o arquitecturas más complejas (como redes en Keras/TensorFlow cuando el problema lo justifique).
4. **Principio operativo:** *La señal es computacional; la decisión es humana.* El sistema entrega indicadores y alertas de apoyo, mientras que la valoración y la intervención corresponden al criterio profesional.

## 4. Estructura del Repositorio
* `data/`: Datos sintéticos de simulación y prueba.
* `notebooks/`: Cuadernos de experimentación en Google Colab (`arqia_practica_1.ipynb`).
* `src/`: Scripts y funciones modulares del prototipo.
* `requirements.txt`: Dependencias del entorno de trabajo.
