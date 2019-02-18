# Fischer Jemison's Base Web Styles

This is a pretty basic set of stylesheets that I found myself rewriting for different web projects, so I collected them all in this repository. 

The `sass` subdirectory follows Hugo Giraudel's [7-1 architecture pattern](https://sass-guidelin.es/#the-7-1-pattern), described in the linked page. Not all elements of the pattern are used as this is not a full website. This is not a fully realized CSS framework like bootstrap; rather, the intent is reduce upfront work on a new custom CSS project by laying out some common styles that are often duplicated in new projects. If you use these stylesheets as a base for your own project, you should feel free to copy the files and edit them directly as needed.

To compile, run:

```bash
$ npm i
$ npm run sass
```

The output will appear at the base of the directory in `main.css`. Building requires `npm` and uses `npm-sass` for compilation. 
