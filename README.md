# What
Module importing all components from @angular/material.

Add this to your project if you are using @angular/material so you don't have to import each material component to app.module every time you want to use new one.

# How 
Put material folder insinde app folder in your project.

Import whole module in your by adding this in app.module:

```
import { MaterialModule } from "./material/material.module";
```

```
//inside @NgModule block:
imports: [
    //... some other modules
    MaterialModule,
  ],
```
