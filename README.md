# Customer Portal Grid System
A Flexbox-based 12 column grid system that allows the columns to behave like cards or tiles.

[View Demo](https://redhataccess.github.io/cp-grid/index.html)

## Usage

```html
<div class="cp-grid" data-cp-grid="sm-2 md-4">
	<div class="cp-grid-item"></div>
	<div class="cp-grid-item"></div>
	<div class="cp-grid-item"></div>
	<div class="cp-grid-item"></div>
</div>
```
The `data-cp-grid=""` attribute allows you to denote the number of columns for each breakpoint.

## Optional Cards

```html
<div class="cp-grid" data-cp-grid="sm-2 md-4">
	<div class="cp-grid-item" data-cp-grid-bg="light-grey"></div>
	<div class="cp-grid-item" data-cp-grid-bg="light-grey"></div>
	<div class="cp-grid-item" data-cp-grid-bg="light-grey"></div>
	<div class="cp-grid-item" data-cp-grid-bg="light-grey"></div>
</div>
```
Applying the `data-cp-grid-bg=""` attribute allows you to assign an approved background color. Use `none` for transparent.

## Development

```
$ gulp
```

## Compile
```
$ gulp styles
```