# Sass Directory

> A Sass directory with simple & smart initial styles, and room to grow.

[View the example output of this Sass directory](http://beaucharman.github.io/sass-directory).

## Notes

**[Normalize](https://github.com/necolas/normalize.css)**

Normalize creates an invaluable blank slate for which to begin building application styles.

**Current version, Normalize.css v2.1.2**

Normalize.css is inlcuded in the `includes/_normalize.scss` file, however the newest version can be obtained via [Normalize's GitHub project page](https://github.com/necolas/normalize.css), or via Bower:

`bower install --save normalize-css`

**[Bourbon](http://bourbon.io/)**

Bourbon is a really awesome, lightweight and non opinionated / uncluttered mixin library.

This can be installed and then included in the Sass Directory via [Bourbon's GitHub project page](https://github.com/thoughtbot/bourbon).

**[Font Awesome](http://fortawesome.github.io/Font-Awesome/)**

> Font Awesome gives you scalable vector icons that can instantly be customized — size, color, drop shadow, and anything that can be done with the power of CSS.

You can include font awesome stright from the Bootsrap CDN, via:

```html
<link href="//netdna.bootstrapcdn.com/font-awesome/3.2.1/css/font-awesome.css" rel="stylesheet">
```

Or, check out [other options](http://fortawesome.github.io/Font-Awesome/get-started/).

## Todo (Roadmap)

- Mind blank at the moment

## File Structure

`main.scss`

### Includes

**Debug utility from inuitcss.com**

`includes/_debug.scss`

**Normalize github.com/necolas/normalize.css**

`includes/_normalize.scss`

**Wordpress**

`includes/_wordpress.scss`

Other files in this directory could include debugging tools (such as the debug.scss from http://inuitcss.com/), vendor style, etc.

### Options

**Functions**

`options/_functions.scss`

**Mixins**

`options/_mixins.scss`

**Project Settings**

`options/_settings.scss`

### Stylesheets

**Component styles**

`stylesheets/_components.scss`

Any self contained blocks of code or Javascript plugin related styles, for example: galleries and light boxes.

**Control styles**

`stylesheets/_controls.scss`

For forms and their related controls. Can also include base and project specific styles related to buttons and clickable, interactive controls.

**Global styles**

`stylesheets/_global.scss`

Base / global / elements styles, core boilerplate styles. This can include inline and block level elements, and thier basic styles.

**Helper styles**

`stylesheets/_helpers.scss`

Any modulated styles that help with cross browser compatibility and user feedback. thanks to http://html5boilerplate.com/

**Layout styles**

`stylesheets/_layout.scss`

Grid layouts and any global layout styles.

**Print Styles**

`stylesheets/_print.scss`

**Project styles**

`stylesheets/_project.scss`

Project related styles, pages specific and branding styles and so on.

**Typography styles**

`stylesheets/_typography.scss`

Type and font styles, and related element styles. Can also include font declarations.
