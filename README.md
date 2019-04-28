# css-flat

*css-flat* is a clean CSS flat file written in pure CSS. It can also be imported in LESS or SASS projects.

# Motivation

For custom projects we need full control of style of our components and therefore by-pass the default browser markup style.
[normalize.css](http://necolas.github.io/normalize.css/) offer a reset starter allowing to maintaining pre-style markups like title or list between each browsers, while
*css-flat* normalize and especially **flat** markups style. 

This one will be use to start project with the **flattest style as possible**.

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

`<h1>` *css-flat* will overwrite some values and return:
```css
h1 {
    display: block; /* default browser value */
    font-size: 1em; /* reset */
    margin: 0; /* reset */
    font-weight: normal; /* reset */
}
```

## Test

You can [test it online!](https://codesandbox.io/s/github/solid-js/css-flat/tree/master/?fontsize=14)

## Credit 

Written and maintained by [Solid JS core team](https://github.com/solid-js). 

## Licence

[MIT License](./LICENSE)

