![Logo](admin/material-webfont.png)
# ioBroker.material-webfont

[![NPM version](http://img.shields.io/npm/v/iobroker.material-webfont.svg)](https://www.npmjs.com/package/iobroker.material-webfont)
[![Downloads](https://img.shields.io/npm/dm/iobroker.material-webfont.svg)](https://www.npmjs.com/package/iobroker.material-webfont)
[![Dependency Status](https://img.shields.io/david/om2804/iobroker.material-webfont.svg)](https://david-dm.org/om2804/iobroker.material-webfont)
[![Known Vulnerabilities](https://snyk.io/test/github/om2804/ioBroker.material-webfont/badge.svg)](https://snyk.io/test/github/om2804/ioBroker.material-webfont)

[![NPM](https://nodei.co/npm/iobroker.material-webfont.png?downloads=true)](https://nodei.co/npm/iobroker.material-webfont/)


## material-webfont adapter for ioBroker

Material Design Icons by (https://materialdesignicons.com/) 

## Usage

Add basic-HTML and use **General -> CSS class**. (https://dev.materialdesignicons.com/getting-started/webfont)

### Basic ###
Each icon can be referenced by their name prefixed with *mdi-*. For instance to get the home icon *mdi-home*.

**Example:**  mdi mdi-home

### Rotate ###
    mdi-rotate-45 - Rotates 45 Degrees.
    mdi-rotate-90 - Rotates 90 Degrees.
    mdi-rotate-135 - Rotates 135 Degrees.
    mdi-rotate-180 - Rotates 180 Degrees.
    mdi-rotate-225 - Rotates 225 Degrees.
    mdi-rotate-270 - Rotates 270 Degrees.
    mdi-rotate-315 - Rotates 315 Degrees.

**Example:**  mdi mdi-account mdi-rotate-45

### Flip ###
    mdi-flip-h - Flip horizontal.
    mdi-flip-v - Flip vertical.

**Example:**  mdi mdi-account mdi-flip-h
**Note:** mdi-flip-* and mdi-rotate-* classes cannot be used on the same element at the same time.

### Spin ###
    mdi-spin - Spinning icon.
**Example:**  mdi mdi-loading mdi-spin

### More ###
To see more (/widgets/material-webfont/css/materialdesignicons.css)

## Changelog

### 0.0.1
* (om2804) initial release

## License
MIT License

Copyright (c) 2019 om2804 <om2804@mail.ru>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.