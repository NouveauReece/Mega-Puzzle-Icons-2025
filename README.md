# Mega Puzzle Icons 2025
A collection of icons for Mega Puzzle 2025. All icons are available under the MIT license.  

## Catalogue
View the icon catalogue by visiting the [index page](https://nouveaureece.github.io/Mega-Puzzle-Icons-2025/) of this repository.

## Usage
When using these icons in HTML, use the `<svg>` and `<use>` tags. Then, include the `id` of the icon from [the catalogue]((https://nouveaureece.github.io/Mega-Puzzle-Icons-2025/)) after the `#` in the `href` and `xlink:href` attributes. In this example, the `mp-person` icon will be displayed and described by a screen reader as the "User Account Centre"
```
<svg width="40px" height="40px" aria-labelledby="useracc">
    <title id="useracc">User Account Centre</title>
    <use href="icons.svg#mp-person" xlink:href="icons.svg#mp-person"></use>
</svg>
```

## Accessibility
Remember that whenever one uses an icon, they must include one of the following on the `<svg>` tag. Learn more about [accessible SVGs on CSS-Tricks](https://css-tricks.com/accessible-svgs/).


| Accessible Attribute     | Usage     |
| ------------- | ------------- |
| `aria-label="description-here"` | A description of the icon when it has stand-alone meaning that must be communicated to screen readers |
| `aria-labelledby="id-here"` | If the icon is described by a `<title>`, include a reference to it via its id |
| `aria-hidden="true"` | The icon is decorative and should not be announced |

## Attributions
Some icons may have come from the following generously MIT-Licensed icon repositories:  
* [Box Icons](https://github.com/atisawd/boxicons)
* [Material Icons](https://github.com/google/material-design-icons)
* [Bootstrap Icons](https://icons.getbootstrap.com/)