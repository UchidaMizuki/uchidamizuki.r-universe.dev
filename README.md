# uchidamizuki.r-universe.dev

Registry for the [r-universe](https://r-universe.dev/) of [Mizuki Uchida](https://github.com/UchidaMizuki):
<https://uchidamizuki.r-universe.dev>

R packages for input-output (IO) analysis, Japanese official statistics, and tidyverse-style data infrastructure.

## Packages

### Input-output analysis (econio family)

| Package | Description |
|---|---|
| [econio](https://github.com/UchidaMizuki/econio) | Input-output analysis |
| [econioread](https://github.com/UchidaMizuki/econioread) | Read input-output tables from csv/xls/xlsx files |
| [econiodatajp](https://github.com/UchidaMizuki/econiodatajp) | Ready-to-use Japanese input-output tables |
| [econagent](https://github.com/UchidaMizuki/econagent) | Utility functions and composite goods in economics |
| [ndgras](https://github.com/UchidaMizuki/ndgras) | n-dimensional generalized RAS (nD-GRAS) method |

### Japanese official statistics & geodata

| Package | Description |
|---|---|
| [jpstat](https://github.com/UchidaMizuki/jpstat) | Tools for the e-Stat API |
| [jpgrid](https://github.com/UchidaMizuki/jpgrid) | Grid square codes (JIS X 0410) |
| [jpcity](https://github.com/UchidaMizuki/jpcity) | Japanese municipality codes |
| [jpmap](https://github.com/UchidaMizuki/jpmap) | Japanese prefecture geometries for ggplot2 |
| [mlitdata](https://github.com/UchidaMizuki/mlitdata) | MLIT Data Platform API |
| [mojxmlr](https://github.com/UchidaMizuki/mojxmlr) | MOJ registry map XML |

### Data infrastructure

| Package | Description |
|---|---|
| [dibble](https://github.com/UchidaMizuki/dibble) | Dimensional data frames |
| [timbr](https://github.com/UchidaMizuki/timbr) | Forest/tree data frames |
| [navigatr](https://github.com/UchidaMizuki/navigatr) | Navigation menus for hierarchical data |
| [stickyr](https://github.com/UchidaMizuki/stickyr) | Data frames with persistent attributes |
| [adverbial](https://github.com/UchidaMizuki/adverbial) | Partialized functions and function composition |
| [tarchives](https://github.com/UchidaMizuki/tarchives) | Archived targets pipelines as packages |
| [dagbuildr](https://github.com/UchidaMizuki/dagbuildr) | DAG builder |
| [prorata](https://github.com/UchidaMizuki/prorata) | Proportional allocation |

## Installation

```r
install.packages("econio", repos = c("https://uchidamizuki.r-universe.dev", "https://cloud.r-project.org"))
```
