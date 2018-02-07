# Angular, TypeScript and HTML Snippets for VS Code

This VS Code extension adds Angular (v2 or higher), TypeScript and HTML code snippets into your editor.

## How To Use the Snippets

Type one of the snippet names below (or part of it) and then press return.

### TypeScript Snippets

```
ag-Bootstrap                     - Bootstrap snippet
ag-AppModule                     - Create the root app module (@NgModule) snippet
ag-AppFeatureModule              - Angular app feature module (@NgModule) snippet
ag-AppFeatureRoutingModule       - Angular app feature routing module (@NgModule) snippet
ag-CanActivateRoutingGuard       - Create a CanActivate routing guard snippet
ag-CanDeactivateRoutingGuard     - Create a CanDeactivate routing guard snippet
ag-Component                     - Component snippet
ag-HttpService                   - Service with Http snippet
ag-HttpClientService             - Service with HttpClient snippet
ag-InputProperty                 - @Input property snippet
ag-InputGetSet                   - @Input property with get/set
ag-OutputEvent                   - @Output event snippet
ag-Pipe                          - Pipe snippet
ag-Routes                        - Angular routes snippet
ag-Route                         - Route definition snippet
ag-Service                       - Service snippet
ag-Subscribe                     - Observable subscribe snippet
ag-ConcatMap                     - ConcatMap snippet used to handle multiple observables returned from a service (Http calls or others)

```

### HTML Snippets

```
ag-ClassBinding              - [class] binding snippet
ag-NgClass                   - [ngClass] snippet
ag-NgFor                     - *ngFor snippet
ag-NgForm                    - ngForm snippet
ag-NgIf                      - *ngIf snippet
ag-NgModel                   - [(ngModel)] binding snippet
ag-RouterLink                - Basic routerLink snippet
ag-RouterLinkWithParameter   - [routerLink] with route parameter snippet
ag-NgSwitch                  - [ngSwitch] snippet
ag-NgStyle                   - [ngStyle] snippet
ag-Select                    - select control using *ngFor snipppet
ag-StyleBinding              - [style] binding snippet

```

In addition to typing the snippet prefix, you can also press Ctrl+Space on Windows or Linux, or Cmd+Space on Mac to activate the snippets.

## Installing the Angular TypeScript and HTML Snippets

```
Windows:  Select Ctrl+P and then type: ext install angular2-snippets
Mac:      Select ⌘+P and then type: ext install angular2-snippets 
```

After restarting the editor open a TypeScript file and type the “ag-” prefix to see the snippets.

NOTE: The VS Code extension gallery doesn’t allow projects to be renamed after they are initially created so “angular2-snippets” will get you the latest version of the snippets even though “2” is in the name.

The following [walk-through](https://code.visualstudio.com/docs/editor/extension-gallery) provides additional details.

