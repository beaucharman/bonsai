# Sass Directory

## Todo (Roadmap)

- Consider testing options (https://github.com/csswizardry/inuit.css)

## File Structure

`main.scss`

### Sass Functions
`options/_functions.scss`

### Mixins
`options/_mixins.scss`

### Sass Variables
`options/_variables.scss`

### Component styles
`styles/_components.scss`

Any self contained blocks of code or Javascript plugin related styles, for example: galleries and light boxes.

### Control styles
`styles/_controls.scss`

For forms and their related controls. Can also include base and project specific styles related to buttons and clickable, interactive controls.

### Global styles
`styles/_global.scss`

Base / global / elements styles, core boilerplate styles. This can include inline and block level elements, and thier basic styles.

### Helper styles
`styles/_helpers.scss`

Any modulated styles that help with cross browser compatibility and user feedback. thanks to http://html5boilerplate.com/

### Layout styles
`styles/_layout.scss`

Grid layouts and any global layout styles.

### Print Styles
`styles/_print.scss`

### Project styles
`styles/_project.scss`

Project related styles, pages specific and branding styles etc...

### Tabula Rasa
`styles/_tabularasa.scss`

The normalize styles, or other reset stylesheets. Taken from normalize.css, git.io/normalize, and http://html5boilerplate.com/, thank you :)

### Typography styles
`styles/_typography.scss`

Type and font styles, and related element styles. Can also include font declarations.

### Wordpress styles
`styles/_wordpress.scss`

WordPress related styles, and shortcode styles.  Default WordPress editor styles selectors are  found here http://digwp.com/2010/05/default-wordpress-css-styles-hooks/

## WordPress Theme Development
If using this with a WordPress theme, uncomment the `@import 'includes/wp-theme-declaration';` line in the `main.scss` file, and then add the appropriate information to that file. The `wp-theme-declaration.scss` file just contains:
```css
/**
 * Theme Name
 * ------------------------------------------------------------------------
 * style.css
 * Theme Name:   themename
 * Theme URI:    http://
 * Description:
 * Author:       @authorname | details
 * Author URI:   http://
 * Version:      1.0
 * Version Date: xx/xx/xxxx
 * License:
 * License URI:
 * ------------------------------------------------------------------------ */
```
