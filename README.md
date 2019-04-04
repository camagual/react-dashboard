
<img src = "https://github.com/webninja1992/react-dashboard/blob/master/screenshots/dashboard-v1.png"/>

### Instructions of Usage :
- Run `npm install adminlte-reactjs`
- Include the stylesheets for the components, similar to the [widgets page](https://github.com/webninja1992/ReactJS-AdminLTE/blob/master/views/widgets.html)
- Include the library `var reactjsAdminlte = require('adminlte-reactjs')`. You may prefer the AMD style or the import statement.
- You can now begin using the components like this `var ProfileCard = reactjsAdminlte.ProfileCard`.
- If you don't need all the components, then you can choose to include only specific ones rather than the entire library. This can reduce your JS bundle size significantly `var StatTile = require('adminlte-reactjs/src/components/stat-tile')`

#### Installation : 

- Fork or clone this repo. Alternatively - if you have NPM installed, you can also do `npm install adminlte-reactjs`.
- Install nodejs and NPM
- Go to the project's root folder from your terminal and run `npm install`
- Run `npm run dev`
- Going to [http://localhost:8000](http://localhost:8000) will render an empty dashboard skeleton in the client-side using ReactJS. Clicking on one of the dashboard options on the left pane displays the original dashboards from AdminLTE.
- Go to [http://localhost:8000/widgets.html](http://localhost:8000/widgets.html) to see available widgets in ReactJS.

