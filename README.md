# Proyecto Hospital-Frontend
En este proyecto he diseñado el frontend para la aplicacion de un hospital llamado **Hospital Primeros Pasos**

## Tecnologías usadas

- CSS       (/Prescripciones)
- Tailwind  (/Urgencias)
- Sass      (/Enfermeria-sass-vite)

### Explicacion rápida

#### _CSS_
Al abrir el archivo _**.html**_, carga main.css, que tiene importado los diferentes módulos, lo que ayuda a la escalabilidad a futuro

#### _Tailwind_
Funciona diferente a css. En lugar de tener una(s) hoja(s) de estilo(s), simplemente usas:

``` html
    <script src="https://cdn.tailwindcss.com"></script>
```
para hacer uso de una sintaxis de estilos mejorada directamente en el _**.html**_.

De lo que he probado, es ideal para proyectos rápidos y simples. Muy cómoda de usar y cualquiera en un par de horas ya es capaz de usarla correctamente pero quizas no es lo más correctos para proyectos en gran escala.

#### _Sass_
Es un preprocesador de CSS. Sirve como una extensión de css normal que permite hacer uso de variables, funciones y anidamiento (ahora ya no pero antes no existian las variables en css).

Más complejo de usar que los dos anteriores pero el mejor para proyectos a gran descala.
Simplifica mucho el codigo y ahorra mucha repetición de colores, fuentes de texto y cosas varias.


>En los anteriores con abrir el archivo y tener todo bien enlazado era suficiente pero sass necesita compilarse antes de que se ejecute.
>Se puede usar tanto vite como en mi caso y seguir las intrucciones de abajo o, teniendo sass instalado hacer:
``` bash
sass "direccion/de/sass" "direccion/de/sass" --watch
```
El _**--watch**_ es lo que hace que, cuando detecte algun cambio, se actualice automáticamente sin tener que recargar la página.

## Requisitos

- Tener instalado:
  - Node.js
  - npm (incluido con Node.js)

## Cómo iniciar el proyecto

1. Abrir una terminal.
2. Entrar a la carpeta del proyecto:

```bash
cd enfermeria-sass-vite
```

3. Iniciar el servidor de desarrollo:

```bash
npm run dev
```

4. Abrir el navegador en:

```txt
http://localhost:5173
```

