
# 📊 Análisis de Inversión Pública en Perú (2018–2025)

Este proyecto analiza la eficiencia de la ejecución de la inversión pública en el Perú durante el periodo 2018–2025, utilizando información proveniente de Invierte.pe (MEF Open Data).

## Problemática

La baja ejecución de la inversión pública representa uno de los principales desafíos de gestión pública en el Perú.

A pesar de incrementos sostenidos en los presupuestos asignados, persisten retrasos significativos, subejecución y baja efectividad en la generación de valor público.

El problema no se explica únicamente por restricciones presupuestales, sino por factores estructurales asociados al diseño, formulación y gestión de los proyectos.

Comprender estos patrones permite mejorar la priorización, supervisión y diseño de futuras inversiones.

## Objetivos

### General

Evaluar la eficiencia y los patrones de ejecución de la inversión pública en el Perú durante el periodo 2018–2025, identificando brechas territoriales, cuellos de botella y factores asociados a la baja ejecución.

### Específicos

- Analizar la concentración presupuestal de la inversión pública y su distribución entre proyectos
- Evaluar la relación entre duración de proyectos y nivel de ejecución
- Identificar diferencias territoriales en eficiencia de ejecución
- Examinar la relación entre tamaño de inversión y desempeño financiero
- Detectar patrones asociados a baja eficiencia social en la formulación de proyectos
- Proponer recomendaciones orientadas a mejorar la eficiencia del sistema

---

## Hallazgos

### 1. Alta concentración presupuestal

La inversión pública presenta una fuerte dependencia de un pequeño grupo de proyectos de gran escala, los cuales concentran una proporción significativa del presupuesto total.

Esto incrementa el riesgo sistémico, ya que retrasos en pocos proyectos generan impactos desproporcionados sobre la ejecución agregada.

### 2. Los proyectos más largos ejecutan peor

Se observa una relación negativa entre duración del proyecto y nivel de ejecución.

Los proyectos de mayor complejidad temporal presentan mayores retrasos, mayor incertidumbre y menor eficiencia operativa.

### 3. Más inversión no implica mejor ejecución

No existe una relación positiva consistente entre el tamaño financiero del proyecto y su nivel de ejecución.

Esto sugiere que el principal problema no radica en la disponibilidad de recursos, sino en la estructura y gestión de los proyectos.

### 4. Baja eficiencia social en la formulación

Se identifican limitaciones relevantes en la etapa de formulación, especialmente en variables asociadas a beneficiarios y dimensionamiento social del proyecto.

Esto afecta la calidad de priorización y el retorno esperado de la inversión pública.

### 5. Ineficiencia territorial focalizada

La baja ejecución no es homogénea a nivel nacional.

Existen brechas territoriales importantes, donde determinados gobiernos subnacionales concentran mayores niveles de ineficiencia.

Esto evidencia la necesidad de intervenciones focalizadas y fortalecimiento institucional diferenciado.

## Recomendaciones

### Rediseñar megaproyectos mediante ejecución por fases

Los proyectos de gran escala concentran presupuesto, presentan mayor duración y menor eficiencia.

La fragmentación estratégica por etapas puede reducir riesgo operativo y mejorar el control de ejecución.

### Fortalecer la calidad de formulación de proyectos

La baja eficiencia social evidencia debilidades en la estimación de beneficiarios y dimensionamiento técnico.

Se requiere mejorar los criterios de priorización desde etapas tempranas.

### Focalizar supervisión en proyectos críticos

No todos los proyectos generan el mismo riesgo sistémico.

La supervisión debe concentrarse en proyectos de alto monto, alta duración y bajo desempeño.

### Reforzar capacidades en gobiernos subnacionales

Las brechas territoriales muestran heterogeneidad institucional significativa.

La asistencia técnica debe priorizar gobiernos locales con mayores niveles de ineficiencia.

### Separar gestión presupuestal de calidad de ejecución

Incrementar presupuesto no garantiza mejores resultados.

La mejora debe centrarse en gobernanza, diseño y control, no únicamente en asignación financiera.

---

## Tecnología

### Herramientas utilizadas

- **Python** → limpieza, transformación y análisis exploratorio de datos
- **Pandas** → procesamiento y manipulación de grandes volúmenes de datos
- **NumPy** → operaciones numéricas y tratamiento de variables cuantitativas
- **Matplotlib / Seaborn** → visualización analítica y exploración de patrones
- **Jupyter Notebook** → desarrollo exploratorio y documentación técnica
- **Git & GitHub** → control de versiones y portafolio profesional

## KPIs Analizados

### 1. Tasa de ejecución financiera

Porcentaje de presupuesto ejecutado respecto al monto total de inversión.

Permite evaluar eficiencia presupuestal y nivel de cumplimiento financiero.

### 2. Avance físico de inversión

Evalúa el progreso real de ejecución física del proyecto frente a lo programado.

Permite identificar brechas entre ejecución financiera y avance operativo.

### 3. Duración efectiva del proyecto

Tiempo transcurrido desde la viabilidad hasta el cierre o estado actual.

Permite medir complejidad operativa y riesgo de retraso.

### 4. Concentración presupuestal

Participación acumulada del presupuesto total en proyectos de gran escala.

Permite evaluar dependencia sistémica y exposición a riesgo estructural.

### 5. Eficiencia territorial

Comparación de desempeño entre regiones, departamentos y niveles de gobierno.

Permite detectar brechas geográficas y focalizar intervenciones.

### 6. Eficiencia social del proyecto

Relación entre monto invertido y población beneficiaria estimada.

Permite evaluar calidad de formulación y retorno social esperado.

### 7. Relación inversión–desempeño

Análisis entre tamaño financiero del proyecto y nivel de ejecución.

Permite validar si mayores recursos se traducen en mejor desempeño.

## Estructura del Repositorio

```text
analisis-inv-pub-peru/
│
├── data/
│   ├── procesado/
│   │   └── Det_inv_limpia.csv
│   └── DETALLE_INVERSIONES.csv (No incluído por almacenamiento)
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
```
