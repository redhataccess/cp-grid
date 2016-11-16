# Customer Portal Grid System
A Flexbox-based 12 column grid system that allows the columns to behave like cards or tiles.

[View Demo](https://redhataccess.github.io/cp-grid/index.html)

## Basic Usage

```html
<div class="cp-grid" data-cp-grid="sm-2 md-4">
	<div class="cp-grid-item"></div>
	<div class="cp-grid-item"></div>
	<div class="cp-grid-item"></div>
	<div class="cp-grid-item"></div>
</div>
```
The `data-cp-grid=""` attribute allows you to denote the number of columns for each breakpoint. For example, `sm-4` would make a grid of 4 columns for small screen devices and larger.

## Varying Column Widths

You can assign individual columns widths to any `.cp-grid-item` using the `data-cp-grid-size=""` attribute.

```html
<div class="cp-grid" data-cp-grid="sm-2 md-4">
	<div class="cp-grid-item" data-cp-grid-size="sm-12-cols md-6-cols"></div>
	<div class="cp-grid-item"></div>
	<div class="cp-grid-item"></div>
	<div class="cp-grid-item"></div>
</div>
```
The values of `data-cp-grid-size=""` define how many columns the respective *grid-item* will take up at that specific breakpoint. For instance, `sm-6-cols` will make the *grid-item* span across 6 columns on small screen devices and larger.

## Optional Cards

```html
<div class="cp-grid" data-cp-grid="sm-2 md-4">
	<div class="cp-grid-item" data-cp-grid-bg="light-grey"></div>
	<div class="cp-grid-item" data-cp-grid-bg="light-grey"></div>
	<div class="cp-grid-item" data-cp-grid-bg="light-grey"></div>
	<div class="cp-grid-item" data-cp-grid-bg="light-grey"></div>
</div>
```
Applying the `data-cp-grid-bg=""` attribute allows you to assign an approved background color. Leave empty or use `none` for transparent.

## Development

```
$ gulp
```

## Compile
```
$ gulp styles
```