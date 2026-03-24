# IUSI Progresivo Guatemala — Documentación Técnica

Estimación del impacto fiscal y conductual de un sistema progresivo del Impuesto Único Sobre Inmuebles (IUSI) en Guatemala, con análisis comparativo de la Iniciativa Legislativa 6586.

## Ver el reporte

👉 **[iusi-progresivo-gt](https://TUUSUARIO.github.io/TUREPO/iusi-progresivo-gt/)** *(actualiza la URL con tu usuario/repo)*

## Metodología

El análisis emplea tres modelos complementarios:

1. **Modelo Paramétrico** — Estimación del espacio fiscal disponible bajo un IUSI progresivo, con tres escenarios (conservador / moderado / optimista).
2. **ABM (Agent-Based Model)** — Dinámica de cumplimiento fiscal con 10,000 agentes heterogéneos; curva de Laffer emergente.
3. **SEM (Structural Equation Model)** — Efectos mediados del impuesto sobre acceso a vivienda (lavaan MLR+FIML, N=200, datos sintéticos calibrados).

## Datos

| Fuente | Tipo | Cobertura |
|--------|------|-----------|
| INE Censo 2018 — HOGAR_BDP.csv | Real | 3,275,931 hogares · 340 municipios |
| MINFIN Ejecución Presupuestaria Municipal 2025 | Real | 280 municipios · Q1,854M IUSI |
| GADM v4.1 | Real | 354 polígonos municipales |
| Panel SEM | Sintético (calibrado) | N=200 · Colombia/Uruguay/Chile/CR/HN |

> El modelo paramétrico y el ABM usan datos reales del INE Censo 2018.
> El panel para el SEM es sintético — los coeficientes son ilustrativos de la dirección causal esperada, no estimaciones validadas para Guatemala.

## Reproducibilidad

Requiere R ≥ 4.4 con: `tidyverse`, `sf`, `lavaan`, `ggplot2`, `patchwork`, `viridis`, `scales`.

```r
source("R/01b_ingest_real_data.R")
source("R/02_parametric_model.R")
source("R/03_sensitivity_analysis.R")
source("R/04_abm_model.R")
source("R/05_sem_model.R")
source("R/06_visualizations.R")
source("R/07_congreso_comparison.R")
source("R/08_decil_impact.R")
source("R/09_rent_passthrough.R")
source("R/10_catastro_dynamic.R")
source("R/11_reclasificacion_abm.R")
```

El `index.html` es autocontenido (imágenes embebidas en base64) — no requiere servidor ni dependencias externas.

## Versión

Marzo 2026 · R 4.5.3 · lavaan 0.6-21 · tidyverse 2.0
