# Angular VS Code TypeScript and HTML Snippets 

This VS Code extension adds Angular (v2 or higher), TypeScript and HTML code snippets into your editor.

## How To Use the Snippets

Type one of the snippet names below (or part of it) and then press return.

### TypeScript Snippets

```
ag-Bootstrap                     - Bootstrap snippet
ag-AppModule                     - Create the root app module (@NgModule)
ag-AppFeatureModule              - Angular app feature module (@NgModule) snippet
ag-AppFeatureRoutingModule       - Angular app feature routing module (@NgModule) snippet
ag-CanDeactivateRoutingGuard     - Create a CanDeactivate routing guard
ag-Component                     - Component snippet
ag-HttpImport                    - Http import snippet
ag-HttpClientImport              - HttpClient import snippet
ag-HttpMap                       - Http map() snippet
ag-HttpClientMap                 - HttpClient map() snippet
ag-HttpService                   - Service with Http snippet
ag-HttpClientService             - Service with HttpClient snippet
ag-InputProperty                 - @Input property snippet
ag-OutputEvent                   - @Output event snippet
ag-Pipe                          - Pipe snippet
ag-Routes                        - Angular routes snippet
ag-Route                         - Route definition snippet
ag-Service                       - Service snippet
ag-Subscribe                     - Observable subscribe snippet

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

