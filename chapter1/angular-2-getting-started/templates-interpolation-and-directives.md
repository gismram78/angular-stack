# Templates, Interpolation and Directives

## Overview

Building a template

Using a Component as a Directive

Building with interpolation

Adding logic and directives \(and Angular built-in directives\)

## Building a Template

Using:

* Inline `template`with single quotes ""
* Inline `template`with back ticks \(\`\`\) of ES 2015
* Linked template using `templateUrl`: './product-list.component.html'

### Build the Linked template

Create the HTML template into: /app/products/product-list.component.html

```
<div class="panel panel-primary">
    <div class="panel-heading">
        Product List
    </div>    
    <div class="panel-body">
        <div class="row">
            <div class="col-md-2">Filter by:</div>
            <div class="col-md-4">
                <input type="text" />
            </div> 
        </div>
        <div class="row">
            <div class="col-md-6">
                <h3>Filtered by:</h3>
            </div> 
        </div>
        <div class="table-responsive">
            <table class="table">
                <thead>
                    <tr>
                        <th>
                            <button class="btn btn-primary">
                                Show image
                            </button>    
                        </th>
                        <th>Product</th>
                        <th>Code</th>
                        <th>Available</th>
                        <th>Price</th>
                        <th>5 Star rating</th>    
                    </tr>    
                </thead>
                <tbody>
                </tbody>        
            </table>    
        </div>        
    </div>    
</div>
```

## Building the Component

Create the class Component into: /app/products/product-list.component.ts

```
import { Component } from '@angular/core';

@Component({
    selector: 'pm-products',
    templateUrl: './product-list.component.html'
})
export class ProductListComponent {

}
```

## Using a Component as a Directive

When a Component has a `selector `then this component is used as Directive. This means that we can insert this component template into any other component template by using the selector as an HTMLtag.

![](/assets/201import.png)

aaa

aa

## References

[http://getbootstrap.com/](http://getbootstrap.com/)

