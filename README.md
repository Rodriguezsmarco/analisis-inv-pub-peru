📊 Análisis de Inversión Pública en Perú (2018–2025)
🎯 Objetivo

Analizar el desempeño de la inversión pública en Perú, evaluando su eficiencia, ejecución, duración y distribución, con el fin de identificar problemas estructurales y oportunidades de mejora en la gestión del gasto público.

📂 Dataset
49,085 proyectos de inversión
Periodo: 2018–2025
Variables analizadas:
Ejecución física y financiera
Costos y presupuesto
Duración de proyectos
Beneficiarios
Ubicación geográfica
Nivel institucional
⚙️ Metodología

El análisis se desarrolló en Python mediante Jupyter Notebooks:

EDA inicial
Limpieza y Feature Engineering
Análisis estructurado:
Ejecución
Financiero
Territorial
Institucional
Temporal
Duración
Eficiencia social
Concentración de inversión
Síntesis visual (heatmaps e insights)
📈 Principales Hallazgos
🔴 1. Alta concentración de la inversión




El 10% de los proyectos concentra el 75% de la inversión
El 1% concentra el 40%

👉 La inversión pública depende fuertemente de un pequeño grupo de megaproyectos, lo que incrementa el riesgo de ejecución.

⏳ 2. Proyectos más largos ejecutan peor




Proyectos cortos: 75% de avance físico
Proyectos muy largos: 48%

👉 Existe una relación negativa entre duración y desempeño.

👥 3. Baja eficiencia social




53.77% de proyectos presentan baja eficiencia
56% no tienen beneficiarios definidos

👉 Se evidencian problemas en la formulación y evaluación de proyectos.

🌎 4. Ejecución territorial heterogénea




La mayoría de departamentos presenta ejecución media-alta
La ineficiencia se concentra en pocos territorios

👉 Los problemas son focalizados, no generalizados.

💰 5. Más inversión no implica mejor ejecución




👉 No existe una relación positiva entre tamaño del proyecto y desempeño.

🧠 Insight Integrador

Los principales problemas de la inversión pública no están en la cantidad de recursos asignados, sino en la estructura de los proyectos.

Los proyectos de gran escala:

Son más largos
Ejecutan peor
Concentran el presupuesto

👉 Representan el principal riesgo del sistema de inversión pública.

🏛 Implicancias de Política Pública
Rediseñar megaproyectos en fases
Mejorar la estimación de beneficiarios
Focalizar supervisión en proyectos de alto presupuesto
Fortalecer capacidades en gobiernos locales
📁 Estructura del Proyecto
.
├── data/
│   ├── procesado/
│   │   └── Det_inv_limpia.csv
│   └── DETALLE_INVERSIONES.csv
│
├── notebooks/
│   ├── 1.eda_inv_publica.ipynb
│   ├── 2.data_clean.ipynb
│   ├── 3.analisis.ipynb
│   └── 4.insights_finales.ipynb ⭐
│
├── outputs/
│   ├── pareto_curve.png
│   ├── duracion_vs_ejecucion.png
│   ├── eficiencia_social.png
│   ├── ejecucion_departamento.png
│   └── costo_vs_ejecucion.png
│
├── requirements.txt
└── README.md
🛠 Tecnologías
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
📌 Conclusión

La inversión pública en Perú presenta desafíos estructurales asociados a la concentración y complejidad de los proyectos. Si bien la mayoría de inversiones tiene desempeño aceptable, los problemas se concentran en un subconjunto crítico de proyectos de gran escala.

👨‍💻 Autor

Marco Rodriguez
Economista | Data Analyst

⭐ Valor del Proyecto

Este proyecto demuestra:

Análisis de datos end-to-end
Pensamiento analítico aplicado a política pública
Capacidad de generar insights accionables
Comunicación efectiva con datos