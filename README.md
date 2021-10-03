# Unrive Bootstrap 5 Boilerplate

This is a Bootstrap 5 Boilerplate with Gulp 4+, cross-env, Sass, sourcemaps, concat, CSS & HTML minification, uglify, image optimization, template partials, BrowserSync.

- Bootstrap 5
- Gulp 4
- Sass
- Sourcemaps
- Concatenation
- CSS minification
- HTML minitification
- Uglify
- Image optimization
- Template partials
- BroswserSync, live reload

#### Install
> npm install

#### Start server
> gulp serve

#### Start server
> gulp serve

You should see a live browser at http://localhost:3000

Override Bootstrap's variables and create your custom styles

`src/scss/style.scss`

This will be automatically compiled to `src/css/styles.css`

Add custom scripts

`src/js/index.js`

#### Partials

You can add partials in `src/partials/`

Insert partial : <partial src="header.html"></partial>.

Examples are already added in this this project for header & footer.

#### Production
> gulp

If you want HTML, CSS minification & image optimization:

> npm run prod

Docs folder is the destination. You can now go docs/index.html and check the output.