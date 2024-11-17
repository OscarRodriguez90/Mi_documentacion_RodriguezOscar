# Mi_documentacion_RodriguezOscar

# 1.MARKDOWN

# Tipos de tamaño de encabezado
## Segundo nivel encabezado
### Tercer nivel encabezado
#### Cuarto nivel encabezado
##### Quinto nivel encabezado
###### Sexto nivel encabezado

## Como poner un texto en cursiva 

De esta manera se puede poner texto en *Cursiva* o de esta _tambien_ (utilizamos "_" o "*" al principio y al final del texto que queramos destacar)

## Como poner un texto en negrita

Se puede hacer de **esta** manera o __esta__. (utilizamos "**" o "__" al principio y al final del texto que queramos destacar)

 - Las etiquetas de **_markdown_** y html pueden anidarse

## Como hacer una lista ordenada 

1. Primer punto lista ordenada
    1. Primer elemento de la sublista odenada
    2. Segundo elemento de la sublista ordenada

## Como hacer una lista desordenada

2. Segundo punto de la lista
    * Primer elemento sublista desordenada
    - Segundo elemento sublista desordenada
    + Tercer elemento sublista desordenada


## Como mostrar codigo en repositorio

utilizamos ``` al principio y al final del codigo que queramos mostrar
``` html
Codigo random
<?xml version="1.0" encoding="utf-8"?>
<configuration>
  <configSections>
    <section name="ProdSettings" type="System.Configuration.NameValueSectionHandler"/>
    <section name="StagingSettings" type="System.Configuration.NameValueSectionHandler"/>
  </configSections>
  <ProdSettings>
    <add key="Installer" value="https://wcdownloadercdn.lavasoft.com/12.1.3.1037/WCInstaller.exe"/>
    <add key="WebProtectionZip" value="https://rt.webcompanion.com/notifications/download/rt/dci/latest/Webprotection.zip"/>
    <add key="InstallerZip" value="http://wcdownloadercdn.lavasoft.com/12.1.3.1037/WebCompanion-12.1.3.1037-prod.zip"/>
    <add key="WebInstallerZip" value="http://wcdownloadercdn.lavasoft.com/12.1.3.1037/webinstaller-12.1.3.1037-prod.zip"/>
  </ProdSettings>
  <StagingSettings>

