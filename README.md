# Mi_documentacion_RodriguezOscar

# 1.MARKDOWN

Markdown es una forma simple y práctica de aplicar formato a textos sin necesidad de usar herramientas complejas. Su objetivo principal es facilitar la escritura y estructuración de contenido de manera clara y ordenada, permitiendo que cualquier persona pueda organizar información con facilidad utilizando una sintaxis muy intuitiva.

## Tipos de tamaño de encabezado

Según cuantos "#" añadamos antes del encabezado, tendremos diferentes niveles y tamaños. El rango esta entre 1 y 6.

# Primer nivel encabezado
## Segundo nivel encabezado
### Tercer nivel encabezado
#### Cuarto nivel encabezado
##### Quinto nivel encabezado
###### Sexto nivel encabezado

```
    # Primer nivel encabezado
    ## Segundo nivel encabezado
    ### Tercer nivel encabezado
    #### Cuarto nivel encabezado
    ##### Quinto nivel encabezado
    ###### Sexto nivel encabezado

``` 

## Como poner un texto en cursiva 

De esta manera se puede poner texto en *Cursiva* o de esta _tambien_ (utilizamos "_" o "*" al principio y al final del texto que queramos destacar)

```
    _cursiva_
```

## Como poner un texto en negrita

Se puede hacer de **esta** manera o __esta__. (utilizamos "**" o "__" al principio y al final del texto que queramos destacar)

```
    **negrita**
```
 - Las etiquetas de **_markdown_** y html pueden anidarse

```
    **_markdown_**
```


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
## Como poner un enlaces

Para enlazar una página web con un texto de nuestro repositorio tenemos que seguir esta estructura.

#### Estructura

```

[Titulo_del_link]+(link_a_la_pagina_web "Titulo opcional")

```

#### Ejemplo

