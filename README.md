## ALMACENAMIENTO DE DATOS EN AZURE

### Es de utilidad cuando 
- Se requiere crear una pagina web estatica, no es modificable (es una alternativa)
- Se almacenan archivos, mensajes, tablas que cuentan con seguridad, alta disponibilidad, duraderos y escalables
- Almacenamiento de cantidades masivas de datos

### Recursos de Azure
- Azure Disk Blobs
- Azure Disk Files
- Azure Disk Storage

**Crear recursos de almacenamiento de Blob Storage**

Ir al [portal de Azure](https://portal.azure.com/#home)
En el buscador del portal ---> **"Cuentas de almacenamiento"** y llenar los espacios que se requieren

![image text](I1s6.png)

![image text](I2s6.png)

![image text](I3s6.png)

Se habilita **"Data Lake Storage Gen2"** para almacenamiento de gran cantidad de datos

![image text](I4s6.png)

Se clickea el recurso, y una vez ahí se selecciona la opción **“contenedores”**

![image text](I5s6.png)

![image text](I6s6.png)

Ir al recurso

![image text](I7s6.png)

Cargar el archivo a almacenar

![image text](I8s6.png)

![image text](I9s6.png)

Haciendo click en los tres puntos de la esquina superior, seleccionar la opción de **"propiedades"** y copiar el enlace

![image text](I10s6.png)

Copiando en enlace y pegando en el buscador aparece la imagen cargada

![image text](I11s6.png)

**NOTA**: Todo lo que se suba es **descargable** o **ejecutable**

![image text](I12s6.png)

Habilitar

![image text](I13s6.png)

Regresar al sitio de contenedores

![image text](I14s6.png)

Click en cargar para poder subir el archivo

![image text](I15s6.png)

Continuar con la creacion de un File Storage

![image text](I16s6.png)

Crear e ir al recurso

![image text](I17s6.png)

![image text](I18s6.png)

Cargar archivo

![image text](I19s6.png)

Se puede conectar a una unidad de almacenamiento

![image text](I20s6.png)

**NOTA**: Active directory con cuenta de Inovaccion no esta permitido
Para ejecutar abrir ventana de Azure Powershell pegarlo y enter

![image text](I21s6.png)

Archivo conectado

![image text](I22s6.png)

***Agregar una carpeta para la seguridad de las aplicaciones, desde el navegador no es posible acceder.***

### Queue Storage

![image text](I23s6.png)

Crear cola de mensajes

![image text](I24s6.png)

Acceder al apartado

![image text](I25s6.png)

**NOTA**: Se pueden ir agregando o quitando mensajes con programacion. Los mensajes no son editables.

![image text](I26s6.png)

### Creacion de tablas

Ir al buscador

![image text](I27s6.png)

Crear una tabla

![image text](I28s6.png)

![image text](I29s6.png)

Para editarla

![image text](I30s6.png)

Hacer click en **"Tablas"** y apareceran las tablas que ya se han creado

![image text](I31s6.png)

Ir al recurso creado

![image text](I32s6.png)

Se agrega la entidad

![image text](I33s6.png)

Repetir

![image text](I35s6.png)

![image text](I36s6.png)

![image text](I37s6.png)

Desde la barra de al lado se puede consultar los recursos que se han creado

![image text](I38s6.png)

### Creacion de base de SQL 

Acceder [Github](https://github.com/) y copiar lo resaltado en azul

![image text](I39s6.png)

Pegar

![image text](40s6.png)

Lo que sucede es que se crea otro clon en el repositorio de azure

![image text](I41s6.png)

Teclear ls y a continuacion copiar el link de la siguiente carpeta

![image text](I42s6.png)

Dentro de lo que se creo hay una carpeta llamada sql

![image text](I43s6.png)

Ejecutar

![image text](I44s6.png)

![image text](I45s6.png)

Consultar la base de datos creada

![image text](I46s6.png)

Consultando la información general, se establece el firewall de servidor, lo cual permite la conexión desde algunas Ip’s y agregar tu Ip para poder realizar consultas de base de datos

![image text](I47s6.png)

![image text](I48s6.png)

Acceso para el servidor de bases de datos

![image text](I49s6.png)

Consultar los datos que hay dentro de la base de datos

![image text](I50s6.png)

Ejecutar

![image text](I51s6.png)

![image text](I52s6.png)

Para insertar un dato se puede hacer de la siguiente manera

![image text](I53s6.png)

Ejecutar y resulta lo siguiente

![image text](I54s6.png)

Ingresar a my [sql workbensh](https://www.mysql.com/products/workbench/) y hacer click en **test connection** para conectar

![image text](I55s6.png)

### Creacion de COSMOS DB

En el buscador de Azure introducir y seleccionar **“Azure Cosmos DB”** ---> **“crear”** con la opción recomendada. Se llenan los datos y a continuación **“revisar y crear”**

![image text](CC1s6.png)

A continuación, se selecciona el apartado de inicio rápido y se escoge un lenguaje de programación

![image text](CC2s6.png)

![image text](CC3s6.png)

Descarga de una aplicación para base de datos

![image text](CC4s6.png)

Para consumo

![image text](CC5s6.png)

Abrir el explorador de datos

![image text](CC6s6.png)

Generar un nuevo item

![image text](CC7s6.png)

![image text](CC8s6.png)

Hacer click en **"save"**

![image text](CC9s6.png)

Seleccionar

![image text](CC10s6.png)

Creación de más ítems (repetir lo anterior)

![image text](CC11s6.png)

Items creados

![image text](CC12s6.png)

![image text](CC13s6.png)

Se selecciona un item para obtener todos los datos y seleccionar **"Save Query"**

![image text](CC14s6.png)

![image text](CC15s6.png)

Especificar un nombre

![image text](CC16s6.png)

Ejecutar el Query para la obtención de resultados

![image text](CC17s6.png)
# Sesion6
