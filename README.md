# Lyft

* **Track:** _Common Core_
* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Maquetado web con HTML & CSS_

***

Para completar este reto, hemos creado este repositorio boilerplate (plantilla
inicial) con todos los recursos que necesitas. Esto incluye imágenes y
estructura de carpetas y archivos donde colocarás tu código.

## Flujo de trabajo

1. Debes realizar un [**fork**](https://gist.github.com/ivandevp/1de47ae69a5e139a6622d78c882e1f74)
   de este repositorio.

2. Luego deberás **clonar** tu fork en tu máquina. Recuerda que el comando a usar
   es `git clone` y su estructura normalmente se ve así:

   ```bash
   git clone https://github.com/<nombre-de-usuario>/lyft.git
   ```

## Objetivo

El reto consiste en replicar el sitio de **Lyft**, este será el resultado
a lograr:

![Lyft Website](docs/fullpage.png)

## Consideraciones

* Encontrarás un archivo base `index.html` en el cual deberás escribir la
  estructura de tu proyecto y enlazar tus archivos de estilos (CSS).

* En la carpeta `css` tendrás un archivo base `main.css` donde agregarás los
  estilos necesarios para tu proyecto:

* Dentro de la carpeta `assets` se encuentra la carpeta `images` donde
  encontrarás todas las imágenes necesarias para completar tu proyecto.

* Deberás **actualizar el archivo `README.md`** explicando el contenido de tu
  repositorio.

* Esta web utiliza la tipografía `Montserrat`.

* La paleta de colores puedes obtenerla inspeccionado el sitio original, pero
  para ganar tiempo, puedes usar los siguientes:

  - Botones, hover: `#FF00BF`
  - Fondo de `footer`: `#333447`
  - Título del formulario: `#352384`
  - Texto del formulario: `#728099`
  - Gradiente morado: `linear-gradient(#76278F, #2B1E66);`

* Para el footer, deberás tomar en cuenta que tiene un hover y se ve como en la
  siguiente imagen:

  ![Lyft - Footer](docs/footer.gif)

  Además, los íconos deberás obtenerlo de `Icomoon`.

* Para este reto, encontrarás ciertas cosas que probablemente aun no has visto
  en clase (formularios, videos de Youtube). No te preocupes, estamos seguros
  que los afrontarás con éxito, de igual forma aquí unos tips:

  - Estos son los videos de Youtube:
    * https://www.youtube.com/watch?v=fLSmUWOYpKw
    * https://www.youtube.com/watch?v=V7j8Aqxmbs8
    * https://www.youtube.com/watch?v=xj2VWLV0xCU
  - Para agregar los videos, averigua sobre la etiqueta `iframe`.
  - Para el formulario, revisa las etiquetas como `form` e `input`.

* Puedes ver el [sitio original](https://www.lyft.com/), sin embargo, su diseño
  ya ha cambiado en ciertas partes, así que tu fuente de verdad es la imagen que
  muestra el objetivo de este reto.

  > Nota: El sitio original tiene ciertos efectos y funcionalidades que
están fuera del alcance de este reto. Enfócate en obtener la maquetación
lo más parecido posible, usando lo aprendido en clase ;)

## A tener en cuenta

Este reto será evaluado sobre lo siguiente:

* Pixel perfect (replicar el diseño con exactitud)
* Estructura de carpetas y archivos
* Nombramiento de clases, id, etc
* Indentación
* Archivo `README.md` actualizado y correctamente redactado
* Uso de comentarios para hacer tu código más legible


## Desarrollo pagina de Lytft
  - Estructura HTML:
* Utilizacion de la etiqueta <header> para crear un menu el cual contiene los elementos del encabezado y logo.
* Con la etiqueta <nav> cree el menu de navegacion, dentro de el agrege la etiqueta <a>  para generar vínculos de hipertexto para enlazar con ellos todos los  documentos de la web.En este caso las partes del menu(Drive, Explore, Help, Login).
* Luego por medio de la etiqueta <form> cree un formulario.
* Luego cree  2 <section> para poder separa las partes del contenido de la  web,su funcion es estructurar semánticamente un documento.Y poder tener un order al poder estructurarla y dar diversos estilos segun los requerimientos.
* Etiqueta <iframe>inserta una ventana en la que podemos ver el contenido de otra página, en este caso los videos de youtube, sin tener que salir de la pagina de lyft.
*  Por ultimo cree la etiqueta <footer> que representa el pie de un documento o sección. La información que se añade en este bloque corresponde al autor del documento, enlaces a contenido relacionados, información de copyright, avisos legales, etc.
   - Class:
   * Para poder dar estilos y cambiar estructuras con css use una serie de class para poder llevar a cabo el proyecto.
   * "background":La cual utilice para poder poner la imagen de fondo en el <header>.
   * "wrapper":Esta clase me permito encerrar una gran parte de contenidos de la pagina mas especificamente del menu de navegacion, y poder definir las carcteristicas basicas de la pagina: como su anchura, sus bordes,si se centra o no respecto de la ventana del navegador.
   * "container":La utilice para que la pagina web aparezca centrada y con un ancho fijo.
   * "signup":Esta clase esta dentro de la etiqueta form para poder darle estructura al formulario.
   * "form-btn":A traves de esta clase pude ajustar el tamaño del botton definir su fuente, estilos, etc, ademas de poner el color backround corresponiente par poder usar la seudoclase :hover al pasar el mouse sobre ella.
   * "phone": A traves de esta clase pude ajustar las dimensiones de la imagen phone.
   * "text-left": La utilice para poder ajustar el texto en relacion al la imagen del telefono de la <section class="phone">.
    * "text": Esta clase tiene como funcion darle estructura al texto que esta al lado del video.
    * "title": Para poder centrar los parrafos.
    * "info": La utilice para poder ajustar el parrafo mas extenso.
    * "video1","video2","video3": La utlice para poder ajustar las dimensiones del video, y su relacion con respecto al texto.
    