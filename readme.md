# css-grd

[![NPM](https://nodei.co/npm/css-grd.png?mini=true)](https://nodei.co/npm/css-grd/)
[![Downloads](https://img.shields.io/npm/dt/css-grd.svg)](https://www.npmjs.com/package/css-grd)

A powerful flex based grid system

## Introduction

Fully functional CSS Grid system in 6kb (or 4kb for the lite version).

## How to use

Simply include the library

```html
<link rel="stylesheet" href="grd.min.css" />
```

And use your grid

```html
<div class="grd grd-auto">
  <div>col 1<br />bigger<br />faster<br />stronger</div>
  <div>col 2</div>
  <div>col 3</div>
</div>
```

## Attributes usage

This system use attributes instead of classes to allow for a nicer experience

```html
<div class="grd">
  <div col="6" md="3">col="6" md="3"</div>
  <div col="6" md="3">col="6" md="3"</div>
  <div col="6" md="3">col="6" md="3"</div>
  <div col="6" md="3">col="6" md="3"</div>
</div>
```

## Demo and more

For usage, please look at the demo

See demo.html or https://codepen.io/lekoalabe/pen/xxPrJWr