[Pagina_web_jesuites_bellvitge](https://srv.net.fje.edu/lg/AccesNetInfantil/#/LOGINNET "Titulo opcional")

## Como poner una imagen

1. Descargamos la imagen en nuestro repositorio
2. Guardamos cambio en el repositorio
3. Entramos al repositorio desde git hub y accedemos a la imagen, donde copiaremos la barra de direcciones del navegador
4. Aplicamos la siguiente Estructura

```

  [Pagina web]+(ubicación de la imagen + "Titulo opcional")

```

#### Ejemplo

![Textoalternativo](https://github.com/OscarRodriguez90/AprendizajeMarkdown/blob/main/descarga.jpg "Titulo opcional")

## Como hacer una tabla 

Para realizar tablas tenemos que seguir esta estructura:
- La cantidad de "-" serà el espacio que queremos que ocupen cada columna de celdas
- Para orientar el texto hacia la derecha o la izquierda ponemos ":" en el extremo respectivo del lado.
- Si queremos que este centrado ponemos el caracter a ambos extremos de la columna

```

|Titulo 1 | Titulo 2 | Titulo 3 |
|:--------------|:----------------:|---------------:|
|SMX2 |Curso 2324|25|
|ASIX1|Curso2425|32|

```

|Titulo 1 | Titulo 2 | Titulo 3 |
|:--------------|:----------------:|---------------:|
|SMX2 |Curso 2324|25|
|ASIX1|Curso2425|32|

# 2.Github

# ¿Qué es GitHub?

**GitHub** es una plataforma basada en la web que permite alojar proyectos utilizando el sistema de control de versiones **Git**. Es ampliamente utilizada por desarrolladores y equipos para colaborar en el desarrollo de software de manera eficiente.

## Objetivos de GitHub

- Facilitar la **colaboración** entre desarrolladores.
- Gestionar el **control de versiones** de los proyectos.
- Permitir el **almacenamiento y organización** del código fuente.
- Proveer herramientas para la **revisión de código** y seguimiento de cambios.
- Fomentar el desarrollo de **proyectos de código abierto** y comunidades colaborativas.

## Repositorios 

Un repositorio como una caja fuerte para tu proyecto: guarda tu código, tus archivos, y cada paso que das. Puedes trabajar solo o compartirlo con otras personas. Además, puedes elegir si quieres que el mundo lo vea (público) o mantenerlo solo para ti o tu equipo (privado).

### Terminal con Git

Aquí tienes una lista desordenada pero útil de comandos básicos para moverte por Git sin parecer completamente perdido:

-**git remote add origin URL**: Enlaza tu proyecto local con un repositorio remoto (por ejemplo, uno que ya creaste en GitHub).
- **git push origin main**: Envía tus cambios al repositorio remoto. Es como decir "¡Listo, aquí va!" a GitHub.
- **git commit -m tu mensaje**: Guarda un punto de control con tus cambios. Es como un mini check-in con una nota que dice qué hiciste.
- **git add . o git add archivo.txt**: Marca archivos para ser guardados en el próximo commit. Puedes añadirlos todos o solo uno.
- **git branch -m nueva_rama**: Cambia el nombre de la rama actual, por si la llamaste "prueba3finaldef" y luego te arrepentiste.
- **git init**: Crea un repositorio en la carpeta actual. No hace magia, pero es el primer paso para empezar a usar Git.

### Crear un repositorio

1. Ve a [github.com](https://github.com)
2. Inicia sesión con tu cuenta (o créala si no tienes)

#### Paso 2: Crear Nuevo Repositorio
1. Haz click en "+" en la esquina superior derecha
2. Selecciona "New repository"

#### Paso 3: Configurar Repositorio
- **Repository name**: Nombre descriptivo (ej: "mi-proyecto")
- **Description**: Descripción opcional
- **Public/Private**: Elige si quieres que lo pueda ver todo el mundo o solo las personas con acceso.
- **Initialize this repository with:**
  - Add a README file (recomendado pero opcional)

#### Paso 4: Crear Repositorio
- Haz click en "Create repository"

#### Cómo Clonar un Repositorio de GitHub

Después de la creación, para poder trabajar localmente, tenemos que clonar el repositorio 

1. **Crear/Copiar Repositorio**
   - Si es nuevo: crear en GitHub
   - Si existe: copiar su URL

2. **Obtener URL del Repositorio**
   - En GitHub, haz click en "Code" (botón verde)
   - Copia la URL HTTPS (ej: `https://github.com/usuario/repositorio.git`)

3. **Abrir Terminal**
   - Navega a la carpeta destino con `cd ruta/de/la/carpeta`
   - Ejemplo: `cd ~/Documents/Proyectos`

4. **Comando Git Clone**
   ```bash
   git clone https://github.com/usuario/repositorio.git
   ```
 
# 3.HTML

### Introduccion a HTML

**HTML** (HyperText Markup Language) es un lenguaje de marcas utilizado para diseñar y estructurar páginas web. Su propósito principal es definir la organización del contenido mediante etiquetas, permitiendo a los navegadores interpretar y mostrar texto, imágenes, videos y otros elementos interactivos. Introducido en 1991 por **Tim Berners-Lee**, HTML ha evolucionado significativamente, convirtiéndose en un estándar esencial para el desarrollo web moderno, compatible con tecnologías como **CSS** y **JavaScript** para crear experiencias dinámicas y visualmente atractivas.


### - Estructura de un archivo HTML
Un documento **HTML** tiene una estructura básica que define cómo se organiza su contenido. Aquí tienes un ejemplo típico:

```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo HTML</title>
</head>
<body>
    <!-- Aquí va el contenido -->
</body>
</html>
```

**Descripción de las partes principales:**
1. `<!DOCTYPE html>`: Declara que el documento utiliza **HTML5**.
2. `<html>`: Es el contenedor principal de todo el contenido.
3. `<head>`: Incluye metadatos como el título, enlaces a estilos y scripts.
   - `<meta>`: Define información como el conjunto de caracteres.
   - `<title>`: Especifica el título que aparece en la pestaña del navegador.
4. `<body>`: Contiene el contenido visible de la página.

---

### - Etiquetas esenciales en HTML
Las etiquetas son los bloques básicos de **HTML**. Aquí tienes una lista de las más comunes y su propósito:

- Para títulos y subtítulos, se usan etiquetas como `<h1>` hasta `<h6>`. `<h1>` es el más grande y `<h6>` el más pequeño.
- Los párrafos se definen con `<p>`.
- Para resaltar texto en **negrita**, se utiliza `<strong>`.
- Para texto en *cursiva*, se emplea `<em>`.
- Si necesitas subrayar algo, usa `<u>`.
- Para insertar un salto de línea, utiliza `<br>`.
- Para separar contenido con una línea horizontal, usa `<hr>`.

---

### - Cómo trabajar con rutas en HTML
Cuando necesitas referenciar recursos como imágenes o archivos, puedes usar dos tipos de rutas:

1. **Ruta Absoluta**: Especifica la ubicación completa del recurso, como un enlace externo.
2. **Ruta Relativa**: Indica la ubicación del recurso en relación con el archivo actual.

Ejemplo práctico de una imagen con ruta relativa:
```
<img src="./imagenes/ejemplo.jpg" alt="Descripción de la imagen" width="300" height="200">
```

---

### - Formularios en HTML
Los formularios son una herramienta clave para interactuar con los usuarios. Se crean con la etiqueta `<form>` y pueden incluir campos de entrada, botones y más.

Ejemplo de un formulario básico:
```
<form action="/submit" method="POST">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" placeholder="Escribe tu nombre">
    <br>
    <label for="email">Correo:</label>
    <input type="email" id="email" name="email" placeholder="Escribe tu correo">
    <br>
    <button type="submit">Enviar</button>
</form>
```

**Elementos importantes en un formulario:**
- `<input>`: Define campos de entrada como texto, correo, contraseñas, etc.
- `<label>`: Asocia un texto descriptivo a un campo de entrada.
- `<button>`: Botón para enviar el formulario.

---

### - Elementos semánticos en HTML5
Con **HTML5**, se introdujeron elementos semánticos que mejoran la organización del contenido. Algunos ejemplos son:

- `<header>`: Define el encabezado de una página o sección.
- `<footer>`: Representa el pie de página.
- `<article>`: Contenido independiente, como un artículo o publicación.
- `<section>`: Agrupa contenido relacionado.
- `<nav>`: Contiene enlaces de navegación.
- `<figure>`: Agrupa contenido gráfico, como imágenes o diagramas.

---

### - Validación de HTML
Es importante asegurarse de que tu código **HTML** cumple con los estándares. Para ello, puedes usar herramientas como el **Validador HTML** del **W3C**, que analiza tu documento y te informa de errores o advertencias.

Accede al validador aquí: [Validador HTML](https://validator.w3.org/)

--- 

### - Listas y contenido estructurado
En **HTML**, puedes organizar contenido en listas. Aquí tienes cómo hacerlo:

1. **Listas ordenadas**: Se crean con `<ol>` y cada elemento se define con `<li>`.
   ```
   <ol>
       <li>Primer elemento</li>
       <li>Segundo elemento</li>
   </ol>
   ```

2. **Listas desordenadas**: Se crean con `<ul>` y también usan `<li>` para los elementos.
   ```
   <ul>
       <li>Elemento A</li>
       <li>Elemento B</li>
   </ul>
   ```

---

### - Enlaces e imágenes
Para enlazar páginas o recursos, se usa la etiqueta `<a>`:
```
<a href="https://www.ejemplo.com">Visita Ejemplo</a>
```

Para insertar imágenes, se utiliza `<img>`:
```
<img src="imagen.jpg" alt="Descripción de la imagen">
```

# 4.CSS

### ¿Qué es CSS?

**CSS** (Cascading Style Sheets) es un lenguaje de diseño utilizado para controlar la apariencia y el formato de un documento HTML. Mientras que **HTML** define la estructura del contenido, **CSS** se encarga de estilizarlo, permitiendo personalizar colores, fuentes, tamaños, márgenes, posiciones y otros aspectos visuales de una página web.

### ¿Para qué sirve CSS?

CSS permite separar el contenido (HTML) de la presentación (estilo), lo que facilita el mantenimiento y la reutilización del código. Algunas de sus principales funciones son:

- **Estilizar texto**: Cambiar colores, fuentes, tamaños y alineaciones.
- **Diseñar layouts**: Crear estructuras de página con columnas, filas y secciones.
- **Controlar el espacio**: Ajustar márgenes, rellenos y bordes.
- **Adaptar el diseño**: Crear páginas responsivas que se ajusten a diferentes dispositivos y tamaños de pantalla.
- **Animaciones**: Agregar transiciones y efectos visuales dinámicos.


### Cómo incluir CSS en un proyecto

Existen tres formas principales de aplicar CSS a un documento HTML:

1. **CSS en línea**: Se aplica directamente en el atributo `style` de una etiqueta HTML.
   ```html
   <p style="color: blue; font-size: 16px;">Texto en azul</p>
   ```

2. **CSS interno**: Se incluye dentro de una etiqueta `<style>` en el `<head>` del documento HTML.
   ```html
   <head>
       <style>
           p {
               color: blue;
               font-size: 16px;
           }
       </style>
   </head>
   ```

3. **CSS externo**: Se utiliza un archivo `.css` separado que se enlaza al documento HTML mediante la etiqueta `<link>`.
   ```html
   <head>
       <link rel="stylesheet" href="styles.css">
   </head>
   ```


### Selectores en CSS

Los selectores son una parte fundamental de CSS, ya que permiten aplicar estilos a elementos específicos de un documento HTML. Algunos de los selectores más comunes son:

- **Selector de etiqueta**: Aplica estilos a todas las etiquetas de un tipo específico.
  ```css
  p {
      color: red;
  }
  ```

- **Selector de clase**: Aplica estilos a elementos con una clase específica (se define con un punto `.`).
  ```css
  .mi-clase {
      font-size: 18px;
  }
  ```

- **Selector de ID**: Aplica estilos a un elemento con un ID único (se define con un `#`).
  ```css
  #mi-id {
      background-color: yellow;
  }
  ```

- **Selector universal**: Aplica estilos a todos los elementos.
  ```css
  * {
      margin: 0;
      padding: 0;
  }
  ```

---

### Propiedades comunes en CSS

CSS cuenta con una amplia variedad de propiedades para personalizar el diseño de una página. Algunas de las más utilizadas son:

- **Color y fondo**:
  ```css
  color: red; /* Cambia el color del texto */
  background-color: lightblue; /* Cambia el color de fondo */
  ```

- **Texto**:
  ```css
  font-size: 16px; /* Tamaño de la fuente */
  font-family: Arial, sans-serif; /* Tipo de fuente */
  text-align: center; /* Alinear el texto */
  ```

- **Espacio**:
  ```css
  margin: 10px; /* Espacio exterior */
  padding: 15px; /* Espacio interior */
  ```

- **Bordes**:
  ```css
  border: 2px solid black; /* Borde */
  border-radius: 10px; /* Bordes redondeados */
  ```

### - Ejemplo práctico de CSS

Archivo HTML:
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 class="titulo">Bienvenido a mi página</h1>
    <p id="descripcion">Este es un ejemplo de CSS externo.</p>
</body>
</html>
```

Archivo CSS (`styles.css`):
```css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
}

.titulo {
    color: blue;
    text-align: center;
}

#descripcion {
    color: gray;
    font-size: 18px;
    text-align: justify;
}
```

### Flexbox

**Flexbox** (Flexible Box Layout) es un modelo de diseño en CSS que permite distribuir y alinear elementos dentro de un contenedor de manera eficiente, incluso cuando sus tamaños son dinámicos o desconocidos. Es ideal para crear layouts flexibles y responsive.

#### Propiedades principales de Flexbox

1. **Propiedades del contenedor flex**:
   - `display: flex;`: Activa el modelo de Flexbox en un contenedor.
   - `flex-direction`: Define la dirección de los elementos dentro del contenedor.
     - Valores: `row` (por defecto), `row-reverse`, `column`, `column-reverse`.
   - `justify-content`: Alinea los elementos horizontalmente.
     - Valores: `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`.
   - `align-items`: Alinea los elementos verticalmente.
     - Valores: `stretch` (por defecto), `flex-start`, `flex-end`, `center`, `baseline`.
   - `flex-wrap`: Permite que los elementos se ajusten a una nueva línea si no caben en una sola.
     - Valores: `nowrap` (por defecto), `wrap`, `wrap-reverse`.

2. **Propiedades de los elementos flex**:
   - `flex`: Es una propiedad abreviada que combina `flex-grow`, `flex-shrink` y `flex-basis`.
   - `align-self`: Permite alinear un elemento individual de manera diferente al resto.
     - Valores: `auto`, `flex-start`, `flex-end`, `center`, `baseline`, `stretch`.
   - `order`: Cambia el orden visual de los elementos (por defecto es `0`).

#### Ejemplo básico de Flexbox

HTML:
```html
<div class="flex-container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
</div>
```

CSS:
```css
.flex-container {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    height: 200px;
    background-color: #f0f0f0;
}

.item {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
    border: 1px solid #ddd;
}
```

Resultado: Los elementos estarán distribuidos horizontalmente con espacio alrededor y alineados verticalmente al centro del contenedor.

---

### Responsive Design

El diseño responsivo permite que una página web se adapte a diferentes tamaños de pantalla y dispositivos, mejorando la experiencia del usuario. Es un enfoque esencial en el desarrollo web moderno.

#### Herramientas clave para diseño responsivo

1. **Media Queries**:
   Las media queries permiten aplicar estilos específicos según el tamaño de la pantalla o el dispositivo.
   ```css
   @media (max-width: 768px) {
       body {
           font-size: 14px;
           background-color: #f9f9f9;
       }
   }

   @media (min-width: 769px) and (max-width: 1024px) {
       body {
           font-size: 16px;
           background-color: #e0e0e0;
       }
   }
   ```

2. **Unidades relativas**:
   Usar unidades como `%`, `em`, `rem`, `vw` (viewport width) y `vh` (viewport height) en lugar de valores fijos para que los elementos se ajusten dinámicamente.
   ```css
   .container {
       width: 80%; /* Ancho relativo al contenedor padre */
       padding: 2em; /* Espaciado relativo al tamaño de la fuente */
   }
   ```

3. **Imágenes responsive**:
   Las imágenes pueden ajustarse automáticamente al tamaño del contenedor utilizando `max-width`.
   ```css
   img {
       max-width: 100%;
       height: auto;
   }
   ```

4. **Flexbox y Grid**:
   Estas herramientas son fundamentales para crear layouts adaptables. Por ejemplo, con Flexbox:
   ```css
   .flex-container {
       display: flex;
       flex-wrap: wrap;
   }
   ```

#### Ejemplo práctico de diseño responsive

HTML:
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diseño Responsivo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">Encabezado</header>
    <main class="main">
        <section class="content">Contenido principal</section>
        <aside class="sidebar">Barra lateral</aside>
    </main>
    <footer class="footer">Pie de página</footer>
</body>
</html>
```

CSS:
```css
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

.header, .footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

.main {
    display: flex;
    flex-wrap: wrap;
}

.content {
    flex: 3;
    background-color: #f4f4f4;
    padding: 20px;
}

.sidebar {
    flex: 1;
    background-color: #ddd;
    padding: 20px;
}

@media (max-width: 768px) {
    .main {
        flex-direction: column;
    }

    .content, .sidebar {
        flex: 1;
    }
}
```

Resultado: En pantallas grandes, el contenido principal y la barra lateral estarán en una disposición horizontal. En pantallas pequeñas, se reorganizarán en una disposición vertical.

# 5.XML

### - ¿Qué es XML?

**XML** (eXtensible Markup Language) es un lenguaje de marcas diseñado para almacenar y transportar datos de manera estructurada y legible tanto para humanos como para máquinas. A diferencia de **HTML**, XML no está enfocado en la presentación de datos, sino en su organización y descripción.



### - Características principales de XML

1. **Estructura jerárquica**: Los datos se organizan en una estructura de árbol con elementos anidados.
2. **Extensible**: Permite definir etiquetas personalizadas según las necesidades del usuario.
3. **Legible**: Es fácil de leer y entender tanto para humanos como para programas.
4. **Independiente de la plataforma**: Puede ser utilizado en diferentes sistemas y aplicaciones.
5. **Interoperabilidad**: Facilita el intercambio de datos entre sistemas heterogéneos.

### - Ventajas de XML

- **Portabilidad**: Es independiente de la plataforma y el software.
- **Flexibilidad**: Permite definir etiquetas personalizadas.
- **Intercambio de datos**: Es ideal para compartir información entre sistemas diferentes.
- **Legibilidad**: Es fácil de entender para humanos y máquinas.

