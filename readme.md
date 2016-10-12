<p align="center">
  <img src="https://raw.githubusercontent.com/lord/img/master/logo-flexblocks.png" alt="Flexblocks: Layout System" width="226">
  <br>
  <a href="https://travis-ci.org/lord/flexblocks">
    <img src="https://travis-ci.org/lord/flexblocks.svg?branch=master" alt="Build Status">
  </a>
  <br>
</p>

Flexblocks is a lightweight, easy-to-learn CSS layout system.

## Why Flexblocks?

Flexblocks was created to mitigate the two biggest pain points of new CSS users: alignment syntax and margin edgecases. For a detailed explanation, check out the [announcement blog post](https://lord.io/blog/2016/flexblocks/).

## Installing Flexblocks

Installing Flexblocks is simple — if you're just using plain CSS, just download `dist/flexblocks-responsive.css`. If you're a SCSS user, download the contents of `src`, and just `include` the contents of `flexblocks-responsive.scss`.

## Using Flexblocks

Using Flexblocks is easy!

- There are two main CSS classes — `row` and `col`. Applying `col` to an element makes all its children appear in a vertical column, on top of each other. Applying `row` to an element makes all its children appear in a horizontal row, next to each other.

- These classes can be applied to a `row` or `col` to align items inside of it: `left`, `right`, `top`, `bottom`, `center` (horizontal centering), and `middle` (vertical centering).

- *Never use margin*. Instead, if you'd like elements to be spaced apart, apply a `gap-1` through `gap-5` class to the elements' parent. `row`s get spaced horizontally, `col`s get spaced vertically. Feel free to use padding liberally.

- Any of the classes above can be prefixed by a `x` to only apply on wide screens. For instance, `<div class="col xrow xcenter">` is a column on mobile, but a centered row on desktop.

## Customizing Flexblocks

If you change the contents of `flexblocks-responsive.scss`, you can update the default widths of the `gap` classes, and add an optional prefix to all class names.

## A Cheatsheet

Click to enlarge.

<img src="https://raw.githubusercontent.com/lord/img/master/cheatsheet-flexblocks.png" alt="Flexblocks: Layout System" width="400">
