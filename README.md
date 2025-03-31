# 00_data_validation

Este repositorio contiene un script en R Markdown (`00_data_validation.Rmd`) que realiza la validación de datos de un conjunto determinado de archivos o fuentes de datos. El objetivo es **asegurar la calidad, consistencia y limpieza de los datos** antes de su análisis o modelado.

## Contenido

- **00_data_validation.Rmd**: Archivo R Markdown que:
  - **Lee** uno o varios archivos de datos (por ejemplo, CSV, Excel, SQL, etc.).
  - **Valida** la estructura de las tablas y variables (tipos de datos, formato de columnas, etc.).
  - **Detecta** valores faltantes, inconsistencias, outliers y posibles errores en los datos.
  - **Genera** reportes o estadísticas descriptivas para facilitar la revisión de la calidad de la información.

## Requisitos

- **R** (versión 4.x o superior).
- **RStudio** (recomendado) o cualquier otro entorno para ejecutar archivos R Markdown.
- Paquetes de R necesarios, que pueden incluir (dependiendo del contenido de tu script):
  - `tidyverse` (o sus componentes como `dplyr`, `readr`, `ggplot2`, etc.).
  - `knitr`, `rmarkdown` (para la generación de reportes en formatos HTML, PDF o Word).
  - Otros paquetes de limpieza o validación de datos (p. ej., `janitor`, `data.table`, `lubridate`).

## Instalación de Paquetes

Si tu script utiliza paquetes adicionales, instálalos ejecutando en R:

```r
install.packages(c("tidyverse", "janitor", "lubridate", "data.table"))
```
> *Asegúrate de incluir en este listado todos los paquetes que se usen en tu script.*

## Uso

1. **Clona o descarga** este repositorio en tu máquina local.

2. Abre el archivo `00_data_validation.Rmd` en RStudio (o un editor equivalente).

3. En la parte superior del archivo, localiza y ajusta las rutas o parámetros de entrada:
   - Ruta(s) de archivo(s) de datos a validar.
   - Opciones de salida (por ejemplo, formato del reporte).
   - Parámetros específicos (si los hubiera) como tipo de codificación, delimitador, hoja de Excel, etc.

4. **Ejecuta** el R Markdown:
   - Oprime el botón “Knit” en RStudio


5. Revisa el reporte generado (HTML, PDF o Word) para ver los resultados de la validación:
   - Inconsistencias detectadas
   - Valores faltantes
   - Outliers
   - Resumen estadístico o descriptivo
   - Observaciones o sugerencias de corrección

## Autor

- **Luis Revilla** (https://github.com/LuisRevilla23)  
  *Desarrollador(a) y analista de datos.*

