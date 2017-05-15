# Custom Elements

This repository is an attempt to showcase the usage and viability of [web components][1], eventually providing users with a collection of native custom elements that are lightweight and easy to use.  

One of the goals of the experiment is to keep development simple going back to the roots of web development, using vanilla Javascript, have 0 build/compilation/transpilation steps, rely on native APIs and make components as self-sufficient as possible not having to include framework/libraries to make things work. There might be some boilerplate and code duplication but let's give the crazy idea of simply saving a file and reloading a browser it a try.

## Using components
1. Import: `<script src="path/to/some-component.js" async></script>`
2. Use: `<bl-some-component></bl-some-component>`
3. Be happy

While we wait for native modules or html imports to leave their limbo state, copy-paste or include this simple [template loader][2] before loading the components.  
0. Before other scripts: `<script src="path/to/templates.js"></script>` 

## Developing
1. Clone the repo and update the the git submodules(`git submodule update --init`).
2. Start a static server, like [simplehttp2server][3].

[1]: https://www.webcomponents.org/introduction
[2]: https://gist.github.com/olanod/ede8befb771057bb004c4f57be591640
[3]: https://github.com/GoogleChrome/simplehttp2server
