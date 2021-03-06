# grunt-htmlcs

[![npm version](https://badge.fury.io/js/grunt-htmlcs.svg)](https://badge.fury.io/js/grunt-htmlcs)

Grunt task for HTML linter: [htmlcs](https://github.com/ecomfe/htmlcs).

## Installation

```
npm install grunt-htmlcs
```

## Usage

Add to the Grunt configuration:

```javascript
htmlcs: {
    all: {
        src: ['src/**/*.html']
    }
}
```

Load the task:

```javascript
grunt.loadNpmTasks('grunt-htmlcs');
```

And run it:

```
grunt htmlcs:all
```

See the simple [full example](example/Gruntfile.js).

## Configuration

Configuration of the htmlcs rules is done by adding a file `.htmlcsrc` next to your Gruntfile.
The config file indicates which rules should be run with which options.
See [default list](https://github.com/ecomfe/htmlcs/blob/master/lib/default/htmlcsrc) to get started.
