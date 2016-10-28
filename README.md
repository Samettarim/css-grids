# CSS grid set

![alt text](https://img.shields.io/badge/build-passing-brightgreen.svg "Build passing")
![alt text](https://img.shields.io/badge/css-tested-brightgreen.svg "CSS")
![alt text](https://img.shields.io/badge/tests-1%2F1-blue.svg "Tests 1/1")

My own css grid repository

> A curated list of awesome CSS grids

* [Tests Preview](test/img/tests.png)

### This repository has some grids for you:

* [l-cell](partials/_cell.css) 13 cell
* [l-coll](partials/_col.css) 24 col
* [l-grid](partials/_grid.css) 12 grid
* [l-row](partials/_row.css) 16 row

## Usage

### General Usage

In general you should include the file `grid.css` in `build` into your 
project css or less/sass folder structur and use the grid, col, cell or row as suggested in the docs for each grid, col, cell or row.

###### @import

```ruby
@import 'your-css-folder/grid.css';
```
```ruby
@import 'your-css-folder/grid.less';
```

##### Stylesheet

###### CSS

```ruby
<link rel="stylesheet" href="your-css-folder/grid.css">
```

##### Example

###### CSS

```ruby
@import 'your-css-folder/grid.css';
@import 'your-css-folder/base.css';
@import 'your-css-folder/layout.css';
```
###### LESS
```ruby
@import 'your-less-folder/grid.less';
@import 'your-less-folder/base.less';
@import 'your-less-folder/layout.less';
```

## Contribute

Please [file an issue](https://github.com/Samettarim/less-mixins/issues) if you
think something could be improved. Please submit Pull Requests when ever
possible.

## Built with

* [NetBeans](https://netbeans.org/) - NetBeans editor for error-free code

## Authors

* **Samet Tarim** - *All works* - [ProDeveloper](https://profiles.wordpress.org/prodeveloper/)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)