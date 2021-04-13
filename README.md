# 📡  SHIET

****S****ummon
****H****ighly
****I****ntelligent
****E****rror
****T****ransmission

![npm](https://aleen42.github.io/badges/src/npm.svg) ![](https://img.shields.io/npm/dt/shiet) ![](https://img.shields.io/npm/v/shiet) ![javascript](https://aleen42.github.io/badges/src/javascript.svg)


## Huh?
Have you ever dreamt of opening StackOverflow seconds after receiving an error?
Well, now you certainly can!

## Installation

```
npm install shiet --save
```

## Usage
Function takes two parameters:

```javascript
shiet(query: string | number, tags: Array<string>)
```

Tags parameter is ****optional****.

```javascript
import shiet from 'shiet';

try {
  ...
} catch (e) {
  shiet(e.message, ['angular material']);
}

```

## Contributions

****SHIET**** is an open-sourced package. Contributions of any shape
are welcome and appreciated.

## License
Copyright (c) 2020, Pijus Rancevas

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

Source: http://opensource.org/licenses/ISC

## Author
[Pijus Rancevas](https://github.com/pijus-r)
