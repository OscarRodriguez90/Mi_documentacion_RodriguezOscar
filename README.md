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

### Como hacer una lista ordenada y desordenada

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

_[Titulo_del_link](link_a_la_pagina_web "Titulo opcional")_

#### Ejemplo

[Pagina_web_jesuites_bellvitge](https://srv.net.fje.edu/lg/AccesNetInfantil/#/LOGINNET "Titulo opcional")

## Como poner una imagen

1. Descargamos la imagen en nuestro repositorio
2. Guardamos cambio en el repositorio
3. Entramos al repositorio desde git hub y accedemos a la imagen, donde copiaremos la barra de direcciones del navegador
4. Aplicamos la siguiente Estructura

_![Textoalternativo](https://github.com/OscarRodriguez90/AprendizajeMarkdown/blob/main/descarga.jpg "Titulo opcional")_

#### Ejemplo

![Textoalternativo](https://github.com/OscarRodriguez90/AprendizajeMarkdown/blob/main/descarga.jpg "Titulo opcional")

## Como hacer una tabla 

|Titulo 1 | Titulo 2 | Titulo 3 |
|-----------|:-------------:|------------:|
|SMX2 |Curso 2324|25|
|ASIX1|Curso2425|32|



