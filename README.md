# css-unicode-bidi 0.0.6

Css module of single purpose classes for unicode bidi

#### Stats

282 | 28 | 28
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-unicode-bidi
```

#### With Git

```
git clone https://github.com/tachyons-css/css-unicode-bidi
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-unicode-bidi";
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
<link rel="stylesheet" href="path/to/module/css/css-unicode-bidi">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   UNICODE BIDI
*/
.ub-norm { unicode-bidi: normal; }
.ub-embed { unicode-bidi: embed; }
.ub-iso { unicode-bidi: isolate; }
.ub-bidi-override { unicode-bidi: bidi-override; }
.ub-iso-override { unicode-bidi: isolate-override; }
.ub-pt { unicode-bidi: plaintext; }
.ub-i { unicode-bidi: inherit; }
@media screen and (min-width: 48em) {
 .ub-norm-ns { unicode-bidi: normal; }
 .ub-embed-ns { unicode-bidi: embed; }
 .ub-iso-ns { unicode-bidi: isolate; }
 .ub-bidi-override-ns { unicode-bidi: bidi-override; }
 .ub-iso-override-ns { unicode-bidi: isolate-override; }
 .ub-pt-ns { unicode-bidi: plaintext; }
 .ub-i-ns { unicode-bidi: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ub-norm-m { unicode-bidi: normal; }
 .ub-embed-m { unicode-bidi: embed; }
 .ub-iso-m { unicode-bidi: isolate; }
 .ub-bidi-override-m { unicode-bidi: bidi-override; }
 .ub-iso-override-m { unicode-bidi: isolate-override; }
 .ub-pt-m { unicode-bidi: plaintext; }
 .ub-i-m { unicode-bidi: inherit; }
}
@media screen and (min-width: 64em) {
 .ub-norm-l { unicode-bidi: normal; }
 .ub-embed-l { unicode-bidi: embed; }
 .ub-iso-l { unicode-bidi: isolate; }
 .ub-bidi-override-l { unicode-bidi: bidi-override; }
 .ub-iso-override-l { unicode-bidi: isolate-override; }
 .ub-pt-l { unicode-bidi: plaintext; }
 .ub-i-l { unicode-bidi: inherit; }
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

ISC
