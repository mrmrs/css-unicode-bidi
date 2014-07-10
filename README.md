# CSS UNICODE BIDI

  Mobile-first classes for css-unicode-bidi.
  Set the desired css-unicode-bidi on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-unicode-bidi
```
or download the css on github and include in your project.

## File Size


## The Code
```
.ub-norm {          unicode-bidi: normal; }
.ub-embed {         unicode-bidi: embed; }
.ub-iso {           unicode-bidi: isolate; }
.ub-bidi-override { unicode-bidi: bidi-override; }
.ub-iso-override {  unicode-bidi: isolate-override; }
.ub-pt {            unicode-bidi: plaintext; }
.ub-i {             unicode-bidi: inherit; }

@include break(not-small) {
  .ub-norm-ns {          unicode-bidi: normal; }
  .ub-embed-ns {         unicode-bidi: embed; }
  .ub-iso-ns {           unicode-bidi: isolate; }
  .ub-bidi-override-ns { unicode-bidi: bidi-override; }
  .ub-iso-override-ns {  unicode-bidi: isolate-override; }
  .ub-pt-ns {            unicode-bidi: plaintext; }
  .ub-i-ns {             unicode-bidi: inherit; }
}

@include break(medium) {
  .ub-norm-m {          unicode-bidi: normal; }
  .ub-embed-m {         unicode-bidi: embed; }
  .ub-iso-m {           unicode-bidi: isolate; }
  .ub-bidi-override-m { unicode-bidi: bidi-override; }
  .ub-iso-override-m {  unicode-bidi: isolate-override; }
  .ub-pt-m {            unicode-bidi: plaintext; }
  .ub-i-m {             unicode-bidi: inherit; }
}

@include break(large) {
  .ub-norm-l {          unicode-bidi: normal; }
  .ub-embed-l {         unicode-bidi: embed; }
  .ub-iso-l {           unicode-bidi: isolate; }
  .ub-bidi-override-l { unicode-bidi: bidi-override; }
  .ub-iso-override-l {  unicode-bidi: isolate-override; }
  .ub-pt-l {            unicode-bidi: plaintext; }
  .ub-i-l {             unicode-bidi: inherit; }
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

