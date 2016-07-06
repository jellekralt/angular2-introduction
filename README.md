# Angular 2 Introduction
Based on Reveal.js, a framework for easily creating beautiful presentations using HTML.

## Download
Download the PDF version [HERE](https://raw.githubusercontent.com/jellekralt/angular2-introduction/master/export/Angular2-Introduction.pdf)

## Read more on the subject
* [How to migrate an Angular 1 component to Angular 2](https://toddmotto.com/walkthrough-to-migrate-an-angular-1-component-to-angular-2/)
* [ngUpgrade](http://blog.thoughtram.io/angular/2015/10/24/upgrading-apps-to-angular-2-using-ngupgrade.html)
* [Angular 2 Docs](https://angular.io/docs/ts/latest/)

## Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (1.0.0 or later)

1. Clone this repo
   ```sh
   $ git@github.com:jellekralt/angular2-introduction.git
   ```

1. Navigate to the folder folder
   ```sh
   $ cd angular2-introduction
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view the presentation

   You can change the port by using `npm start -- --port 8001`.


## License

MIT licensed

Copyright (C) 2016 Jelle Kralt, https://jellekralt.com
