# Shoperti Bold Theme
> Este es el tema utilizado en [Bold] (https://bold-theme.shoperti.com/) y puede servirte de inspiración. Puede usar este tema cómo base para crear uno nuevo o realizar ajustes pequeños y modificaciones. Sin duda, puede ser el punto de partida para aprender a construir tus propios temas.
>
> ** Para más detalles sobre el desarrollo del tema, lee nuestra [Documentación del tema] (https://github.com/Shoperti-Themes/Bold) **.

## Obteniendo este tema
1. <a href="https://github.com/Shoperti-Themes/Bold/archive/master.zip"> Descargar </a> la última versión y rama master.
2. También puedes clonar el reporte git: <code>git clone git@github.com:Shoperti-Themes/Bold.git</code>

![alt text](https://raw.githubusercontent.com/Shoperti-Themes/Bold/master/screenshot.png "Screeshot")


## Implementación manual
La opción más sencilla si no desea realizar cambios en el tema es cargar el archivo [theme.zip] (dist/theme.zip) encontrado dentro de la carpeta 'dist' una vez descargado el paquete completo.

**Puede realizar cualquier cambio directamente descomprimiendo el archivo zip, sin embargo no es recomendable porque puede dañar alguna parte del código**

## Personalizando el tema

Para facilitar aún más el desarrollo y la implementación del tema, puede utilizar las herramientas para construcción con Webpack incluídas.

Estas tareas toman el código fuente del tema y empaquetan en un zip para ser instalado.

### Instalando Node

Es indispensable contar con NodeJs instalado. Para saber si cuenta con él, vaya a su terminal y escriba <code>node -v</code> y podrá ver algo así <code>v6.9.1</code> si ya lo tiene instalado. En caso contrario vaya a la página de [Node] (https://nodejs.org/download/) 

1. Navegue hasta la raíz de este proyecto de tema descargado
2. Ejecute `npm install`.

Npm examinará [package.json] (package.json) e instalará automáticamente las dependencias locales necesarias que se encuentren allí.

** ¿Qué es `npm`? Npm significa [node packaged modules] (http://npmjs.org/) y es una forma de administrar dependencias de desarrollo a través de NodeJs.


### Implementación del tema

Pending

* Pending ` mi-página`. *

### Tareas de Webpack
Cada ves que corra alguno de los comandos desde su terminal, Webpack realizará varias acciones, cómo compilar sus estilos Sass, Javascript o empaquetar los archivos.
Si quiere saber más sobre [Webpack 2](https://webpack.js.org/)

* <code>npm run dev</code>
* <code>npm run prod</code>
* <code>npm run test</code>
* <code>npm run serve</code>

#### Instalación

Pending docs.

* Pending

## Versionado
Para mayor transparencia y comprensión de nuestro ciclo de lanzamiento, y para tratar de mantener la compatibilidad con versiones anteriores, este proyecto se mantendrá en la medida de lo posible bajo las directrices de Versión Semántica.

`<Major>. <Minor>. <Patch>`

* `MAJOR` versión al realizar cambios incompatibles,
* `MINOR` cuando se agregue una funcionalidad de una manera que siga siendo compatible con versiones anteriores.
* `PATCH` cuando se corrijan errores compatibles con versiones anteriores.

Para obtener más información sobre [SemVer] (http://semver.org/lang/es/).


## Copyright

&copy; Copyright Shoperti 2017 - Ver [TÉRMINOS Y CONDICIONES](https://www.shoperti.com/terminos-y-condiciones) para más detalles.