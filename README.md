# css-reset

*css-reset* is a clean CSS reset file written in pure CSS. Can also be imported in LESS or SASS projects. Inspired by [normalize.css](http://necolas.github.io/normalize.css/).

# Motivation

For custom projects we need full control of style of our components and therefore by-pass the default browser markup style.
[normalize.css](http://necolas.github.io/normalize.css/) offer a reset starter while maintaining but keep pre-style some markups like title or list.
*css-reset* allow to start a project with the **flattest style as possible**.

## Example

`<h1>` browser return:

```css
    h1 {
        display: block;
        font-size: 2em;
        margin-top: 0.67em;
        margin-bottom: 0.67em;
        margin-left: 0;
        margin-right: 0;
        font-weight: bold;
    }
```      

`<h1>` with css-reset will overwrite some values and return:
```css
    h1 {
        display: block; /* default browser value */
        font-size: 1rem; /* reset */
        margin: 0; /* reset */
        font-weight: normal; /* reset */
    }
```

## Credit 

Written and maintained by [Solid JS core team](https://github.com/solid-js). 

## Licence

[MIT License](./LICENSE)

