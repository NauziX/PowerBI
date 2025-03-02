
## Descripción General

- **General Dashboard**  
  Ofrece una vista global de las startups, incluyendo su distribución geográfica, métricas principales (número total de startups, media de empleados, etc.) y sector. Es un panel que ayuda a comprender el panorama completo de las compañías aceleradas por Y Combinator.

- **Atomic Dashboard**  
  Se centra en el análisis detallado de las empresas **inactivas**, mostrando:
  - Distribución por sectores (B2B, Consumer, etc.) y estado (Acquired, Active, Inactive).  
  - Proporción de inactivas según el tamaño de equipo.  
  - Evolución de inactivas a lo largo del tiempo (Summer/Winter + año).  
  - Un mapa que ilustra la ubicación de donde estan las startups inactivas.  
  

## Características

 **Limpieza de Datos**:  
  - Partimos de varios ficheros CSV originales, depurando y transformando la información. 
  - Se han eliminado columnas irrelevantes y corregido campos mal asignados.

**Modelo de Datos y Relaciones**:  
  - Se establecen las relaciones adecuadas entre tablas.
 
**Medidas DAX personalizadas**:  
  - Cálculo de KPIs   
  - Uso de funciones como `SUMMARIZECOLUMNS`, `TOPN`, `DISTINCTCOUNT` y `CALCULATE`.

**Visualizaciones Interactivas**:  
  - Barras apiladas, gráficos de líneas, tarjetas, mapas, etc.  
  - Slicers para filtrar.

**Diseño**:  
  - Paleta de colores orientada a la marca   
  - Estética limpia, con énfasis en métricas grandes y visualizaciones claras.

## Requisitos

- **Power BI Desktop**   
- Archivos CSV de https://www.kaggle.com/datasets/sashakorovkina/ycombinator-all-funded-companies-dataset/data  

## Instrucciones de Uso

1. **Clonar** este repositorio:  
   ```bash
   git clone https://github.com/NauziX/PowerBI.git
