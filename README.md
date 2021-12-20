# Typescript + esbuild Boiler Plate

Simple boiler-plate project that contains all of the required bits and pieces to
get a basic Typescript + esbuild project started for serving as a compiled
javascript bundle file, complete with static HTML, images, and CSS etc.

## Features:
* Compile all Typescript files & modules (and their dependencies) into a single
`bundle.js` file.

## Using this boiler plate for a new project

Simplest way to get a clean slate to start from is just to clone the existing
repo, delete the `.git/` dir and then re-initialise git in the new project.

- `git clone https://github.com/matt1/TypescriptEsbuildBoilerplate.git MyNewProject`
- `cd MyNewProject`
- `rm -rf .git/`
- `git init`

## Set up

You'll need to install the dependencies for this project with the following
command (dependencies are specified in package.json).

`npm install`

All static files are hosted in `www/` - the `index.html` file there expects
to execute `bundle.js`, which will be the compiled code. All other static
assets will serve as usual.

## Building

`npm run build`

## Dev server

`npm run serve`
