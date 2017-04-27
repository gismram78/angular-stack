# Implementando una aplicación con Angular 4

[https://pastebin.com/WuMw1BJQ](https://pastebin.com/WuMw1BJQ)

[https://github.com/angular/angular-cli](https://github.com/angular/angular-cli)

Ahora se permite hacer el Cross Platform, esto es:

* Progressive Web Apps:
* Native
* Desktop

Mejora la velocidad y performance, code eneration, universal, code shitting

Aumenta a productividad: mediante templates, Angular CLI, IDEs \(scatfolding\)

Herramientas propias para animación, accesibilidad \(discapacidades\), pruebas \(protractor\), documentacion,

Angular usa TS aunque no es obligatorio \(lenguaje tipado, es un super conjunto\)

TS es transpiler, traduce de un lenguaje a otro

Angular conoce componentes y viene mucho del concepto del desarrollo móvil. Es mas facil el mantto.

## Style  Guide

[https://angular.io/styleguide](https://angular.io/styleguide)

Esta guia es la buena y es apartir de angular 2. Angular 1 no tenia un style guide, varios hacian el suyo propio.

## Pasos

* Instalar Angular CLI: `npm install -g @angular/cli`
* Generar un proyecto: ng new myfirstproy o bien `ng new project --style=scss`
* Ejecutar: `ng set --global packageManager=yarn`
* Ir a la carpeta del proyecto
* Ejecutar: `ng serve`
* Abrir el navegador:  [http://localhost:4200/](http://localhost:4200/)

Componente esta compuesto por: markup, style, logic

@NgModule: pueden existir  todas las que queramos, porque no todos los modulos se necesitarían cargar al mismo tiempo, entonces se pueden separar por objetivos o logica de negocio o presentación.

package.json: es un archivo de convención, por el estandar de Node, ya que actualmente toda app moderna la incluye, y tiene una estructura estandarizada.

dependencies y devDependencies: con el primero se empaquetan las librerías a producción; el segundo son las dependencias de desarrollo.

Para tener varias versiones de node: `npm install -g n`

Para cambiar la versión con n: `n 4.4.2`

`n lts`   para instalar la ultima versión estable

`n latest`  para instalar la ultima de las ultimas

Otro tool para llamar REST services: Rest Angular

Referencia de librerias: [https://github.com/AngularClass/awesome-angular](https://github.com/AngularClass/awesome-angular)

Se deben declarar los modulos tanto en el componente padre \(module\) como el los hijos \(components\).

```
import { BrowserModule } from '@angular/platform-browser';
import { NgModule } from '@angular/core';
import { FormsModule } from '@angular/forms';
import { HttpModule } from '@angular/http';
import { RouterModule, Routes } from '@angular/router';

import { AppComponent } from './app.component';
import { appRoutes } from './app.routes';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    FormsModule,
    HttpModule,
    RouterModule.forRoot(appRoutes)
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }
```

Agregar nuevo componente desde Angular CLI dentro de app/: `ng g component home`

El directorio components/ es para los componentes individuales

Los demas se instalan en app/ fuera de components/

Lo anterior para seguir los guidelines de diseño de Angular.

Npm install bootstrap --save

  


Bootstrap 4

  


Dentro de angular cliente.json agregar bootstrap CSS

  


Angular no comprime imágenes

  


Ng build.   Esto crear la distribución del programa. Genera folder dist

  


Nativescript ionic para meter el distribuidor de angular

  


Carga de datos asíncrona

  


Lazy loading

