# Angular 2 Getting Started

[https://app.pluralsight.com/library/courses/angular-2-getting-started-update/table-of-contents](https://app.pluralsight.com/library/courses/angular-2-getting-started-update/table-of-contents)

Why Angular?

* Expressive HTML
* Powerful Data Binding
* Modular By Design
* Built-in Backend Integration

Why Angular and not AngularJS?

* Build  for Speed \(initial loads, change detection, rendering times\)
* Modern \(latest Javascript standards, classes, modules,  decorators, support to Greenfield and Legacy browsers\)
* Simplified API \(fewer built-in directives, simpler bindings,  less things to learn\)
* Enhances productivity

## Anatomy of Angular Application

An **application** is a composition of components and services which operate along them.![](/assets/1import.png)

The **component** is conformed of these modules.

* Template: HTML fragment to define the view
* Class: Associated to the view, it contains methods and properties
* Metadata: Additional information to identify the class as an Angular component.![](/assets/2import.png)

Now the form to organize and put all these components together is:

* **Angular modules** to organize application into cohesive blocks of functionality
* Every Angular application has at least one Angular module called application's **root Angular module**
* Every Angular application has one or more **feature Angular modules** focus on an specific application feature. 

![](/assets/3import.png)

A sample Product Management application could be composed of the next components:

## ![](/assets/5import.png)

## First Things to Do

### Selecting Language

* Javascript Language Specification
  * ECMAScript \(ES\)
  * ES 3 \(for old browsers\)
  * ES 5 \(for most modern browsers, no compile require\)
  * ES 2015 o ES 6 \(latest release but not many browsers support it yet, so the transpilers are in the rescue, compile require, new powerful features\)
* Typescript
  * Superset of Javascript
  * String typing
  * Great IDE tooling \(inline documentation, syntax checking, code navigation, advanced refactorings\)
  * Typescript was used to build Angular 2
  * Opensource
  * Typescript type definition  files \(\*.d.ts\)
  * Class-based object-orientation
* Dart
  * Non Javascript

### Selecting Editor

* Visual Studio
* Visual Studio Code
  * Support Typescript
  * Runs in any OS
  * [https://code.visualstudio.com/](https://code.visualstudio.com/)
* WebStorm
* Atom
* Eclipse
* Sublime
* Others

### Setting Up the Environment

* Installing npm 3 and later
  * Node Package Manager
* * Package Manager for Javascript
  * Install libraries, applications and packages
  * [https://www.npmjs.com](https://www.npmjs.com)
* Setting Up Angular application
  * 
* ## References

[https://github.com/DeborahK/Angular-GettingStarted](https://github.com/DeborahK/Angular-GettingStarted)

[https://github.com/DeborahK](https://github.com/DeborahK)

[http://www.typescriptlang.org/Playground/](http://www.typescriptlang.org/Playground/)

