<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Telecomunicaciones`**</h1>

<p align='center'>
<img src="https://newses.cgtn.com/n/BfJIA-CAA-HAA/BceGDAA.jpg"  height=300>
<p>

# <h1 align="center">**`Data Analist: Nicolás Agustín Ibarra`**</h1>

# **Contexto**

Las telecomunicaciones se refieren a la transmisión de información a través de medios electrónicos, como la telefonía, la televisión, la radio y, más recientemente, el internet. Estos medios de comunicación permiten la transmisión de información entre personas, organizaciones y dispositivos a largas distancias.

El internet, por su parte, es una red global de computadoras interconectadas que permite el intercambio de información en tiempo real. Desde su creación, ha tenido un impacto significativo en la vida de las personas, transformando la manera en que nos comunicamos, trabajamos, aprendemos y nos entretenemos.

La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua incluso en medio de una pandemia mundial. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, y en casi cualquier lugar del mundo. 


# **Rol a desarrollar**

En el presente documento se plasma el trabajo a desarrollar a partir de la contratacion por parte de ENACOM de un 'data analist', para llevar a cabo un plan del Gobierno Nacional Argentino.
### Quien es ENACOM?
El Enacom es un ente autárquico y descentralizado que funciona en el ámbito de la Jefatura de Gabinete de Ministros de la Nación. Su objetivo es conducir el proceso de convergencia tecnológica y crear condiciones estables de mercado para garantizar el acceso de todos los argentinos a los servicios de internet, telefonía fija y móvil, radio, postales y televisión.

Enacom fue creado en Diciembre del 2015 a través del Decreto 267 en el cual se establece su rol como regulador de las comunicaciones con el fin de asegurar que todos los usuarios del país cuenten con servicios de calidad.
### Cual es el objetivo de la contratacion?
Se contactan con el objetivo de clarificar el contexto actual e historico de la conectividad a internet en el pais con los datos disponibles, con tres fines especificos:

+ **Accesos**: Democratizar el acceso a internet en el pais, para que los beneficios de las tecnologías de la información estén disponibles para todos los argentinos, potenciando las economías regionales. La intencion es generar politicas de incentivos de inversion a empresas dedicadas a la instalacion de fibra optica en ciudades, y en zonas rurales donde hay poco atractivo para una empresa privada, realizar obras publicas de instalacion de red wireless que requieren menos infraestructura y por lo tanto menos inversion (Ya se ha hecho en la provincia de San Luis, en la region de Cuyo, si bien no aporta gran 'velocidad' si soluciona el tema 'acceso')
+ **Velocidad**: Mejorar la velocidad de navegacion a nivel Nacional por medio de la inversion privada de fibra optica ya mencionada.
+ **Polo productivo-tecnologico:** Crear un polo productivo-tecnologico en Córdoba debido a su facil implementacion, ya que tiene una infraestructura de fibra optica desarrollada, se encuentra en el centro del país y ademas, tiene una gran cantidad de poblacion joven y con altas capacidades debido a sus universidades.Este polo productivo se desea con el fin de exportar conocimiento IT y favorecer el desarrollo e innovacion digital en la industria del pais, para asi mejorar la competitividad internacional de las mismas, lo cual seria una ayuda al faltante de divisas actual

### KPI'S para lograr dichos objetivos:

+ **Accesos:** En el caso de los accesos tenemos el archivo de penetracion de internet cada 100 hogares, con la informacion por fecha y provincia, ademas se utilizara a modo de complementacion de informacion el archivo con la cantidad de accesos por tecnologia en cada provincia de la nacion. Ademas se expone para completar la informacion y facilitar las decisiones, datos sobre la poblacion, habitantes, densidad de poblacion y sus salarios, para evaluar si conviene incentivar las obras de fibra optica o invertir en red wireless.
El kpi a utilizar: Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia. La fórmula es la siguiente:


    *Kpi acceso*= [( internet cada 100 hogares proximo - internet cada 100 hogares actual ) / internet cada 100 hogares actual ] * 100

+ **Velocidad:** Para medir la evolucion de la velocidad de la conectividad en las provincias se tiene el archivo de velocidades historicas, con el cual se verifica el cumplimiento del kpi, del cual se espera un crecimiento del 10% trimestral.

    *kpi velocidad* = [(velocidad siguiente trimestre - velocidad actual) / (velocidad actual)] * 100

+ **Polo productivo-tecnologico:**  El KPI utilizado van a ser los acceos a fibra optica en la ciudad de Cordoba. Se espera un crecimiento del 10% trimestral

    *kpi fibra* = [(accesos fibra siguiente trimestre - accesos fibra actual) / (accesos fibra actual)] * 100


## Trabajo realizado
### `EDA` 

Con los datos proporcionados por ENACOM, lo primero a hacer es un analisis exloratorio de los datos, eliminando nulos, corrigiendo datos, observando composicion de columnas, formatos, etc. Luego se procede a realizar graficos para empezaar a crear de a poco informacion y siguiendo con las correcciones que se creen necesarias. Finalmente se seleccionan los dataframes que se van a utilizar para el dashboard y kpis y se los exporta como csv desde visual studio code.

### `Dashboards y kpis` 

Se procede a hacer los graficos pertinentes para lograr la visualizacion de la informacion y los kpis finales. Para dicha tarea se utiliza el software PowerBi

## Contenido del repositorio:
+ *Readme:* Explicacion del trabajo
+ *DATA Power Bi:* Datasets utilizados en Power Bi
+ *DATA:* Los archivos en crudo a los cuales se les hace el EDA
+ *EDA datasets:* notebooks donde se realiza el EDA a los archivos de DATA. Los notebooks que inician con la frase no se usa, se les hizo un eda extensivo pero por no ser necesarios para el dashboards y kpis, no se utilizan los resultados de los mismos.
