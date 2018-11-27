# NgFlipDiv3D

This project show how using flip-div 3D component using [StencilJs] (https://stenciljs.com) in an Angular7 project, **without import script**.

This component made with StencilJs is tiny and have **zero** dependencies.


## How to build

Follow this steps, in root folder:
1. npm install
2. npm build
3. npm start


## How to analyze bundle

To run analyzer in dev and prod environment.

dev:
`npm run build-analyzer`

prod:
`npm run build-prod-analyzer`

And acessing `http://127.0.0.1:8888`


## How to use fli-div 3D

In `app.module.ts` include CUSTOM_ELEMENTS_SCHEMA.  :shipit:
Before that you need register the component in you `main.ts`.

import the ts loader of component
`import { defineCustomElements } from 'flip-div/dist/loader';`

Register component
`defineCustomElements(window);`


## How to use:

```
<flip-div height="300px" width="300px">
    <card-item class-names="my-custom-class">
        Front Item
        <!-- Insert you html here -->
    </card-item>
    <card-item class-names="my-custom-class">
        Back Item
        <!-- Insert you html here -->
    </card-item>
</flip-div>
```


## Technology

This project was done with:

 - node v11.2.0
 - Angular CLI 7.0.7
 - Angular 7.0.4


## References

[flip-div-3D GitHub](https://github.com/rafaelboschini/flip-div-3D)

[StencilJs] (https://stenciljs.com)
