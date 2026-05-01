# Detección de Plagio en Código Python

## Reporte final

[Click aquí para ver el reporte final](./reporte_final.pdf)

## Abstract

En los últimos años, el uso de herramientas de inteligencia artificial para el desarrollo de software ha crecido de manera acelerada, abriendo nuevas posibilidades para la generación, modificación y optimización de código. Sin embargo, este crecimiento también ha generado retos importantes relacionados con la calidad, seguridad y autoría del software. Uno de los problemas más relevantes es el plagio de código asistido por IA, ya que estas herramientas pueden modificar, reestructurar u ofuscar soluciones existentes, dificultando la identificación de similitudes entre programas.

Este problema no solo afecta el ámbito académico, sino también el desarrollo profesional de software. La práctica conocida como *vibe coding*, cuando se utiliza sin una comprensión adecuada del código generado, puede introducir errores funcionales, vulnerabilidades de seguridad y deuda técnica. En consecuencia, sistemas aparentemente funcionales pueden volverse difíciles de mantener, corregir o escalar.

Ante esta problemática, el presente proyecto propone el desarrollo de un modelo basado en una red neuronal multicapa —MLP— para detectar posibles casos de plagio en código Python. El modelo utiliza características léxicas, estructurales y semánticas extraídas de pares de código, con el objetivo de estimar la probabilidad de similitud sospechosa o plagio. De esta manera, se busca construir una herramienta auxiliar que aporte evidencia técnica para apoyar la revisión y análisis de autoría de código.

## Estructura del repositorio

```text
.
│ 
├── PlagioIA/
│   └── Presentacion final
├── scripts/
│   └── Libretas Jupyter con el código de los modelos y procesos ETL
├── reporte_final.pdf
│   └── Reporte final del proyecto
└── README.md
    └── Archivo de documentación principal del repositorio