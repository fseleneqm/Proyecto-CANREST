# Proyecto-CANREST

Repositorio del grupo 7 de 2º DAW para el proyecto de la asignatura de Diseño de Interfaces Web.


## Requisitos
1. Diseñar la estructura html semántica de la web que se había planteado previamente en la guía de estilo y boceto.
Pautas:
  - El **fichero css** debe estar linkado al fichero html, no puede haber código css incrustado en el html.
  - El **fichero html** debe tener las etiquetas semánticas: _header, nav, section, article, aside, footer_, también pueden usar _main_ si lo desean.
    - **No pueden haber div**, ya que no es una etiqueta semántica.
    - No abusar del uso de Span, solo si es necesario para dar formato al texto.
    - Un section puede estar formado por distintos sections y article pero **un article no puede estar formado por section**.
  - En el _nav_ estaría el **menú principal de la web** y **debería estar formado por una lista ol ó ul con cada uno de sus items li**. A su vez, un **elemento li puede tener una lista anidada dentro ol ó ul**, éste sería el **submenu**. **No debe haber más de 3 niveles de profundidad en un menú**.
    - Cada uno de esos items puede ser un section que queremos cargar en la pantalla principal al seleccionarlo, para ello **usamos la # seguido del id**. Así conseguimos cargar ese section en concreto en la página principal debajo del menú.
  - El **logotipo** representa la imagen y finalidad de la empresa, a parte de ser un elemento de identificación porque identifica la empresa también lo es de navegación, porque **pulsando en él nos lleva normalmente a la página home de la empresa**.
  - **Etiquetas**:
      - Se tiene que hacer uso de las **etiquetas semánticas** como contenedores de la página web y todo su contenido dentro de ellas: header, nav, section, aside, article, footer
      - Tiene que contener:
        -  Un menú.
        -  Párrafos.
        -  Enlaces.
        -  Formularios.
        -  Imágenes.
        -  Vídeos.
        -  Audios.
        -  Contenido interactivo.
        -  Apartado de contacto con ubicación de google maps.
        -  Derechos de autor o licencias de divulgación.

- **Accesibilidad**: tiene que cumplir con los estándares de accesibilidad web, se tiene que testear una vez finalizado el proyecto con una herramienta de accesibilidad web y mostrar los resultados.
- **Usabilidad web**: tiene que cumplir con los principios de usabilidad web. El día de la presentación del proyecto se testeará por el resto de compañeros su usabilidad. 
