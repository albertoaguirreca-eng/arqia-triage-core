# ARQIA Triage Core

Prototipo de análisis semántico, triaje psicosocial y validación sistémica desarrollado como parte de la formación en Inteligencia Artificial aplicada (Estud-IA).

---

## 1. Propósito del Proyecto
**ARQIA Triage Core** es un motor de análisis preliminar diseñado para identificar quiebres sistémicos, niveles de rigidez y riesgos psicosociales en narrativas y registros clínicos o comunitarios. Su objetivo principal es servir como una herramienta de apoyo analítico para la toma de decisiones en salud mental e intervención humana, optimizando el tiempo de triaje sin perder la sensibilidad contextual.

---

## 2. Alcance y Límites Éticos (Muy Importante)
* **Soporte, no reemplazo:** Este sistema es una herramienta de asistencia metodológica y analítica. **La decisión diagnóstica, clínica e interventiva final recae exclusivamente en los profesionales humanos.**
* **Privacidad por diseño:** El sistema opera bajo estrictos protocolos de protección de datos. Ninguna información sensible o identificable de pacientes es procesada ni almacenada en repositorios públicos.

---

## 3. Estructura del Repositorio
```text
arqia-triage-core/
├── README.md           # Documentación general y marco ético del proyecto
├── requirements.txt    # Dependencias y librerías de Python necesarias
├── .gitignore          # Archivos excluidos (seguridad y protección de datos)
├── data/               # Muestras de texto sintéticas y anonimizadas para pruebas
├── notebooks/          # Experimentos en Jupyter para limpieza y pruebas de inferencia
├── src/                # Código fuente modular (funciones de procesamiento y análisis)
└── tests/              # Pruebas básicas para verificar el funcionamiento del motor
