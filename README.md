# 🐾 Análisis de ingresos y gestión de una clínica veterinaria

**Proyecto personal de análisis de datos y visualización en Power BI.**

El proyecto busca transformar los registros de una clínica veterinaria en información clara para analizar ingresos, actividad y desempeño operativo. El foco no estuvo solamente en construir gráficos, sino también en **la calidad de la información** y en **cómo presentar indicadores útiles para quien toma decisiones**.

---

## 🎯 Objetivos

- Analizar la evolución de los ingresos a lo largo del tiempo.
- Comparar el desempeño de los empleados mediante los indicadores disponibles.
- Identificar los tipos de animales con mayor cantidad de atenciones.
- Explorar los resultados por mes y tratamiento.
- Diseñar un tablero intuitivo, con una lectura clara de los datos.

## 📊 Dashboard e indicadores

| Elemento | ¿Qué permite analizar? |
| --- | --- |
| **Ingresos totales (KPI)** | Importe total registrado en los datos. |
| **Evolución de ingresos** | Tendencias y cambios a lo largo del tiempo. |
| **Desempeño por empleado** | Comparación del indicador representado para cada empleado. |
| **Animales más atendidos** | Distribución de las atenciones según tipo de animal. |
| **Filtros por mes y tratamiento** | Exploración de la información según el período o servicio seleccionado. |

> **Criterio de interpretación:** más ingresos o atenciones no significan necesariamente mayor rentabilidad. Para analizarla también sería necesario disponer de costos y márgenes.

## 🔎 Enfoque del proyecto

### 1. Calidad de datos

Antes de interpretar un indicador es importante revisar la información que lo alimenta. El repositorio incluye un archivo de datos sin corregir y un archivo Excel, lo que permite conservar el contexto de trabajo con los datos.

La intención es evitar que problemas en la información de origen se traduzcan en conclusiones erróneas en el tablero.

### 2. Análisis orientado al negocio

Los gráficos responden a preguntas concretas: cómo evolucionan los ingresos, dónde se concentra la actividad y qué diferencias aparecen al filtrar los resultados. El objetivo es que los datos ayuden a **explorar y comprender el funcionamiento de la clínica**.

### 3. Claridad en la visualización

El tablero tuvo una primera propuesta visual con un uso marcado de negro y rojo. Luego se replanteó el diseño para priorizar **legibilidad, jerarquía visual y una lectura más intuitiva**.

La elección de colores no es solo estética: también puede influir en la percepción de los resultados. Por ejemplo, un color asociado a alertas puede sugerir problemas incluso cuando un indicador no es negativo.

## 💡 Aprendizajes

1. **Calidad antes que visualización:** la confiabilidad de los indicadores depende de los datos de origen.
2. **Contexto antes que conclusiones:** una métrica necesita interpretarse según el negocio y las limitaciones de los datos.
3. **Claridad antes que complejidad:** un buen dashboard facilita encontrar respuestas, en lugar de exigir que el usuario descifre los gráficos.

## 🛠️ Herramientas

- **Power BI Desktop:** modelado y visualización interactiva.
- **Excel y CSV:** archivos con los datos utilizados en el proyecto.
- **Power BI Project (`.pbip`):** formato del proyecto que separa los componentes del informe y del modelo semántico.

## 📁 Estructura del repositorio

```text
analisis-ingresos-veterinaria/
├── Tablero de gestion y analisis.pbip
├── Tablero de gestion y analisis.Report/
├── Tablero de gestion y analisis.SemanticModel/
├── Datosveterinaria.xlsx
├── Datos no corregidos.csv
├── images/
└── .gitignore
```

## ▶️ Cómo abrir el proyecto

1. Descargá el repositorio desde **Code → Download ZIP** o clonalo con Git.
2. Abrí `Tablero de gestion y analisis.pbip` en una versión de **Power BI Desktop** compatible con proyectos `.pbip`.
3. Si Power BI solicita actualizar las rutas de origen, vinculá los archivos de datos que se encuentran en el repositorio.
4. Explorá los indicadores y utilizá los filtros de mes y tratamiento.

> Al abrir el proyecto en otro equipo puede ser necesario configurar nuevamente las rutas locales a los archivos de origen y actualizar los datos.

---

**Autor:** [Lucas Carrizo](https://github.com/LucasCarrizo10)  
**Tipo de proyecto:** práctica personal · Análisis de datos · Business Intelligence
