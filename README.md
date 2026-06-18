# 📚 Graduados STEAM en Costa Rica — Análisis Exploratorio 2014–2022

![Estado](https://img.shields.io/badge/Estado-En%20progreso-yellow)
![Proyecto](https://img.shields.io/badge/Portafolio-Proyecto%201%20de%204-purple)
![Fuente](https://img.shields.io/badge/Fuente-OPES--CONARE-blue)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

> **Proyecto 1 de 4** de la serie
> [Radiografía de Empleabilidad STEAM en Costa Rica](https://github.com/RDRamosU/data-portfolio)

---

## 🔍 Pregunta central

**¿Cuántos graduados STEAM producen las universidades estatales de Costa Rica
por año y en qué áreas se concentran?**

---

## 📌 Preguntas de análisis

1. ¿Cuál es la tendencia de graduados STEAM entre 2014 y 2022?
2. ¿Qué áreas concentran más graduados: Ciencias, Tecnología, Ingeniería o Matemáticas?
3. ¿Cómo se distribuye la graduación por universidad estatal (UCR, TEC, UNA, UNED, UTN)?
4. ¿Existe una brecha de género en las graduaciones STEAM?
5. ¿Qué grados académicos (bachillerato, licenciatura, maestría) predominan en STEAM?

---

## 📂 Fuente de datos

| Atributo | Detalle |
|----------|---------|
| Institución | Oficina de Planificación de la Educación Superior (OPES) — CONARE |
| Repositorio oficial | [hdl.handle.net/20.500.12337/32](https://hdl.handle.net/20.500.12337/32) |
| Archivo 1 | Estadísticas de diplomas otorgados — universidades estatales 2014–2021 |
| Archivo 2 | Estadísticas de diplomas otorgados — universidades estatales 2018–2022 |
| Formato | PDF con tablas e infogramas |
| Periodo | 2014 – 2022 |
| Universidades | UCR · TEC · UNA · UNED · UTN |
| PII | Ninguna — datos agregados institucionales |
| Licencia | Uso público — repositorio institucional abierto |

> ⚠️ **Alcance:** Este análisis cubre exclusivamente las universidades estatales
> costarricenses. Las universidades privadas no están incluidas por no disponer
> de datos consolidados equivalentes en el periodo analizado.

---

## 🗂️ Estructura del proyecto

```
cr-graduados-steam-analisis/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   ├── raw/
│   │   ├── OPES_diplomas_estatales_2014_2021.pdf
│   │   └── OPES_diplomas_estatales_2018_2022.pdf
│   └── processed/
│       └── graduados_steam_2014_2022.csv
├── notebooks/
│   ├── 01_definicion_problema.ipynb
│   ├── 02_exploracion_datos.ipynb
│   ├── 03_limpieza_preparacion.ipynb
│   └── 04_visualizaciones_hallazgos.ipynb
└── assets/
    └── graficas/
```

---

## 📓 Notebooks

| Notebook | Descripción | Estado |
|----------|-------------|--------|
| [01 — Definición del problema](notebooks/01_definicion_problema.ipynb) | Contexto, preguntas de análisis e inventario de fuentes | 🟡 En progreso |
| [02 — Exploración de datos](notebooks/02_exploracion_datos.ipynb) | Extracción de tablas del PDF y primera inspección | ⚪ Pendiente |
| [03 — Limpieza y preparación](notebooks/03_limpieza_preparacion.ipynb) | Normalización, validación cruzada y dataset final | ⚪ Pendiente |
| [04 — Visualizaciones y hallazgos](notebooks/04_visualizaciones_hallazgos.ipynb) | Gráficas, tendencias y conclusiones | ⚪ Pendiente |

---

## 📊 Tablas clave extraídas del PDF

| Página | Tabla | Uso en el análisis |
|--------|-------|--------------------|
| 13 | Diplomas por universidad estatal, según año 2014–2021 | Tendencia general |
| 19 | Diplomas por grado académico, según año 2014–2021 | Nivel de formación |
| 20–21 | Diplomas por grado académico y clasificación STEAM, según año | Tendencia STEAM ⭐ |
| 22–23 | Diplomas por grado académico y clasificación STEM, según sexo | Brecha de género ⭐ |
| 24 | Diplomas por área de conocimiento, según año 2014–2021 | Distribución por área |
| 25 | Diplomas por clasificación STEAM y sexo, según año | STEAM + género ⭐ |

---

## 🔧 Cómo ejecutar este proyecto

```bash
# 1. Clona el repositorio
git clone https://github.com/RDRamosU/cr-graduados-steam-analisis.git
cd cr-graduados-steam-analisis

# 2. Instala las dependencias
pip install -r requirements.txt

# 3. Abre Jupyter
jupyter notebook
```

> También puede ejecutarse en **Google Colab** sin instalación local.

---

## 🛠️ Tecnologías

`Python 3.11+` `pandas` `NumPy` `Matplotlib` `Seaborn` `tabula-py` `pdfplumber` `Jupyter`

---

## 📎 Parte de la serie

| # | Proyecto | Estado |
|---|----------|--------|
| **1** | **Graduados STEAM en CR 2014–2022** ← estás aquí | 🟡 En progreso |
| 2 | Mercado laboral tech en CR | ⚪ Pendiente |
| 3 | Habilidades demandadas por empresas tech en CR | ⚪ Pendiente |
| 4 | Comparativa regional: CR vs Latinoamérica en STEAM | ⚪ Pendiente |

---

## 📰 Artículo publicado

Análisis completo publicado en LinkedIn:  
[Graduados STEAM de las Universidades Estatales de Costa Rica](https://www.linkedin.com/pulse/graduados-steam-de-las-universidades-estatales-costa-rica-zaj4e)

---

## 👤 Autor

**Ruben Dario Ramos**
🌐 [rubendario.dev](https://rubendario.dev) · 💼 [LinkedIn](https://www.linkedin.com/in/ruben-ramos) · 🐙 [GitHub](https://github.com/RDRamosU)
