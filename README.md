# CSS GRID SET

![alt text](https://img.shields.io/badge/build-passing-brightgreen.svg "Build passing")
![alt text](https://img.shields.io/badge/css-3.0%20tested-brightgreen.svg "CSS 3.0 tested")
![alt text](https://img.shields.io/badge/license-CCO-blue.svg "CCO 1.0")
![alt text](https://img.shields.io/badge/tests-4%2F4-blue.svg "Tests 4/4")

My own css grid repository

> A curated list of awesome CSS grids

* [Tests Preview](test/img/tests.png)

### This repository has some grids for you:

* [l-cell](partials/_cell.css) 13 cell
* [l-col](partials/_col.css) 24 col
* [l-grid](partials/_grid.css) 12 grid
* [l-row](partials/_row.css) 16 row

## Usage

### General Usage

In general you should include the file `grid.css` in `build` into your 
project css or less/sass folder structur and use the grid, col, cell or row as suggested in the docs for each grid, col, cell or row.

#### Example

###### @import

```less
@import 'your-css-folder/grid.css';
```
###### @link

```html
<link rel="stylesheet" href="your-css-folder/grid.css">
```

###### @use

12 grid
```html
<div class="l-grid--6">
    <p>Content</p>
</div>
<div class="l-grid--6">
    <p>Content</p>
</div>
<div class="l-clear"></div>
```

13 cell
```html
<div class="l-cell--6">
    <p>Content</p>
</div>
<div class="l-cell--7">
    <p>Content</p>
</div>
<div class="l-clear"></div>
```

16 row
```html
<div class="l-row--8">
    <p>Content</p>
</div>
<div class="l-row--8">
    <p>Content</p>
</div>
<div class="l-clear"></div>
```

24 col
```html
<div class="l-col--12">
    <p>Content</p>
</div>
<div class="l-col--12">
    <p>Content</p>
</div>
<div class="l-clear"></div>
```

## Contribute

Please [file an issue](https://github.com/Samettarim/less-mixins/issues) if you
think something could be improved. Please submit Pull Requests when ever
possible.

## Built with

* [NetBeans](https://netbeans.org/) - NetBeans editor for error-free code

## Authors

* **Samet Tarim** - *All works* - [ProDeveloper](https://www.tnado.com/author/prod3v3loper/)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)