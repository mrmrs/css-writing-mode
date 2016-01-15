# css-writing-mode 0.0.6

Css module of single purpose classes for writing mode

#### Stats

295 | 32 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-writing-mode
```

#### With Git

```
git clone https://github.com/tachyons-css/css-writing-mode
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-writing-mode";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-writing-mode">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   WRITING MODE
*/
.wm-horizontal-tb { writing-mode: horizontal-tb; }
.wm-rl-tb { writing-mode: rl-tb; }
.wm-vertical-lr { writing-mode: vertical-lr; }
.wm-vertical-rl { writing-mode: vertical-rl; }
.wm-bt-rl { writing-mode: bt-rl; }
.wm-bt-lr { writing-mode: bt-lr; }
.wm-lr-bt { writing-mode: lr-bt; }
.wm-rl-bt { writing-mode: rl-bt; }
@media screen and (min-width: 48em) {
 .wm-horizontal-tb-ns { writing-mode: horizontal-tb; }
 .wm-rl-tb-ns { writing-mode: rl-tb; }
 .wm-vertical-lr-ns { writing-mode: vertical-lr; }
 .wm-vertical-rl-ns { writing-mode: vertical-rl; }
 .wm-bt-rl-ns { writing-mode: bt-rl; }
 .wm-bt-lr-ns { writing-mode: bt-lr; }
 .wm-lr-bt-ns { writing-mode: lr-bt; }
 .wm-rl-bt-ns { writing-mode: rl-bt; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .wm-horizontal-tb-m { writing-mode: horizontal-tb; }
 .wm-rl-tb-m { writing-mode: rl-tb; }
 .wm-vertical-lr-m { writing-mode: vertical-lr; }
 .wm-vertical-rl-m { writing-mode: vertical-rl; }
 .wm-bt-rl-m { writing-mode: bt-rl; }
 .wm-bt-lr-m { writing-mode: bt-lr; }
 .wm-lr-bt-m { writing-mode: lr-bt; }
 .wm-rl-bt-m { writing-mode: rl-bt; }
}
@media screen and (min-width: 64em) {
 .wm-horizontal-tb-l { writing-mode: horizontal-tb; }
 .wm-rl-tb-l { writing-mode: rl-tb; }
 .wm-vertical-lr-l { writing-mode: vertical-lr; }
 .wm-vertical-rl-l { writing-mode: vertical-rl; }
 .wm-bt-rl-l { writing-mode: bt-rl; }
 .wm-bt-lr-l { writing-mode: bt-lr; }
 .wm-lr-bt-l { writing-mode: lr-bt; }
 .wm-rl-bt-l { writing-mode: rl-bt; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

