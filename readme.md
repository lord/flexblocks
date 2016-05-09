<p align="center">
  <img src="https://raw.githubusercontent.com/lord/img/master/logo-flexblocks.png" alt="Flexblocks: Layout System" width="226">
  <br>
  <a href="https://travis-ci.org/lord/flexblocks">
    <img src="https://travis-ci.org/lord/flexblocks.svg?branch=master" alt="Build Status">
  </a>
  <br>
  This library is being developed
</p>

Flexblocks is a lightweight, easy-to-learn CSS layout system.

## Why Flexblocks?

Flexblocks was created to mitigate the two biggest pain points of new CSS users: alignment syntax, and margin edgecases. For a detailed explanation, check out the [announcement blog post](#TODOLINK).

## Installing Flexblocks

Installing Flexblocks is simple — if you're just using plain CSS, just download `dist/flexblocks-responsive.css`. If you're a SCSS user, download the contents of `src`, and just `include` the contents of `flexblocks-responsive.scss`.

## Using Flexblocks

Using Flexblocks is easy!

- There are only two main CSS classes you need to worry about — `row` and `col`. Applying `col` to an element makes all its children appear in a vertical column, on top of each other. Applying `row` to an element makes all its children appear in a horizontal row, next to each other.

- To align a bunch of elements, simply apply one of these classes to the elements' *parent* — `left`, `right`, `top`, `bottom`, `center`, `middle`. For clarification, `center` is horizontal centering, and `middle` is vertical centering. Hopefully, you won't have to use this too much.

- *Never use margin*. Instead, if you'd like elements to be spaced apart, apply a `gap-1` through `gap-5` class to the elements' parent. `row`s get spaced horizontally, `col`s get spaced vertically. Feel free to use padding liberally.

## Customizing Flexblocks

If you change the contents of `flexblocks-responsive.scss`, you can update the default widths of the `gap` classes, and add an optional prefix to all classnames.

## A Cheatsheet

Click to enlarge.

<img src="https://raw.githubusercontent.com/lord/img/master/cheatsheet-flexblocks.png" alt="Flexblocks: Layout System" width="400">
