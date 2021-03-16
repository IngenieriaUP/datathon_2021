# datathon_2021
Repositorio de datos para la Datathon 2021

<!-- Debido a la pandemia del COVID-19 la digitalización ha avanzado a pasos agigantados tanto en las empresas privadas como en las instituciones públicas. Uno de los grandes beneficios de esto, es la mejora en la transparencia de los procesos mediante la liberación de datos abiertos para el escrutinio público. Asimismo, estos datos pueden ser aprovechados para informar las soluciones a los desafíos propuestos en esta hackathon. Por un lado, para el desafío de Sistemas de la Información se pueden utilizar los datos de defunciones y casos de covid en conjunto con datos de movilidad urbana y demográficos para determinar las zonas más susceptibles al COVID-19. Por otro lado, se pueden utilizar los datos de la ubicación de los establecimientos de vacunación como variables de entrada a modelos de optimización para responder al desafío logístico. -->

## Conjuntos de datos sobre la vacunación y salud 💉 🏥

#### Información de fallecidos del sistema informático nacional de defunciones - SINADEF
- **Unidad de observación:** Individuo
- **Formato:** csv
- **Archivo:** fallecidos_sinadef.csv
- **Fuente:** [Datos abiertos Perú](https://www.datosabiertos.gob.pe/dataset/informaci%C3%B3n-de-fallecidos-del-sistema-inform%C3%A1tico-nacional-de-defunciones-sinadef-ministerio)

#### Casos positivos por COVID-19 - MINSA
- **Unidad de observación:** Individuo
- **Formato:** csv
- **Archivo:** positivos_covid.csv
- **Fuente:** [Datos Abiertos Perú](https://www.datosabiertos.gob.pe/dataset/casos-positivos-por-covid-19-ministerio-de-salud-minsa)

#### COVID-19 Mobility Report
- **Unidad de observación:** Subregión
- **Formato:** csv
- **Archivo:** 2020_PE_Region_Mobility_Report.csv
- **Fuente:** [Google](https://www.google.com/covid19/mobility/)

#### Disponibilidad de camas de Hospitalización y UCI a nivel nacional - SUSALUD
- **Unidad de observación:** Establecimiento
- **Formato:** csv
- **Archivo:** Camas_15-02-2021.csv
- **Fuente:** [Datos abiertos SUSALUD](http://datos.susalud.gob.pe/dataset/data-hist%C3%B3rica-del-registro-de-camas-diarias-disponibles-y-ocupadas-del-formato-f5002)

#### Disponibilidad de oxigeno medicinal - SUSALUD
- **Unidad de observación:** Establecimiento
- **Formato:** csv
- **Archivo:** Oxigeno_15-02-2021.csv
- **Fuente:** [Datos abiertos SUSALUD](http://datos.susalud.gob.pe/dataset/informaci%C3%B3n-por-d%C3%ADas-del-consumo-y-disponibilidad-de-ox%C3%ADgeno-del-formato-f5002)

#### Distribución de vacunas - MINSA
- **Unidad de observación**: Establecimientos
- **Formato:** csv
- **Archivos:** vacunados_minsa.csv
- **Fuente:**  [Mapa en línea](https://gis.minsa.gob.pe/GisVisorVacunados/)
> Los datos fueron extraídos automáticamente del mapa en línea el 16/02/21

#### Establecimientos de salud
- **Unidad de observación**: Establecimiento
- **Formato:** geojson
- **Archivo:** establecimientos_salud.geojson
- **Fuente:** [Guía de calles](http://www.guiacalles.com/movil/)

#### Mercados, supermercados y bodegas
- **Unidad de observación**: Establecimiento
- **Formato:** geojson
- **Archivo:** establecimientos_mercados_bodegas.geojson
- **Fuente:** [Guía de calles](http://www.guiacalles.com/movil/)

## Recomendaciones
Todo esto siempre se tiene que trabajar bajo [datos de grupos de edad y población del INEI](https://censos2017.inei.gob.pe/pubinei/). Por último también sería interesante comparar con [datos de vacunación de otros países](https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations).
