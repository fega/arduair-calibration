# Pruebas de calibraci/on de sensores de meteorolog/ia

Se usan los notebooks presentes en esta carpeta para generar las variables de calibraci/on de los sensores usados en el proyecto Arduair.
## Estructura:

### Datos de entrada
**DATA.TXT:** Datos generados por el dispositivo Arduair, formato csv
**DATA_CIUDADELA.TXT:** Datos generados por la estaci/on ubicada en Colombia/Sder/Bmanga, barrio real de minas, propiedad de la CDMB

### Procesamiento
**Test.ipynb:** Algunas pruebas de funcionamiento de Jupyter y pandas.
**Raw meteorology data processing.ipynb:** Adecuaci/on de los datos generados por el dispositivo Arduair
**Raw estaci/on meteorology data processing.ipynb:** Adecuaci/n de los datos generados por la estaci/on
**comparison.ipynb:** Generaci/on de resultados

### Resultados### Procesamiento
**Test.ipynb:** Algunas pruebas de funcionamiento de Jupyter y pandas.
**Raw meteorology data processing.ipynb:** Adecuaci/on de los datos generados por el dispositivo Arduair
**Raw estaci/on meteorology data processing.ipynb:** Adecuaci/on de los datos generados

**Temperature[C]**
y = x*0.1688896859403191 + 19.265576344271782

**Humidity[%]**
y = x*0.3647440519259984 + 64.02510521599481

**Pression[mmHg]**
y = x*0.7182389783230818 + 28.01007387176966

**Radiation[W/m2]**
y = x*0.013153785956325843 + -1.6451526314835176

