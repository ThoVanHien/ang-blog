# Angular Project Blog App - Learning on youtube

## Static: Routing and Navigation

- src\app\app-routing.module.ts: adding `path` and `component` for `routes: Routes` variable. `pathMatch?`:
- Add `<outer-outlet></outer-outlet>` a template where you want to it show.

## Bootstrap: There are 3 ways to import bootstrap on angular app:

- > `npm i bootstrap@4.6`

1.  `angular.json` : push element `"node_modules/bootstrap/dist/css/bootstrap.min.css"` on `build` and restart app.
2.  `src\index.html`: not work.
3.  `styles.css`: @import "~bootstrap/dist/css/bootstrap.min.css";

## Common styles:

- :root {variable}
- body: font-size, color:text-primary, font-family

## Design part1:

1. Design header component
2. Design Category navbar header component
3. Design the Footer component
4. Design the Post Card Component
5. Design the Subscription Card component
