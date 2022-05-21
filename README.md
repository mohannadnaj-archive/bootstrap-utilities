# ⚠️ Bootstrap Utilities

⚠️ Deprecated. Bootstrap (5+) now ships with a distributed build of `utilities`, `grid`, `reboot` modules. You should use it, this package no longer relevant.

``` sh
npm install -S bootstrap
```
``` js
import 'bootstrap/dist/css/bootstrap-utilities.min.css';
```

CDN (for version 5.2.0-beta1, the latest at the time of this writing):

```
https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap-utilities.min.css

https://unpkg.com/bootstrap@5.2.0-beta1/dist/css/bootstrap-utilities.min.css
```
File size: 55.08 KB

----------

:warning: USE THE [DISTRIBUTION VERSION](https://github.com/MohannadNaj/bootstrap-utilities-dist). THIS IS THE GENERATOR.

----------

# Bootstrap Utilities

[![npm version](https://badge.fury.io/js/bootstrap-utilities.svg)](https://www.npmjs.com/package/bootstrap-utilities)
[![npm downloads](https://img.shields.io/npm/dt/bootstrap-utilities.svg)](https://www.npmjs.com/package/bootstrap-utilities)
[![jsdelivr hits](https://data.jsdelivr.com/v1/package/npm/bootstrap-utilities/badge)](https://www.jsdelivr.com/package/npm/bootstrap-utilities)

[Bootstrap 4 Utilities](http://getbootstrap.com/docs/4.1/utilities/borders/) without bootstrap. 

Because I like bootstrap's utilities, and sometimes I just need bootstrap's awesome utilities, nothing more.

## CDN

#### jsdelivr

```
https://cdn.jsdelivr.net/npm/bootstrap-utilities@4.1.3/bootstrap-utilities.css
```

#### unpkg

```
https://unpkg.com/bootstrap-utilities@4.1.3/bootstrap-utilities.css
```

## Installation

 - install the package:
 
``` sh
 npm install bootstrap-utilities --save
```

or link to [bootstrap-utilities.css](https://github.com/MohannadNaj/bootstrap-utilities-dist/blob/master/bootstrap-utilities.css) in your markup.
``` html
        <link rel="stylesheet" href="node_modules/bootstrap-utilities/bootstrap-utilities.css">
```

## Usage

Check [Bootstrap documentation](https://getbootstrap.com/docs/4.1/utilities/borders/) .

## Sass Usage

``` scss
@import "node_modules/bootstrap-utilities/bootstrap-utilities";

// or

@import "~bootstrap-utilities";

```

#### Note for Sass usage

This package distributes a bundled/compiled CSS. That's CSS built with the default Bootstrap Sass variables. Thus, Overriding Bootstrap's variables before importing this package won't take place.