```
## Como poner un link

#### Estructura

[Titulo_del_link]+(link_a_la_pagina_web "Titulo opcional")

#### Ejemplo

[Pagina_web_jesuites_bellvitge](https://srv.net.fje.edu/lg/AccesNetInfantil/#/LOGINNET "Titulo opcional")

## Como poner una imagen

1. Descargamos la imagen en nuestro repositorio
2. Guardamos cambio en el repositorio
3. Entramos al repositorio desde git hub y accedemos a la imagen, donde copiaremos la barra de direcciones del navegador
4. Aplicamos la siguiente Estructura

[Textoalternativo]+(https://github.com/OscarRodriguez90/AprendizajeMarkdown/blob/main/descarga.jpg "Titulo opcional")

#### Ejemplo

![Textoalternativo](https://github.com/OscarRodriguez90/AprendizajeMarkdown/blob/main/descarga.jpg "Titulo opcional")

## Como hacer una tabla 

|Titulo 1 | Titulo 2 | Titulo 3 |
|-----------|:-------------:|------------:|
|SMX2 |Curso 2324|25|
|ASIX1|Curso2425|32|

# 2.Como sincronizar en github

## Como clonar un repositorio

1. Primero, creamos un repositorio desde github
2. Copiamos la url del repositorio
3. Abrimos el cmd en la carpeta donde queremos clonarlo
4. Usamos el comando "git clone _url del repositorio_"

## Comandos basicos para sincronizar cambios en github

 - __git init__ Situarse en el repositorio desde la terminal
 - __git branch__ Ver la rama en la que estas trabajando
 - __git add .__ Agrega los cambios que deseas confirmar
 - __git commit -m "nombre del comit"__ confirma los cambios y agrega un comentario orientativo
 - __git push origin__ Envía tus cambios al repositorio remoto

# HTML 
## Apuntes HTML

## Historia HTML

HTML o HyperText Markup Language significa: 
- HyperText: Hipertexto, texto que enlaza con otros documentos.
- Markup: Marcar o etiquetar, base del funcionamiento de la web.
- Language: Lenguaje de las páginas web estandarizadas. No puede hacer bucles o condiciones.
HTML es el lenguaje más común para describir la estructura y presentación de una página web. Las etiquetas de HTML tienen una estructura de apertura y cierre.

## Introducción a elementos HTML

Partes:

- Etiqueta apertura: < p>
- Etiqueta de cierre: < /p>
- Contenido: lo que está dentro de las dos etiquetas
- Elemento completo: la combinación de las 3 cosas

## Introducción a Atributos HTML

Contenido adicional que no quieres que se vea en el documento. Class - nombre del atributo.

- Un espacio entre este y el nombre del elemento
- Nombre del atr seguido de un =
- Comillas de apertura y de cierre despues del =

Elementos dentro de otros → anidamiento
Elementos vacíos → no tienen etiqueta de cierre.

## Estructura básica de un fichero HTML

Tiene que tener una declaración DOCTYPE, un elemento < html> y un < head> < body> dentro. Head es para metadatos, hojas de estilo y scripts, el body es el contenido principal.

< link> href=””

- Sección < head >:
- Juego de caracteres, metainformación 
- Descripción de la pagina → aparecer en resultados de búsquedas
- Palabras claves → keywords
- Titulo de la pagina → < title></ title> es el título de tu página en la barra de búsquedas
- Icono de la página de favicon
- Enlace a otros ficheros→ hojas de estilo
- Codigo CSS → dar estilo

Head:

Introducir datos, información extra 

- width= device - width → ancho adaptable
- link rel =”icon” → poner icono pestaña

### Etiquetas SEO

OPEN GRAPH: etiquetas que creo facebook
- meta property = título …. imagen o ruta
- si no se encuentra se carga la etiqueta principal

Body: contenido que quieras mostrar, texto, imágenes, video, etc…

- Elementos bloque: contienen otros elementos de bloque, texto o elementos de línea, títulos, listas o tablas
- Elementos de línea: pequeños datos o texto. Hiperenlaces, imágenes citas… etc.

## Resumen Normas básicas etiquetas HTML

- Las etiquetas vienen en pares, apertura y cierre
- Etiquetas vacías, no etiqueta cierre
- Deben anidarse correctamente
- Atributos de etiquetas de apertura nombre = “texto”
- Recomendación: escribir todo en minuscula

## Organización de los archivos

- No tener archivos mezclados → caos

- Debemos organizar nuestra aplicación en directorios

- Crear directorio para los archivos, poner html y crear directorios para multimedia

- Archivo de inicio → index.html → usuario no tiene que escribir el nombre 

## Etiquetas básicas de HTML

- Enlaces (< a >): saltar de un documento a otro, href → donde ponermos el enlace
  - Enlaces a páginas externas
  - < p>< a href link title = > jesuites </ a></ p>

- Enlaces a páginas locales 
  - usamos ruta relativa con href
  - < a href= ruta/ruta

- Encabezados (h1 - h6): para hacer encabezados
  - Elementos de bloque

- Párrafos → p: para hacer parrados
  - elemento de bloque

- Salto de linea: br

- Separación linea: hr → poner linea horizontal

- Énfasis em → dar énfasis strong → dar más énfasis

- Contenedor en linea → span

- Listas de definición: formado término y definición
  - Definición lista "dl"
  - Definición term "dt"
  - Definition descripción "dd"

- Imagenes
  - "img" → no tiene cierre
  - src: saber donde esta la imagen ubicada. “media/logo”.

Dos tipos de rutas
- Ruta absoluta → ubicación completa comenzando desde dominio
  - Usar si imagen esta servidor externo
  - www.web.com/ruta/ruta.png

- Ruta relativa → ubicación desde el archivo actual
  - Facilita mantenimiento del sitio


- Enlaces a etiquetas dentro del HTML:
  - Puntos donde queremos ir → anclas. < h1 id=”seccion1”>... 
  - Enlazar ancla: < a href= #seccion1> …

## Elementos semánticos HTML 5

- Consigue describir el contenido dándole un significado de forma correcta
- Ejemplos: < header>< footer>< article>< section>< nav>< figure> → proporcionan inf sobre tipo contenido

## Formularios

- Interactuar con usuario y que nos transmita inf
- Tipos de control: campos de texto, contraseña, botones de opción, para introducir archivos. 
- Controles deben tener atributo name → identifica dato que se quiere enviar

## Etiquetas de formulario

- < Form > → crear formularios para que usuario envíe datos o haga acción en web
  - Atributos:
  - Action: url donde se enviaran los datos
  - method: metodo de envio datos
  - enctype: cómo se codifican datos antes de enviar al servidor, se usa cuando se suben archivos.
  - target: donde se debe mostrar la respuesta al enviar el formulario:
    - _self: la resp se carga en la misma ventana
    - _blank: resp en una nueva pestaña o ventana

- < input> → crear tipos campos interactivos
  - type: tipo de entrada que se debe mostrar
  - id: identificador único del campo, asociar < label > a campo entrada
  - name: nombre campo entrada, se utiliza para identificar dato
  - value: valor predeterminado del campo de entrado o valor enviado servidor si campo no interactivo
  - placeholder: texto que aparece cuando campo vacío
  - required: indica campo a contemplar antes enviar formulario
  - disabled: desactiva campo, para que  usuario no interactúe
  - readonly: campo sea solo de lectura, para usuario no modificarlo

- input type = radio → botón de opción (se agrupa con otros con mismo nombre)
- input type = checkbox → casilla verificación (permitir selecciones múltiples)

- button → crear botones interactivos en un formulario o web,
  - diferencia input → el contenido de < button > puede incluir texto, imágenes o HTML adicional
  - type: tipo de botón
  - submit: para enviar el formulario, por defecto
  - reset: restablece los campos a los valores iniciales. 
  - name: nombre del botón que será enviado con datos del formulario si tiene type=submit
  - value: especifica valor que se envía al servidor si el boton es submit
  - disabled: desactiva el botón, impidiendo su uso





	



