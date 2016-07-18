# Buttons

> Component

The `wocss-components-button` module contains button `component`, a styled button that scales to any size.

Install using npm:

```sh
$ npm install wocss-components-button --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-components-button';
```

Then you can use the `c-button` class for a styled button:

```html
<button class="c-button" type="button">Cool</button>
<a class="c-button" href="#!">Awesome</a>
```

### Modifiers

* `o-button--outline` for a outline button.
* `o-button--oval` for a oval button.

## Dependencies

* [wocss-settings-defaults](https://github.com/wocss/settings.defaults)
* [wocss-settings-colors](https://github.com/wocss/settings.colors)
* [wocss-tools-bem-constructor](https://github.com/wocss/tools.bem-constructor)
