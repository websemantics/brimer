```
                ______ CSS Goodies
               /
              /
        _____/____          _____        _
       /____/____/         | ___ \      (_)    
      /\   ☌    /\         | |_/ / _ __  _  _ __ ___    ___  _ __
     /  \  ____/__\__      | ___ \| '__|| || '_ ` _ \  / _ \| '__|    
    /    \/_________/      | |_/ /| |   | || | | | | ||  __/| |   
    \    /         /       |____/ |_|   |_||_| |_| |_| \___||_|   
     \  /         /      
      \/_________/         Github Primer CSS toolkit with a 'B'
      
      
  ░░░░░░░░░░▒▒▒▒▒▒▒▓▓▓▓▓███  W O R K   I N   P R O G R E S S  ███▓▓▓▓▓▒▒▒▒▒▒░░░░░░░░░░░


```

> Brimer is a CSS Framework built after [Primer](http://primercss.io/), GitHub’s internal CSS framework. The idea is to have the cake and eat it too by combining Github attractive clean style and Bootstrap extensive feature list. A GitHubby marriage made in heaven!

### [Showcase](http://websemantics.github.io/brimer)&nbsp;&nbsp;&nbsp;[Getting Started](#getting-started)&nbsp;&nbsp;&nbsp;[Submit Issue](https://github.com/websemantics/brimer/issues)


## Getting Started

Three quick start options are available:

- [Download the latest release](https://github.com/websemantics/brimer/archive/1.0.0.zip).
- Clone the repo: `git clone https://github.com/websemantics/brimer.git`.
- Install with [Bower](http://bower.io): `bower install brimer`.
- Install with [npm](https://www.npmjs.com/): `npm install brimer`.


### What's included

Within the download you'll find the following directories and files for the framework and the docs, logically grouping common assets and providing both compiled and minified variations,

```
brimer/
├── dist/
|   ├── css/
│   |   ├── brimer.css
│   |   ├── brimer.css.map
│   |   └── brimer.min.css
│   |   └── brimer.min.css.map
|   ├── js/
│   |   ├── brimer.js
│   |   └── brimer.min.js
├── js/
|   ├── dist/
│   |   ├── custom.js
│   |   └── custom.min.js
|   ├── src/
│   |   ├── custom.js
│   |   └── util.js
├── docs/
|   ├── dist/
|   ├── assets/
│   |   ├── brand
│   |   ├── css
│   │   |   ├── docs.css
│   │   |   └── docs.min.css.map
│   |   ├── js
│   |   └── scss
|   └── index.html
└── scss/
    └── primer

```

All css override styles for Bootstrap and Primer are stored in `scss` and `scss/primer` folders respectively, while compiled and minified CSS and JS are in `dist` folder.


## Contributions

We are more than happy to accept external contributions to the project in the form of feedback, bug reports and even better - pull requests :)

To start development on your local machine following these steps,

- First, clone,

  ```bash
  git clone https://github.com/websemantics/brimer
  ```

- Install npm dependencies,

  ```bash
  cd brimer

  npm i
  ```

- Build sass styles into `dist`,

  ```bash
  npm run build
  ```

- Build project pages into `_gh_pages`, and before running the following script, comment-out `baseurl` line in
`_config.yml` or set to empty string,

  ```bash
  npm run prep-release
  ```

- Watch changes and refresh browser automatically,

  ```bash
  npm run watch
  ```

- Deploy into Github Pages (owner),

  ```bash
  npm run deploy
  ```


## Screenshot

[![Brimer](https://raw.githubusercontent.com/websemantics/themeblr/master/docs/assets/img/brimer.png)](https://websemantics.github.io/brimer/)

Love the Github *repository buttons* used and want to use them to showcase your own GitHub repositories? the name is Bragit, [Brag It](http://websemantics.github.io/bragit/).


## Resource

[Primer](http://primercss.io/), The CSS toolkit and guidelines that power GitHub..

[Bootstrap 4](http://v4-alpha.getbootstrap.com/), The most popular HTML, CSS, and JS framework in the world for building responsive, mobile-first projects on the web.

[Themeblr](https://websemantics.github.io/themeblr/), A powerful CSS framework boilerplate and Bootstrap 4 themes builder .

[Bootstrap 4 Cheatsheet](https://hackerthemes.com/bootstrap-cheatsheet/), A quick reference for Bootstrap v4.0.0-alpha.3.


## Support

Need help or have a question? post a questions at [StackOverflow](https://stackoverflow.com/questions/tagged/brimer)

*Please don't use the issue trackers for support/questions.*


## Credits

This project was built using [Themeblr](https://websemantics.github.io/themeblr/), on top of the awesomeness known as [Bootstrap](https://github.com/twbs/bootstrap/).


## Copyright and license

[MIT license](http://opensource.org/licenses/mit-license.php)
Copyright (c) Web Semantics, Inc.
