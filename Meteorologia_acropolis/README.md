# Pruebas de calibracion de sensores de meteorologia

Se usan los notebooks presentes en esta carpeta para generar las variables de calibracion de los sensores usados en el proyecto arduair.

## Estructura:

### Datos de entrada
**DATA.TXT:** Datos generados por el dispositivo Arduair, formato csv
**DATA_CIUDADELA.TXT:** Datos generados por la estacion ubicada en Colombia/Sder/Bmanga, barrio real de minas, propiedad de la CDMB

### Procesamiento
**Test.ipynb:** Algunas pruebas de funcionamiento de Jupyter y pandas.
**Raw meteorology data processing.ipynb:** Adecuacion de los datos generados por el dispositivo Arduair
**Raw estacion meteorology data processing.ipynb:** Adecuacion de los datos generados por la estacion
**comparison.ipynb:** Generacion de resultado

### Resultados
Temperature[C]
y = x*0.1688896859403192 + 19.26557634427178
Humidity[%]
y = x*0.36474405192599857 + 64.02510521599481
Pression[mb]
y = x*0.7182389783230818 + 28.010073871769578
Radiation[mb]
y = x*0.013153785956325851 + -1.6451526314835176

