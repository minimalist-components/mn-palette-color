# mn-palette-color

A simple palette color, to define all colors of a project.


### Install

With bower

```sh
bower install --save mn-button
```

### Usage

Import the main file in your sass files, i.e.:

```scss
@import 'bower_components/sources/styles/mn-palette-color.scss'
```

This file include the following variables:

- $mn-primary-color
- $mn-accent-color
- $mn-warning-color

All these variables, just be sass objects, with different color shades. 
And most important, theses variables exists are [sass default variables](https://robots.thoughtbot.com/sass-default).

If you want ovewrite these in your projects, just assign new values to same variables, before of files where use it.
