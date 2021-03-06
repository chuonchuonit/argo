# Architecture

Argo is an HTML5 interface for the OANDA trading platform.

The source code is located in the `src` folder.

The backend is based on [Node.js][].
The frontend is based on [hyperHTML][].

The application structure follows LIFT Principle, a Folders-by-Feature
structure.

`src/client/app/index.html` loads the scripts and the stylesheets.
`src/client/app/layout` contains the default view.
`src/client/app/services` contains the common services.
`src/client/app/components` contains the directives.

The other folders contain the implementation of each feature.

[Node.js]: http://nodejs.org/
[hyperHTML]: https://viperhtml.js.org/
[OANDA Rest APIs]: http://developer.oanda.com/rest-live/introduction/
[R]: http://www.r-project.org/
[rio]: https://github.com/albertosantini/node-rio
