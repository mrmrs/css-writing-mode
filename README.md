# CSS WRITING MODE

  Mobile-first classes for css-writing-mode.
  Set the desired css-writing-mode on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-writing-mode
```
View on [npm](https://www.npmjs.org/package/css-writing-mode)


## File Size

1.7K writing-mode.css
1.2K writing-mode.min.css 
248B minified and gzipped

## The Code
```
.wm-horizontal-tb { writing-mode: horizontal-tb; }
.wm-rl-tb {         writing-mode: rl-tb; }
.wm-vertical-lr {   writing-mode: vertical-lr; }
.wm-vertical-rl {   writing-mode: vertical-rl;}
.wm-bt-rl {         writing-mode: bt-rl; }
.wm-bt-lr {         writing-mode: bt-lr; }
.wm-lr-bt {         writing-mode: lr-bt; }
.wm-rl-bt {         writing-mode: rl-bt; }

@media screen and (min-width: 48em) {
  .wm-horizontal-tb-ns { writing-mode: horizontal-tb; }
  .wm-rl-tb-ns {         writing-mode: rl-tb; }
  .wm-vertical-lr-ns {   writing-mode: vertical-lr; }
  .wm-vertical-rl-ns {   writing-mode: vertical-rl;}
  .wm-bt-rl-ns {         writing-mode: bt-rl; }
  .wm-bt-lr-ns {         writing-mode: bt-lr; }
  .wm-lr-bt-ns {         writing-mode: lr-bt; }
  .wm-rl-bt-ns {         writing-mode: rl-bt; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .wm-horizontal-tb-m { writing-mode: horizontal-tb; }
  .wm-rl-tb-m {         writing-mode: rl-tb; }
  .wm-vertical-lr-m {   writing-mode: vertical-lr; }
  .wm-vertical-rl-m {   writing-mode: vertical-rl;}
  .wm-bt-rl-m {         writing-mode: bt-rl; }
  .wm-bt-lr-m {         writing-mode: bt-lr; }
  .wm-lr-bt-m {         writing-mode: lr-bt; }
  .wm-rl-bt-m {         writing-mode: rl-bt; }
}

@media screen and (min-width: 64em)  {
  .wm-horizontal-tb-l { writing-mode: horizontal-tb; }
  .wm-rl-tb-l {         writing-mode: rl-tb; }
  .wm-vertical-lr-l {   writing-mode: vertical-lr; }
  .wm-vertical-rl-l {   writing-mode: vertical-rl;}
  .wm-bt-rl-l {         writing-mode: bt-rl; }
  .wm-bt-lr-l {         writing-mode: bt-lr; }
  .wm-lr-bt-l {         writing-mode: lr-bt; }
  .wm-rl-bt-l {         writing-mode: rl-bt; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

