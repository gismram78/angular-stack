# Introduction to Components

## What is a Component?

![](/assets/22import.png)

## Creating the Component Class

Naming Suffix: Component

Root Module: AppComponent

Defining attributes \(camelCase\), datatypes and default values

```
export class AppComponent {
    pageTitle: string = "Hola";
}
```

## Defining the Metadata with a Decorator

Decorator: a function that adds metadata to a class, its members, its members attributes.

Prefixed with an @

Angular built-in decorators:

@Component\(\)

    @Component({
        selector: 'pm-root',
        template: `
        <div><h1> {{pageTitle}} </h1>
            <div>Primer Component</div>
        </div>
        `
    })
    export class AppComponent {
        pageTitle: string = "Hola g";
    }

## Importing What We Need

It is a ES 2015

`import`statement

Import from a third-party library, our own ES modules or from Angular.

Angular is modular \(https://www.npmjs.com/~angular\):

* @angular/core
* @angular/animate
* @angular/http
* @angular/router

aa

## Building a Nested Component

Using a Nested Component

