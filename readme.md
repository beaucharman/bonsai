# SASS Directory

One main.scss to rules them all, 

One folder so I can damn well find them.

## File Structure 

### Component styles 
`project/_components.scss`

Any self contained blocks of code or Javascript plugin related styles, for example: galleries and light boxes.

### Control styles
`project/_controls.scss`
  
For forms and their related controls. Can also include base and project specific styles related to buttons and clickable, interactive controls.

### SASS Functions
`project/_functions.scss`

### Global styles
`project/_global.scss`

Base / global / elements styles, core boilerplate styles. This can include inline and block level elements, and thier basic styles.

### Helper styles
`project/_helpers.scss`

Any modulated styles that help with cross browser compatibility and user feedback. thanks to http://html5boilerplate.com/

### Layout styles
`project/_layout.scss`

Grid layouts and any global layout styles.

### Media Queries
`project/_mediaqueries.scss`

### Mixins
`project/_mixins.scss`

### Print Styles
`project/_print.scss`

### Project styles
`project/_project.scss`

Project related styles, pages specific and branding styles etc...

### Tabula Rasa
`project/_tabularasa.scss`

The normalize styles, or other reset stylesheets. Taken from normalize.css, git.io/normalize, and http://html5boilerplate.com/, thank you :)

### Typography styles
`project/_typography.scss`

Type and font styles, and related element styles. Can also include font declarations.

### SASS Variables
`project/_variables.scss`

### Wordpress styles
`project/_wordpress.scss`

WordPress related styles, and shortcode styles.	Default WordPress editor styles selectors are	found here http://digwp.com/2010/05/default-wordpress-css-styles-hooks/

## WordPress Theme Development
If using this with a WordPress theme, replace the `main.scss` header comments with the following (making your project specific changes):
```css
/*	
  Theme Name:        themename
  Theme URI:         http://
  Description:       
  Author:            @authorname
  Author URI:        http://
  License:
  License URI:
  Version:           1.0
  Version Date:      001/02/2013
  Style Guide Notes: 
  General Notes:
------------------------------------------------ */
```
