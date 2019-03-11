# greenhouse.io CSS builder

This is the codebase and CSS builder for [Canonical's Greenhouse page](https://boards.greenhouse.io/canonical/), a recruitment and applicant tracking system.

## Local development

For working on Sass files, you will want to dynamically watch for changes to rebuild the CSS whenever something changes.

To set up the watcher, open a new terminal window and run:

``` bash
npm run watch
```

## Deployment

To generate the custom CSS, run;

``` bash
npm run build
```

A CSS file will then generated at; `static/css/styles.css`

To implement the built CSS via Greenhouse's in-house job board configuration tools, navigate to the "Configure Your Job Board" page (you will need dev permission) and upload through the Custom CSS URL option.
