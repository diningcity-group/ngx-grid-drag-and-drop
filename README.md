- [English](https://github.com/diningcity-group/vue-color-picker#welcome-to-the-vue-color-picker) 

# Welcome to the Angular Grid Drag and Drop plug in

This repository is a fork of the awesome @sam-1994/ngx-drag-and-drop-grid.

This drag and drop plug in takes the same features as the previous plug in, but updated with Angular 10+ support.

# Table of contents

- [Installing](#installing)
- [Usage](#usage)
- [API](#api)

## Installing

To install from the command line:

````shell
npm install XXXXXXXXXX
````

## Usage

#### 1. Import the `XXXXXXXX`:

Finally, you can use ngx-translate in your Angular project. You have to import `XXXXXXXX` in the NgModule.

```ts
import {BrowserModule} from '@angular/platform-browser';
import {NgModule} from '@angular/core';
import {SamDragAndDropGridModule} from 'XXXXXXXXXXXXX';

@NgModule({
    imports: [
        BrowserModule,
        XXXXXXXXXXXXXX
    ],
    bootstrap: [AppComponent]
})
export class AppModule { }
```

#### 2. Use the component:

```ts
import {Component, OnInit} from '@angular/core';
import {XXXXXXXXXXXXXX} from 'drag-and-drop-grid-module';

@Component({
  selector: 'app-drag-and-drop-grid-example',
  templateUrl: './drag-and-drop-grid.component.html',
  styleUrls: ['./drag-and-drop-grid.component.sass']
})
export class XXXXXXXXXXXXXXXXXX implements OnInit {

  public list = [1, 2, 3, 4, 5, 6, 7, 8, 9];

  ngOnInit() {
  }
}
```

```html
<XXXXXXXXXXXX [items]="list" [columnNumber]="5">
  <div *XXXXXXXXXXXXX="let listItem; let i=index">
    Item {{listItem}}; Index {{i}}
  </div>
</XXXXXXXXXX>
```

## API

You can use the `XXXXXXXXXXX` directive to inject your custom template as grid items.
