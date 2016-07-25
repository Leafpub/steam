# Steam

Steam is a minimal and responsive theme for [Postleaf](https://www.postleaf.org/), forked from [@epistrephein’s](https://github.com/epistrephein) Ghost theme.

It features a clean and essential style with single column layout, beautiful typography, two colors, customizable partials and some nice javascript enhancements.

## Customization

### Choose a theme color
By default Steam uses a flat green theme color.
To switch to another theme color, first replace `{{> theme-red}}` with `{{!> theme-red}}` in `header.hbs`, then choose your desired color among those available: i.e. to activate the orange theme replace `{{!> theme-orange}}` with `{{> theme-orange}}`.

To use a custom color, replace instead `{{!> theme-customcolor}}` with `{{> theme-customcolor}}` and change the three occurrences of `#111111` and `#000000` in `partials/theme-customcolor.hbs` with the colors you prefer.

### Customize the social icons
Change the given `a href` addresses in `partials/footer-social.hbs` or replace the icons with the ones you prefer using the [Font Awesome list](http://fortawesome.github.io/Font-Awesome/icons/), e.g. to add a Facebook icon add:

```
<a href="https://www.facebook.com/username" target="_blank" title="Facebook">
    <i class="fa fa-2x fa-fw fa-facebook"></i>
    <span class="hidden">Facebook</span>
</a>
```