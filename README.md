just testing
<h1 align="center">
Blockly Samples <br /> <a href="https://github.com/google/blockly"><img src="https://tinyurl.com/built-on-blockly" /> </a>
</h1>

This repo contains self-contained sample projects demonstrating techniques to
include and extend the [Blockly](https://github.com/google/blockly) library.
It also contains [codelabs](codelabs/) and extension [packages](packages/)
released under the ``@blockly`` scope.

## Samples

### Integrating Blockly
- [``blockly-requirejs-sample``](examples/blockly-requirejs/): Loads RequireJS from a CDN and loads Blockly using ``AMD``.
- [``blockly-umd-sample``](examples/blockly-umd/): Loads the UMD build of Blockly (``blockly.min.js``), both from node_modules and from Unpkg.
- [``blockly-webpack-sample``](blockly-webpack/): Using Blockly in Webpack.
- [``blockly-node-sample``](examples/blockly-node/): Using Blockly in Node.js, loaded using require (``CommonJS``).
- [``blockly-angular-sample``](examples/blockly-angular/): Blockly in an Angular project, defines an Angular Blockly Component.
- [``blockly-react-sample``](examples/blockly-react/): Blockly in a React project, defines a React Blockly Component.
- [``blockly-svelte-sample``](examples/blockly-svelte/): Blockly in a Svelte project, defines a Svelte Blockly Component.
- [``blockly-vue-sample``](examples/blockly-vue/): Blockly in a Vue project, defines a Vue Blockly Component.

### Real-time Collaboration

- [``blockly-rtc``](examples/blockly-rtc/): Real-time collaboration environment on top of the Blockly framework.

## Prerequisites

Install [node](https://nodejs.org/) and [npm](https://www.npmjs.com/get-npm).

## Running

```
git clone https://github.com/google/blockly-samples
cd <any sample folder>
npm install
npm run start
```
Browse to http://localhost:3000

You may need to refer to a sample's README for further setup and running instructions.

## Support

Blockly has an active [developer forum](https://groups.google.com/forum/#!forum/blockly). Please drop by and say hello. Show us your prototypes early; collectively we have a lot of experience and can offer hints which will save you time. We actively monitor the forums and typically respond to questions within 2 working days.


## License

Apache 2.0
