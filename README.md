# Node Generator [![Build Status](https://secure.travis-ci.org/easy-node/generator-easy-node.svg?branch=master)](https://travis-ci.org/easy-node/generator-easy-node)

> Create a node.js module with [Yeoman][], including nodeunit unit tests.

This generator is based on
[generator-node](https://github.com/yeoman/generator-node/), authored by the
yeoman team.

This is original from [generator-node](https://github.com/yeoman/generator-node/), but easy-node modify the following features.

1. Move `/test/` folder to root folder.
2. Move `/lib/` folder to root folder.
3. Add bower.json
4. Add component.json
5. <s>Add default keywords and ask for the keywords needed</s> *(generator-node add this feature)*
6. <s>Add cli.js</s> *(generator-node implement this)*
7. Add .travis.yml test for node 0.11
8. Not yet implement this *(Add an examples dir, with basic example template.)*

[Yeoman]: http://yeoman.io/


## Installation

Install the generator by running: `npm install -g generator-easy-node`.


## Usage

At the command-line, cd into an empty directory, run this command and follow the prompts.

```
yo easy-node
```

_Note that this template will generate files in the current directory, so be sure to change to a new directory first if you don't want to overwrite existing files._


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
