# harp-flat-ui

> A comfortable, responsive, and functional framework built upon LESS and Bootstrap.

## Dependencies

* [NodeJS](http://nodejs.org/) – _Server-side JavaScript runtime_
* [Harp](http://harpjs.com/) – _The static web server with built-in preprocessing_

## Install

To install Flat UI, run the following command from the root of your Harp project:

```bash
harp install flat-ui
```

Your project will look something like this…

```
myproject/                  <-- your project root (or public dir if in framework-mode)
  |- components/            <-- harp puts components here
  |   +- harp-flat-ui/      <-- where this lib gets installed
  |       …
  |- main.less              <-- where you reference Bootstrap 
  +- index.jade             <-- where you reference main.css
```

## Link

Now, from within a `.less` file in your project, you can `@import` Bootstrap and Flat UI:

```less
@import "components/harp-bootstrap/less/_bootstrap.less";
@import "components/harp-bootstrap/less/_flat-ui.less";
```

Or, just a portion of Bootstrap:

```less
@import "components/harp-bootstrap/less/_variables.less";
@import "components/harp-bootstrap/less/_mixins.less";
@import "components/harp-bootstrap/less/_grid.less";
```

## Resources

* [Harp documentation](http://harpjs.com/docs)
* [LESS documentation](http://lesscss.org)
* [Bootstrap documentation](http://getbootstrap.com)
* [Flat UI demo](http://designmodo.github.com/Flat-UI/)

## License

This component is [Flat UI](https://github.com/designmodo/Flat-UI), which is MIT and Creative Commons Attribution 3.0 Unported licensed.