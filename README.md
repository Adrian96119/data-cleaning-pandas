
# data-cleaning-pandas by ADRIÁN MADRID


## LIMPIEZA, FILTRO ,MANIPULACION DE DATOS Y ANALISIS ESTADÍSTICOS .

**VAMOS A TRABAJAR CON UN TEMA INTERESANTE ----------------> EL ATAQUE DE LOS TIBURONES.

-NOS VAN A DAR UNA TABLA CON TODO TIPO DE INFORMACIÓN ACERCA DE LOS ATAQUES DE TIBURON.
*La edad de los casos
*Los paises donde se producen ataques
*Las areas de esos paises donde se producen esos casos
*El año de cada caso
*El género de las victimas
*Nos muestran si esos casos fueron mortales o no
*La fecha

Y un largo etcétera de información que nos puede venir muy bien a la hora de analizar ciertos datos estadísticos.

## LO PRIMERO:

**DEBEMOS HACER UN ANALISIS PREVIO DE LA INFORMACIÓN QUE NOS DAN Y USAR SOLO LOS DATOS RELEVANTES PARA NUESTRO ESTUDIO

**DEBEMOS QUEDARNOS CON LAS COLUMNAS QUE NOS PUEDAN INTERESAR, Y EN ESTE CASO NOS HEMOS QUEDADO CON:

- EL AÑO EN EL QUE SE PRODUJERON LOS CASOS
-LOS PAISES EN DONDE SE PRODUCEN LOS ATAQUES
-lOS TERRIRORIOS DE LOS PAISES DONDE SE PRODUCEN ESOS ATAQUES
-LA ACTIVIDAD QUE SE ESTABA REALIZANDO EN ESE MOMENTO
-EL GENERO Y LA EDAD DE LAS VICTIMAS
-La LESION QUE SE PRODUJO CON EL ATAQUE
-LOS QUE MURIERON Y LOS QUE SOBREVIVIERON, O INCLUSO DE LOS QUE NO SE SABE NADA

## LO SEGUNDO:

**UNA VEZ QUE TENEMOS YA LAS COLUMNAS SELECCIONADAS, TENDREMOS QUE LIMPIARLAS DE DATOS IRRELEVANTES, QUE NO SEAN COHERENTES,
, DATOS NULLOS CON LOS QUE NO SE PUEDEN TRABAJAR, ELIMINAR LAS FILAS DUPLICADAS ETC..

#### En este caso, y a lo general hemos:

- ELIMINADO FILAS QUE SE REPITEN
- HEMOS ELIMINADO TODOS LOS VALORES NULOS DE TODAS LAS COLUMNAS
- HEMOS CAMBIADO EL TIPO DE DATO ADECUANDONOS A CADA COLUMNA, ES DECIR, ADECUAR LOS VALORES AL TIPO DE DATO DE SU
COLUMNA CORRESPONDENTE. EJEMPLO. LA COLUMNA YEAR DEBEN SER TODO DATOS DE TIPO NUMERICO, ASIQUE DEBEMOS ENCARGARNOS DE QUE TODOS DATOS SEAN NUMERICOS PARA PODER TRABAJARLOS.
- HEMOS CORREGIDO ALGUNOS VALORES SIN SENTIDO, ALGUNOS LOS HEMOS QUITADO, Y OTROS LOS HEMOS CAMBIADO POR LA MEDIA DE ESE VALOR, COMO EN LA COLUMNA DEL GENERO, QUE HABÍA ALGUN DATO INCORRECTO, COMO EL STRING "LLI".

##### AL FINAL NOS HA TENIDO QUE QUEDAR UNA TABLA MAS REDUCIDA Y LIMPIA CON LA QUE NOS SERA MAS FACIL TRABAJAR ####

### TOCA LA PARTE DEL ANALISIS

**EN ESTE PROYECTO, HEMOS QUERIDO ANALIZAR LOS ATAQUES A SURFISTAS EN ESTADOS UNIDOS.
 PARA ELLO HEMOS FILTRADO TODAS LAS FILAS DONDE SE ENCUENTRA ESTADOS UNIDOS Y QUE HAGAN SURF.

Hemos reducido el espectro y por lo tanto ya podemos hacer ciertos analisis como por ejemplo:
 
 -TOP SURFISTAS MUERTOS POR AREA
 -SURFISTAS MUERTOS EN ESTADOS UNIDOS
 -RELACION DE GENERO RESPECTO A LAS MUERTES
 -TOP 3 ATAQUES POR AREA A SURFISTAS EN EE.UU
 -COMPARATIVA AREAS POR GENERO
 -ULTIMO ANALISIS - MUERTES EN LOS ULTIMOS 8 AÑOS
 
 **TODOS O CASI TODOS ESTOS ANÁLISIS HAN SIDO REPRESENTADOS EN DIFERENTES TIPOS DE GRAFICAS, DONDE EN CADA UNA SE COMENTAN LAS
 CONCLUSIONES QUE SACAMOS DE ELLAS.
 
 
 **FINALMENTE SE HACE UN RESUMEN DEL CONJUNTO DE LOS ANALISIS SACANDO NUESTRAS CONCLUSIONES FINALES.


  
## NOTAS DEL PROYECTO

**La mayor parte del código fuente esta comentado
**El archivo para abrir el DataFrame está ubicado en la misma carpeta donde se encuentra este mismo Readme
**El cuaderno donde se desarrolla todo el proyecto está en la misma carpeta que el Readme, y el archivo CSV, con el nombre de clean.ipynb


