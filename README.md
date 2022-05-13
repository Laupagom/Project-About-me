# **Project Alpha**
Frontend design project. Design and development of my personal website.

## **Objetivo**
Creación de un sitio web sobre mi experiencia profesional y aptitudes.

## **Programas utilizados**
El proyecto se ha construido con los siguientes programas:
- Para el diseño: 
  - <a href="https://www.figma.com/">Figma</a>: diseño de wireframes.
- Para el desarrollo: 
  - <a href="https://code.visualstudio.com/">Visual Studio Code</a>: editor de código fuente.
  - <a href="https://prepros.io/">Prepos</a>: compilador de archivos.

## **Nomenclatura**

### **Clases**

La convención de nombre para las clases de los elementos sigue el patrón BEM:

- .bloque{}
- .bloque__elemento{}
- .bloque--modificador{}

'.bloque' representa el primer nivel de una abstracción o componente, es el elemento padre.
'.bloque__elemento' representa un hijo del elemento padre '.bloque'.
'.bloque--modificador' representa un estado diferente de '.bloque'.


## **SCSS**

Los archivos scss son los encargados de aportar los estilos necesarios a los elementos html, estos se encuentran organizados en la carpeta sass/.

### **Estructura del repositorio scss/**

- sass/
  - atmosphere/
    - _typography.scss
  - components/
    - _animation.scss
    - _arrow.scss
    - _avatar.scss
    - _circle.scss
    - _divider.scss
    - _parallax-skills.scss
    - _scroll-animation.scss
    - _symbol.scss
  - htmlelements/
    - _buttons.scss
    - _form.scss
  - layout/
    - copyright.scss
    - _footer.scss
    - _grid.scss
    - _manu.scss
  - settings/
    - _mixinis.scss
    - _site.scss
    - _space.scss
    - _variables.scss
  - utilities/img
  - style.scss


### **Variables**

Las variables que se emplearán en este proyecto se encuentra en el archivo sass/settings/_variables.scss. Estas variables globales definen los colores, el espaciado y las tipografías de todo el documento.



